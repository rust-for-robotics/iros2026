---
sequence_id: 12
speaker: Yuyuan Yuan
time: 15:15 – 15:45
title: "From ROS to Rust: Hiroz, Zenoh, and a Robotics Stack You Can `cargo build`"
# webpage: https://jane.doe
# affil: Buzz University
# affil_link: https://buzz.edu
img: zetta.png
# affil2: BuzzFizz Corp
# affil2_link: https://buzzfizz.corp
---

This talk covers why the two existing Rust-in-ROS-2 approaches each involve real trade-offs—ros2_rust wraps the C RCL layer and stays wire-compatible but requires a full ROS 2 install and spreads `unsafe` FFI throughout; dora-rs goes pure Rust but drops wire compatibility entirely—and how **hiroz** takes a third path: pure Rust, no C dependencies, and wire-compatible with standard ROS 2 nodes out of the box. We then go inside hiroz's async runtime design, message generation pipeline, and multi-language binding strategies.
