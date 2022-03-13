# Semi-Global-Matching-GPU
SGM implementation with python and pyCUDA, each step can be followed in Jupiter notebook.

This implementation is designed to process my personal high-resolution stereo images(not KITTI) with long baseline and very large disparity, but here are the results of tests on KITTI benchmark.

​																						KITTI left image

<img src="https://github.com/Atlaszjr-star/Semi-Global-Matching-GPU/blob/main/kitti_left.png" alt="kitti_right" style="zoom: 50%;" />

​																						KITTI right image

<img src="D:\TUM\Semi-Global-Matching-GPU\kitti_right.png" alt="kitti_right" style="zoom:50%;" />

​																						Left disparity map

<img src="D:\TUM\Semi-Global-Matching-GPU\left_disparity_map.png" alt="left_disparity_map" style="zoom: 50%;" />

​																						Right disparity map

<img src="D:\TUM\Semi-Global-Matching-GPU\right_disparity_map.png" alt="right_disparity_map" style="zoom:50%;" />

​																Left disparity map after left-right-consistency check

<img src="D:\TUM\Semi-Global-Matching-GPU\Consistency_check_left_disp_map.png" alt="Consistency_check_left_disp_map" style="zoom:50%;" />

​																						Final left disparity map

<img src="D:\TUM\Semi-Global-Matching-GPU\Interpolated_left_disp_map.png" alt="Interpolated_left_disp_map" style="zoom:50%;" />



References:

1. https://github.com/beaupreda/semi-global-matching

2. https://github.com/dhernandez0/sgm

   
