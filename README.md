Usefull lines 
Launch camera in ROS2
ros2 launch orbbec_camera ob_camera.launch.py \
  color_width:=1920 color_height:=1080 color_fps:=15 color_format:=MJPG \
  depth_width:=640 depth_height:=576 depth_fps:=30 depth_format:=Y16 \
  ir_width:=640 ir_height:=576 ir_fps:=30 ir_format:=Y16

