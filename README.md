microstrain_3dmgx2_imu
==========


## Before Launch

Install the udev rule for the Microstrain 3DM-GX3-25 IMU by copying the file in the udev directory to `/etc/udev/rules.d/` and restarting udev with `udevadm control --reload-rules`. This should create a symlink at /dev/microstrain which will make the included launch file work. Otherwise, edit the "port" param in the launchfile to reflect whatever port the device is connected to (e.g., `/dev/ttyACM0`).
