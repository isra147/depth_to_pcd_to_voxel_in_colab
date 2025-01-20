THIS .IPYNB FILE IS FULLY EXECUTABLE IN COLAB.

Convert the input image format into .tif before applying all the transformations.

It's important to use an image captured with camera calibration. Replace fx, fy, cx, cy with your own camera intrinsics under the title "Depth Image to Point Cloud Formation."

If you did not calibrate your camera, you can still use a normal image as an experiment. However, the depth might not be accurate, which will affect the point cloud and voxel results.

You can change the voxel size under the title 'Downsampling Point Cloud and Voxelization', but it shouldn't be too low or too high.

Please open an issue if you encounter any bugs or have suggestions for improvement.

-------------------
## Colab Notebook

You can find the Colab notebook [here](https://colab.research.google.com/drive/12I2rFI4e1VKnW6_othZRDwxug05BpyaY?usp=sharing).

-------------------
