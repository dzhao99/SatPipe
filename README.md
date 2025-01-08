# SatPipe

## from SatPipe: Deterministic TCP Adaptation for Highly Dynamic LEO Satellite Networks

### Rebuffering Comparison between BBR and SatPipe

In order to visualize SatPipe's effect on reducing the freezing frame during video transmission, we compare the stall rate of a fixed bitrate video over a period of time.

![Image: Rebuffering_Explanation.jpg](https://github.com/dzhao99/SatPipe/blob/main/DASH/SatPipe_vs_BBR.jpg)

The left side of the image represents the results of the BBR, and the right side of the image shows the results of SatPipe. A buffer level of 0 means the video is stalled. We can tell that SatPipe reduces rebuffering time down to 2 seconds, 15 seconds less than BBR in a 2-minute video. The video recording time is close to ensure that the backbone network does not fluctuate much.



The full video is available [here](https://github.com/dzhao99/SatPipe/blob/main/DASH/SatPipe_vs_BBR.mp4)

The source code and intruction can be found [here](https://github.com/dzhao99/SatPipe/tree/main/Code)

### Acknowledgement

This research was supported by Cisco Research.

<p align="center">
<img src="https://github.com/dzhao99/SatPipe/blob/main/cisco-logo-blue.jpg" width=20% height=20%>
</p>