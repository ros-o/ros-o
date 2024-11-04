# ROS-O

![ROS-O logo](https://avatars.githubusercontent.com/u/99648569?s=230&v=4)

This organization bundles patches to have ROS One-specific repositories build on recent OS distributions.
Overall we provide a common place for multiple packaging efforts (including Debian and RoboStack) to share patches and provide upstream git branches that are expected to compile on recent OS distributions.
The goal is *not* to actively continue development on these packages here, but to maintain actively used packages in a state that can be used on newer systems.

This project is a volunteer effort and no fixed set of target platforms is defined as requirements will change in the future.
When adding new patches we encourage to keep compatibility with prior versions of upstream dependencies.
As most compatibility patches rework only marginal aspects of the code base this is mostly feasible.

# How To Run It

There is more than one way to build and use ROS-O for newer systems.
The most prominent online resource is https://ros.packages.techfak.net/, which provides provides a deb repository for newer Ubuntu systems.
These packages **are compatible with the ROS2 packages available from https://packages.ros.org**.

An advanced project to build ROS-O packages for various Debian-based distributions is the [ros-o-builder](https://github.com/v4hn/ros-o-builder/).
These packages are explicitly built on Debian-maintained ROS packages to facilitate further work in packaging ROS-O officially in Debian.
However, this means they are not compatible with external pre-built ROS2 packages.

More ways to build ROS-O packages are discussed [in this discussion thread](https://github.com/ros-o/ros-o/discussions/4).

# 10-minutes What's-This-All-About at ROSCon 2022

[![Talk at ROSCon 2022](http://i.vimeocdn.com/video/1540267138-484107074d66c143f5b8289ef6667dce9bceb655211849672f57fe30645cfe17-d_640)](https://vimeo.com/showcase/9954564/video/767158063)

# Get involved

If you have questions or want to get in touch regarding this project please [start a discussion in this repository](https://github.com/ros-o/ros-o/discussions).

If you want to continue development of existing ROS One packages with support for newer distributions (e.g., in new upstream branches in the original repository or a fork) feel free to do so and each upstream package distributor can decide whether or not they want to package your version.
To notify the community you can post a discussion here and/or on ros discourse as well.
