## Dataset

This dataset has 810 dynamic videos captured from 5 dynamic scenens ("Meetingroom"scene, "Livingroom"scene, "Bathroom"scene, "Street"scene and "Industrialparts"scene), including 405 multi-focus videos and 405 all-in-focus videos. Each video is a 3-frame specific focus video or a 3-frame all-in-focus video with 1920x1080 resolution. At present, for each scene, we provide 81 multi-focus images at the first frame with 240x135 resolution for download. The complete dataset will be released upon publication.

## Code

The source codes for our extensive validation experiments on depth estimation, 3D reconstruction and novel view synthesis tasks are now available. Please refer to the [Code](https://github.com/North-Li/MVMF-VIDEO/tree/main/Code) folder.

## Environment

- Python >= 3.7
- PyTorch >= 1.4.0 is recommended
- opencv-python = 4.5.1
- matplotlib
- tensorboard
- pytorch_msssim
  
## Results

We release all the depth estimation, 3D reconstruction and novel view synthesis comparison results between MVMF-VIDEO and conventional multi-view video. For each scene, we reconstruct 81 dynamic depth map videos, 1 dynamic 3D point cloud video and synthesize 120 dynamic novel view videos. Please refer to the [Results](https://github.com/North-Li/MVMF-VIDEO/tree/main/Results) folder.

## Declare

This dataset and results cannot be used for commercial purposes. For non-commercial research or educational purposes, please inform us for our permission via yangyou AT hust DOT edu DOT cn.
