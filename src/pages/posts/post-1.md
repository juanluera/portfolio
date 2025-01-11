---
layout: ../../layouts/MarkdownPostLayout.astro
title: Using FPGA's for autonomous vehicles
pubDate: 2025-01-11
description: 'This is the first post of my new Astro blog.'
author: Juan Luera
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'

video: 
    url: https://www.youtube.com/watch?v=0TS0FlSu1_4
    alt: Video of FPGA project
tags: ["FPGA","Verilog"]
---


The integration of LIDAR sensors and Inertial
Measurement Units (IMUs) in robotic navigation can provide
enhanced data sensing processing and energy efficiency. Our
project aims to explore the robustness and responsiveness of
FPGA in handling the demands of these sensors. Leveraging
the parallel processing capabilities of FPGAs, our system is
designed to simultaneously interpret continuous LIDAR data
and calculate the car’s real-time orientation and position using
IMUs. This approach ensures an efficient and real-time reaction
to surrounding obstacles. The minimally viable project consists
of implementing the UART protocols to interface with an IMU
and a LIDAR camera and use this data to navigate an RC car.
The FPGA will process information from the IMU and LIDAR
cameras and update the trajectory of our RC car if an object is
detected. The goal is to recognize obstacles in lanes and maneuver
around them. Our stretch goal is to implement an algorithm for
room mapping using obstacle avoidance and position control. Our
aim is to demonstrate how FPGA’s timing and parallel processing
can optimize real-time navigational task

## What I've accomplished

1. **Installing Astro**: First, I created a new Astro project and set up my online accounts.

2. **Making Pages**: I then learned how to make pages by creating new `.astro` files and placing them in the `src/pages/` folder.

3. **Making Blog Posts**: This is my first blog post! I now have Astro pages and Markdown posts!

## What's next

I will finish the Astro tutorial, and then keep adding more posts. Watch this space for more to come.
