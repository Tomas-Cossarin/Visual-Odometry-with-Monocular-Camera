# 3D Reconstruction from Stereo Pair


The objective of this program was to perform visual odometry only using a single camera.

The input data is frames from a video of a pedestrian with a camera walking the perimeter of a building. The first frame is shown below.

![first_frame](first_10_images/1540479358.061281.png)

## Step 1: Feature Matching
Features were detected in each frame using ORB and matched with the next frame using a brute-force matcher. An example of these matches is shown below.

![matches](matches.png)