# Video-Classification
Continuous video classification


We will explore the way continuously classify video as it’s captured, in an online system. continuous classification will solve lot of intresting problems in the real time world , what’s in front of a car for autonomous driving applications to understanding what’s streaming on a TV or CCTV. We’ll attempt to do the latter using only open source software and uber-cheap hardware. Specifically, TensorFlow on a Raspberry Pi with a PiCamera.Here we concentrate on whats on the CCTV.


By the time we’re done today, we should be able to classify what we see on our CCTV as either a normal image or a supesious image, running on our Raspberry Pi.



## Method
We’re going to collect data for offline training with a Raspberry Pi and a PiCamera. We’ll point the camera at a CCTV and record 10 frames per second, or more specifically, save 10 jpegs every second, which will comprise our “video”.

Code for capturing our images: [stream_images.py](https://github.com/sureshannapureddy/Video-Classification/blob/master/stream_images.py)

