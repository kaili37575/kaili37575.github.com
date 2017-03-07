---
layout: project-detail
title: Object Tracking
cat: computer-vision
meta: Tracking objects by matching the interested points in each frame.
image: tracking-object1.png
---
## Object Tracking
* green box is ground truth value;
* red box is predicted value;

<video width="320" height="240" controls="controls">
  <source src="{{site.baseurl}}/video/obj-tracking.mp4" type="video/mp4" />
</video>


Matching points 
When there are only a few good matching points, the accuracy of matching point are more important.<br>
So I set matching MaxRatio=0.6 by default.<br>
<img src="{{site.baseurl}}/img/projects/tracking-object2.png" alt="Photo of {{project.title}}" width="350" height="170">

[Source code and details](https://github.com/kaili37575/object-tracking/)