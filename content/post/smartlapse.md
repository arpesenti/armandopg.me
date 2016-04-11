+++
date = "2015-12-28T16:49:41+01:00"
draft = false
title = "Smartlapse"
+++

{{< youtube 1MegHzwU6U8 >}}

Time-lapse photography is a technique whereby the frequency at which film frames are captured (the frame rate) is much lower than that used to view the sequence. Online there are hundreds of thousands of webcams that record images at regular intervals of 10-30 minutes. By merging these sequences of photos is possible to obtain beautiful videos. Smartlapse is an image processing pipeline that I am implementing to improve the smoothness of these videos. In the example above I have created a comparison between a *timelapse* and a *smartlapse* from a day of recording of the webcam [Vallée Blanche Arete from Aiguille du Midi - Chamonix](http://amos.cse.wustl.edu/camera?id=18982#20160411_090541).    
<!--more-->
[AMOS](http://amos.cse.wustl.edu) (Archive of Many Outdoor Scenes) is a great place to find an extensive archive of public avaible webcams.  

At the moment the pipeline consist of two main processing steps:

- exposure fusion with decaying between consecutive images  
- incremental time-based morphing 
