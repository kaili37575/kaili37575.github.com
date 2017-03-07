---
layout: project-detail
title: Interested Point
cat: computer-vision
meta: Detect Harris Corner on two photos contain same object but with different perspective.
image: interested-point.png
---
## Interested Point

### Algorithm Steps:
1. get interested points using Harris algorithm
get_interest_points(image, feature_width)<br>
2. find features for each interested points using SIFT method
get_features(image, x, y, feature_width)<br>
3. compute Euclidean distance for each feature to match vailed interested points
match_features(features1, features2)<br>

[Source code and details](https://github.com/kaili37575/interested-point)