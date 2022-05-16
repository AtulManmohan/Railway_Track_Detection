# 1. Objective

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftamasino52%2FRailway_detection)](https://hits.seeyoufarm.com)

The project deals with the detection of cracks in railway tracks. Unless these defects are detected and controlled earlier, they may lead to multiple derailments, resulting in heavy loss of life and property. A proposed rail crack detection detects the faulty rail track automatically without human intervention (Manual Survey), using the cameras installed at the front of the trains to only register the areas corresponding to the tracks.

# 2. Requirements
```
pip install -r requirements.txt
```

# 3. Run
```
python main.py --input video/test1.mp4
```

# 4. Architecture

<img src="/Railway_introduce/architecture.jpg">

# 5. Process

<img src="/Railway_introduce/process.png">
From the top, the original images, black-and-white images, histogram smoothing images, blurry images, motionblur images, convolution images, sliding windows and prediction lines are shown in order.


# 6. Example

<img src="/Railway_introduce/1.JPG"><img src="/Railway_introduce/2.JPG">
<img src="/Railway_introduce/3.JPG"><img src="/Railway_introduce/4.JPG">
<img src="/Railway_introduce/5.JPG">
