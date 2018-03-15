# Direct Sparse Odometry with Saving Point Cloud Data
DSO with additional function for saving point cloud data. You can use it to show point cloud which made from DSO on 3D viewer like Mesh Lab or OpenGL, VTK. It can save point cloud data as a PCD file.

## Installation
You can install it to follow https://github.com/JakobEngel/dso.

## Usage
It also same thing https://github.com/JakobEngel/dso. It can use DSO on using dataset or realtime ROS.
To use DSO with saving Point cloud data, You just add parameter option for sampleoutput.
 Example: $ rosrun dso_ros dso_live image:=/mv_25001549/image_raw calib=/home/neoplanetz/catkin_ws/src/dso_ros/camera.txt sampleoutput=1 quiet=1 nolog=1
 
 And press the 'Save PCL' button when you want to save point cloud data.
 
 
