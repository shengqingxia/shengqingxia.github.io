---
layout: single
title: "Projects"
permalink: Project
author_profile: true
redirect_from: 
  - /project/
  - /project.html
---

My research aims to build an efficient and effective mobile system combined with computer vision, edge computing and machine learning.

Currently, I am particular interested in the following problems:
* Autonomous drone delivery to the door
* Making mobile vision more efficient with more video compression
* Enhancing DNN deployment efficiency in diverse use scenarios

  
Autonomous drone delivery to the door
----
We present our attempt to tackle the last-hundred-feet problem for autonomous drone delivery. We take a semantic segmentation-based approach to progressively landing towards a convenient and safe drop-off point at all times. We leverage a single-family house structure to streamline and enhance semantic segmentation in the drop-to-door problem context. 
#### SSS: Towards Autonomous Drone Delivery to Your Door Over House-Aware Semantics
We were honored to receive the Best Demo Award at ACM HotMobile’24.
Check our interactive [demo](https://ddd.cs.purdue.edu) and real-world experiment video on [Youtube](https://www.youtube.com/watch?v=090d-8ZvHyw&list=PLLzN69of2f9bD5ZfPYhDpkAv-Pz2zI7Ac&index=1).


Making Mobile Vision More Efficient with More Video Compression
----
Given the fast development in computer vision, we orthogonally enforces more efficient compression for the specific vision inference tasks. Our approach  adapts to input contexts and significantly reduces the volume of video data without sacrificing visual inference accuracy.
<!--Compress Video without Compromising Analytical Accuracy-->


#### VPPlus: Exploring the Potentials of Video Processing for Live Video Analytics at the Edge

<div style="display: flex">
    <video width="320" height="240" controls style="float: left; margin-right: 10px;">
        <source src="../images/vpplus.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <p style="margin-top: 40px;">VPPlus aims to compress video content live streamed from the device to the edge without scarifying accuracy and timeliness of its video analytics. It enlarges the configuration space that can be optimized during on-device processing to achieve greater compression and generates proper feedback automatically to guide the joint tuning over more than 8 parameters (e.g. brightness, saturation, etc.).</p>
</div>


Enhancing DNN Deployment Efficiency in Diverse Use Scenarios
----
For efficient deployment, a DNN is specialized by training to fit the target use scenario (depending on computing power and visual data input). To handle this costly training and meet diverse deployment needs, we tailor the DNN to enhance performance for each scenario using Once-For-All DNN paradigm. This involves training one super network and searching for different sub-networks (subnets) to fit the specific use case.
<!--Customize DNN Deployment in Diverse Use Scenario-->

#### OPA:One-Predict-All For Efficient Deployment
<div style="display: flex">
    <img src="../images/ofa_flow.png" alt="Your Image" width="300" style="float: left; margin-right: 10px;">
    <p>Instead of training a specialized DNN for each deployment scenario, we have developed a
novel approach of using one shallow subnet to test the water. The effectiveness of using a
shallow subnet to accelerate the search of a deep subnet has been validated effective in image
classification, one showcase application.</p>
</div>

