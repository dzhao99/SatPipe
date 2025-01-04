# SatPipe

### from *SATPIPE: Deterministic TCP Adaptation for Highly Dynamic LEO Satellite Networks

### Rebuffering Comparison between BBR and SatPipe

In order to visualize SatPipe's effect on reducing the freezing frame during video transmission, we compare the stall rate of a fixed bitrate video over a period of time.

![Image: Rebuffering_Explanation.jpg](https://github.com/dzhao99/SatPipe/blob/main/SatPipe_vs_BBR.jpg)

The left side of the image represents the results of the BBR, and the right side of the image shows the results of SatPipe. A buffer level of 0 means the video is stalled. We can tell that SatPipe reduces rebuffering time down to 2 seconds, 15 seconds less than BBR in a 2-minute video. The video recording time is close to ensure that the backbone network does not fluctuate much.



The full video is available [here](https://github.com/dzhao99/SatPipe/blob/main/SatPipe_vs_BBR.mp4)
