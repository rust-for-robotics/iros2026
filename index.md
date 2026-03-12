---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: "Why Rust for Robotics: </br>A Perspective From Industry"
subtitle: "IROS 2026 Workshop | September 27, 2026 | 8:00 AM - 5:30 PM"
layout: home
---

<div class="img-wrapper">
<div class="img-container">
    <img src="{{ site.baseurl }}/assets/img/iros.webp" height="100" style="object-fit: contain;"/>
</div>
<div class="img-container">
    <img class="middle-img" src="{{ site.baseurl }}/assets/img/rust.png" height="100" style="object-fit: contain;"/>
</div>
</div>

<p style="font-style: italic; text-align: center; font-size: 0.8em;">
  Rust for Robotics is not officially affiliated with the Rust Foundation.
</p>

This full-day workshop investigates why so many in industry are choosing Rust as their stack of choice and what pitfalls or success stories they have encountered in doing so. In addition, we seek to discuss what barriers are preventing Rust adoption in academia and discuss how many of the successes of industry adoption can be adapted to academic settings.

More specifically, we will discuss
- Rust's value proposition for robotics, 
- Adoption challenges with legacy systems, 
- Role in research and education, 
- The robotics Rust ecosystem, and 
- Potential for future growth. 
 
Participants, including those unfamiliar with Rust, will gain a better understanding of how Rust can aid in developing robust robotics systems through presentations, interactive code demonstrations, panels, and poster sessions. Targeting software engineers, researchers, educators, and students, this workshop is focused on helping progress the adoption and development of robotics software written in Rust, thereby helping catalyze a shift towards safer and more reliable autonomous systems.

This workshop will include 8 invited talks, a panel discussion, a live demonstration, and a poster session.
<br>
<br>

### Why Rust for Robotics?

Rust has a number of features that make it particularly well-suited for robotics applications, including:

<div class="code-grid">
  <div>
    <img src="{{ site.baseurl }}/assets/img/code/memory.png" style="object-fit: contain;"/>
  </div>

  <div>
    <h5> Memory Safety</h5>
    Rust's ownership model ensures memory safety without a garbage collector, reducing the risk of memory leaks and segmentation faults, which are critical in real-time robotics applications.
  </div>

  <div>
    <img src="{{ site.baseurl }}/assets/img/code/concurrency.png" style="object-fit: contain;"/>
  </div>

  <div>
    <h5>Concurrency</h5>
    "Fearless concurrency" is a core trait of Rust and makes it remarkably easy to develop concurrent applications that handle intensive I/O operations efficiently.
  </div>

  <div>
    <img src="{{ site.baseurl }}/assets/img/code/multithreading.png" style="object-fit: contain;"/>
  </div>

  <div>
    <h5>Multithreading</h5>
    Rust design makes it super easy to develop multithreaded applications. It's going to be a breath of fresh air compared to C/C++ MPI, or fighting against Python Global Interpreter Lock(GIL)
  </div>

  <div>
    <img src="{{ site.baseurl }}/assets/img/code/multi-arch.png" style="object-fit: contain;"/>
  </div>

  <div>
    <h5>Multi-Architecture Support</h5>
    Building an application compiled for a specific architecture has never been so easy!
  </div>

  <div>
    <img src="{{ site.baseurl }}/assets/img/code/tooling.png" height="200px" style="object-fit: contain;"/>
  </div>

  <div>
    <h5>Tooling</h5>
    Rust's tooling ecosystem is robust and user-friendly, making it easy to manage dependencies, build projects, and integrate with other systems. Tools like Cargo simplify package management and project setup, while Clippy and Rustfmt help maintain code quality and consistency.
  </div>
</div>