---
layout: post
title: ARM CPU with value prediction
excerpt: "I worked with three team members to design and implement an ARM-based CPU from the ground up and develop a
          successful form of value prediction. We first designed an in-order pipeline, but eventually moved to an
          HPS-style out-of-order microarchitecture. After modeling the architecture in SystemC, we implemented the
          design in structural Verilog with unit- and top-level SystemVerilog testbenches. To aid us with verification
          and demoes, we also built a wide array of tooling."
showdate: false
readmore: false
image:
  feature: projects/arm-cpu/feature.jpg
  credit: Andrew Carr
  creditlink: https://www.flickr.com/photos/utece/17298506706/in/album-72157651867758070/
---
ARM with Datapath eXtensions (ADX), is a CPU design project I undertook with three others under the supervision of Dr.
Yale Patt for my senior capstone at UT. Our initial goal was open ended: pick an ISA, design a CPU, and then make it
better. What we ended up developing was an ARMv4 out-of-order CPU with a successful form of value prediction and a less
successful configurable coprocessor.

### Proteus: Starting simple

### Hydra: Going out-of-order

### Makara: Adding the eXtensions

### Kraken: From SystemC to Verilog

### Ares: The special sauce
