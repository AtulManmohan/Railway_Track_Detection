# Abstract
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftamasino52%2FRailway_detection)](https://hits.seeyoufarm.com)

The project was developed as a base technology for autonomous train traffic, with only the areas corresponding to the tracks from the cameras installed at the front of the trains. This Repository was created in 2019 as part of Soongsil University's industry-academic cooperation project. The architecture and code will be used to create the thesis, and you can use them as you wish after the license is specified.

# Requirements
```
pip install -r requirements.txt
```

# Run
```
python main.py --input video/test1.mp4
```

# Architecture
<img src="/Railway_introduce/architecture.jpg">

# Process
<img src="/Railway_introduce/process.png">
From the top, the original images, black-and-white images, histogram smoothing images, blurry images, motionblur images, convolution images, sliding windows and prediction lines are shown in order.

# Example
<img src="/Railway_introduce/1.JPG"><img src="/Railway_introduce/2.JPG">
<img src="/Railway_introduce/3.JPG"><img src="/Railway_introduce/4.JPG">
<img src="/Railway_introduce/5.JPG">
