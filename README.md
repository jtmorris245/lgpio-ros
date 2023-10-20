
lgpio is a library for Linux Single Board Computers (SBC) which allows control of the General Purpose Input Outputs (GPIO).

This package is a ***C/C++ Library Only*** ROS packaging of the lgpio library.
This does not include the Python, or remote/daemon functionality.
Please feel free to make pull requests adding the remote/daemon functionality.
I don't have enough experience with ROS to tell if combining the python module into the same package is a good idea, but if it is, please feel free.

Keeping with the original project, this package is released with the Unlicense.
You may use this project as you see fit.

For information, examples, etc, please see the upstream project  [here](https://github.com/joan2937/lg).

## Features

* reading and writing GPIO singly and in groups
* software timed PWM and waves
* callbacks on GPIO level change
* notifications via pipe on GPIO level change
* I2C wrapper
* SPI wrapper
* serial link wrapper

* ~~@daemon interface~~
* ~~access control (daemon interface)~~
* ~~file handling (daemon interface)~~
* ~~creating and running scripts (daemon interface)~~
* ~~network access (daemon interface)~~

