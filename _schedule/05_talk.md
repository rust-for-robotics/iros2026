---
sequence_id: 5
speaker: Nihal Pasham
time: 10:30 – 11:00
title: "cuda-oxide - Write CUDA kernels in pure Rust"
# webpage: https://jane.doe
# affil: Buzz University
# affil_link: https://buzz.edu
img: nihal.png
# affil2: BuzzFizz Corp
# affil2_link: https://buzzfizz.corp
---

cuda-oxide is a Rust-to-CUDA compiler stack for writing GPU kernels in pure Rust. It lets host and device code live in one Rust source file, compiles #[kernel] functions to PTX through a custom rustc backend, and keeps normal Rust features like generics, closures, type checking, and monomorphization in the workflow. The main point is simple: developers should not have to choose between CUDA’s latest hardware features and Rust’s safer, more composable programming model. cuda-oxide shows that Rust kernels can target modern NVIDIA GPUs, including advanced features like TMA, clusters, atomics, async execution, and Blackwell tensor cores, while retaining Rust’s core benefits: strong type checking, generics, closures, monomorphization, and safer host/device API boundaries.
