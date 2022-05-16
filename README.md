# 1. Objective

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftamasino52%2FRailway_detection)](https://hits.seeyoufarm.com)

The project was developed as a base technology for autonomous train traffic, with only the areas corresponding to the tracks from the cameras installed at the front of the trains.

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
