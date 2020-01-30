microstrain_3dmgx2_imu
==========


## Before Launch

Install the udev rule for the Microstrain 3DM-GX3-25 IMU by copying to `/etc/udev/rules.d/`. This should create a symlink at /dev/microstrain which will make the included launch file work. Otherwise, edit the "port" param in the launchfile.
