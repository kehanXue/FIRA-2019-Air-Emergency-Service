# FIRA-2019-Air-Emergency-Service

The final version packages for [FIRA-2019 Air Emergency Service](http://www.firaworldcup.org/VisitorPages/show.aspx?IsDetailList=true&ItemID=4411,1) NPUSoar team, finally we won the 1st place.

This repository mainly contains some git submodules：

- [`fira_esi`](https://github.com/kehanXue/fira_esi/tree/ec18150cc9866f89a26795fd73b42b7cc28d00eb): The main ROS package of the robot. Include the UAV behavior, workflow (use FSM) and vision detection.
- [`plot_path`](https://github.com/kehanXue/plot_path/tree/bb09748b43fef9b407620869154a6f2c2ea21676): A mini package for plotting the UAV's trajectory.
- [`px4_indoor_setup`](https://github.com/kehanXue/px4_indoor_setup/tree/3c68fa9783aa645c9b315c4ccdc732bab2d42598): A mini package for forwarding vision odometry data to PX4 filght controller, through mavros.
- [`px4_modules_test`](https://github.com/kehanXue/px4_modules_test/tree/b68092c7bedfd7859e95291a7072ddc3df3c92d0): A package for testing mavros with PX4 in simulation env(Gazebo).
- [`zed-ros-wrapper`](https://github.com/kehanXue/zed-ros-wrapper/tree/ba83f7d64513f827cc0bf17da61916997fe58656): ZED Stereo Camera driver. 
- [`MG995_key`](https://github.com/WeiGuo12138/MG995_key/tree/e0aa2ff0a47e00a8e595eb7ce25c13914db1e466): A driver for our mechanical claw.

> For some reasons, detailed documentation on the code is temporarily unavailable. Very sorry!

Videos:
- [Video1](https://youtu.be/tVGnO_dZ_lM)
- [Video2](https://youtu.be/aOoP80PxOgs)
