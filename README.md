# ros-o

![ROS-O logo](https://avatars.githubusercontent.com/u/99648569?s=230&v=4)

This organization bundles patches to have ROS One-specific repositories build on recent OS distributions.
Overall we provide a common place for multiple packaging efforts (including Debian and RoboStack) to share patches and provide upstream git branches that are expected to compile on recent OS distributions.
The goal is *not* to actively continue development on these packages here, but to maintain actively used packages in a state that can be used on newer systems.

This project is a volunteer effort and no fixed set of target platforms is defined as requirements will change in the future.
When adding new patches we encourage to keep compatibility with prior versions of upstream dependencies.
As most compatibility patches rework only marginal aspects of the code base this is mostly feasible.

# 10-minutes What's-This-All-About at ROSCon 2022

[![Talk at ROSCon 2022](http://i.vimeocdn.com/video/1540267138-484107074d66c143f5b8289ef6667dce9bceb655211849672f57fe30645cfe17-d_640)](https://vimeo.com/showcase/9954564/video/767158063)

# Get involved

If you have questions or want to get in touch regarding this project please [start a discussion in this repository](https://github.com/ros-o/ros-o/discussions).

If you want continue development of existing ROS One packages with support for newer distributions (e.g., in new upstream branches in the original repository or a fork) feel free to do so and each upstream package distributors can decide whether or not they want to package your version.
To notify the community you can post a discussion here as well.
