---
layout: post
title: "Processors: Random terminologies to benchmark on new Ryzen"
date: 2026-05-10
---
Greetings!

For CPU learning curve, I'll use Chips and Cheese (https://chipsandcheese.com/) website.

I've read it during the weekend, and understood what they talk about maybe 10%. The methodology is to read, copy sentences which seem important but not
clear and research on them further.

Current list built from this weekend, which I will post a separate post for each:

- Operates within a 600W thermal envelope, and supports BF16, FP8, MXFP6 and MXFP4 workloads,
- Zen 5 processors make use of an improved branch prediction system with <span style="color: green">dual decode pipes</span>.
- Number of <span style="color: green">dispatch</span> and <span style="color: green">execution engines</span>.
- But I won’t comment on <span style="color: green">GPU cache miss bandwidth</span>, which will obviously be limited by PCIe bandwidth.
- Switching the GPU to the <<span style="color: green">chipset lanes</span> dropped cache hit bandwidth to just above 25 GB/s, and that figure remains similar regardless of whether one or two PROM21 chips sat between the CPU and GPU.
- <span style="color: green">GPU cache hit rate bandwidth</span>
- instructions per cycle
- Nvidia’s L1 cache offers an impressive combination of low latency and high capacity. With dependent array accesses, it can return data nearly as fast as AMD’s 16 KB <span style="color: green">scalar cache</span> while offering more capacity than AMD’s first level scalar and vector caches combined.
- <span style="color: green">Pointer dereferences</span> indicate that AMD takes a lot of overhead from array addressing calculations
- Because it’s distributed in binary form, Geekbench 6 can easily target <span style="color:green">ISA-specific features</span>....With Intel’s Granite Rapids as an ISA target.
- AVX(2) has a huge presence across Geekbench 6 workloads, to the point that it’s easier to name workloads that aren’t <span style="color:green">heavily vectorized</span> than ones that are.

* Ivan

The day is clear for flying.
