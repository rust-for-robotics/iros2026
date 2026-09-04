---
sequence_id: 2
speaker: Georges Goetz
time: 09:15 – 09:45
title: "Deploying a Behavior Policy on a 115,000 Pound Robot: What Rust Governs, and What It Doesn't"
# webpage: https://jane.doe
# affil: Buzz University
# affil_link: https://buzz.edu
img: bedrock.png
# affil2: BuzzFizz Corp
# affil2_link: https://buzzfizz.corp
---

At Bedrock, we deploy a learned behavior policy to operate a heavy-duty excavator on our job sites. The policy proposes motion from multimodal observations, but it does not own machine authority. Around it is an onboard system we wrote in Rust from scratch, from sensor drivers through ML inference and control.

In this talk, we will show where our investment in Rust paid off: in what the model sees (the sensor drivers), what the model may do (a fault system whose response ladder ensures safe fallbacks when the unexpected happens), and how the model is developed (a middleware layer that runs the same components live, in replay over field logs, in simulation, and generates the data the policy trains on). We will also cover three boundaries where Rust got harder: model authoring against Python-authored contracts, model execution against the GPU runtime, and model support, where Rust has optimizers but no Ceres. Overall, we would choose Rust again, and those boundaries are where we would want the ecosystem to grow.