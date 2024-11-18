使用方法

要播放文件，请使用以下命令：

rosbag play jiantu2.bag

要使用提供的subscriber node subscribe /driver/encoder 话题，请运行：

rosrun my_rosbag_example encoder_subscriber

要使用提供的subscriber node subscribe /driver/eul 话题，请运行：

rosrun my_rosbag_example eul_listener.py

要使用提供的subscriber node subscribe /driver/imu 话题，请运行：

rosrun my_rosbag_example imu_listener.py

要使用提供的subscriber node subscribe /driver/mag 话题，请运行：

rosrun my_rosbag_example mag_listener.py

要使用提供的subscriber node subscribe /driver/scan 话题，请运行：

rosrun my_rosbag_example scan_listener.py
