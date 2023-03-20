# Demo of SAFR(A Real-Time Communication System with Adaptive Frame Rate)

[![Demo of SAFR](https://res.cloudinary.com/marcomontalbano/image/upload/v1679299276/video_to_markdown/images/youtube--XNW-uDKIOg8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=XNW-uDKIOg8 "Demo of SAFR")

To intuitively compare the transmission performance of SAFR and BASE, we make a demo to demonstrate the videos viewed on the receiver side of SAFR and BASE (above: SAFR, below: BASE). Since the SAFR system introduces a VFI module on the receiver side, the illustrated video (above) is derived after frame interpolation process in SAFR system. The demo experiment is conducted on a network trace with severe bandwidth flunctuations ([250K, 1M]bps). Watermarks are further added to the bottom-left corner of each frame, to clearly present the frame index and corresponding frame delay.

For better visualizing the effect of frame dropping and presenting the QoE supuriority of SAFR, all the video frames of SAFR and BASE are aligned strictly during playing, and the missing frames are replaced with fully black frames labeled “Missing”.

Due to the upload size limitation of youtube, the demo videos of SAFR and BASE are further compressed after being put together. So please note that the demo videos’ visual quality is unequal to the actual visual quality on the receiver side. However, the uncompressed raw videos are uploaded to the Google driver as well (https://drive.google.com/file/d/1LnnHO9DBllGqnHzd6Gu7aBxEm2wK2Yx0/view?usp=share_link), please check the uncompressed version for better viewing experience.

The average metrics of the two videos mentioned above (excluding the full black frame) are presented as follows:  
**SAFR: {VAMF: 72.4564, Frame Delay: 235 ms, Frame Loss Rate: 0.71%}**  
**BASE: {VAMF: 69.1295, Frame Delay: 421 ms, Frame Loss Rate: 5.58%}**

video source: Xiph.org Video Test Media [derf’s collection]. [Online] Available: https://media.xiph.org/video/derf/
