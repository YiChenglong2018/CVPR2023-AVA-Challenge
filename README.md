# CVPR2023-AVA-Challenge
The First Place Solution for CVPR 2023 AVA Challenge - Keypoint Track.
This paper presents the first place solution for CVPR2023 AVA Accessibility Vision and Autonomy Challenge - Keypoint Track. We designed our solution based onTop-down method, which applied CBNetV2 [5] as detectorand followed by single-object pose estimator. During thefirst stage, we applied Swin-Large [6] as CBNetV2 backbone, and some data augmentation policies were also used,including Auto Augmentation [7], Mixup [3], Copy Paste,Horizontal flip and Multi-scale training; during the secondstage, we applied VIT-Huge [4] as a strong encoder. As aresult, we got 90.96 AP on the test set.
https://accessibility-cv.github.io/index.html#challenge
