---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<i class="fa-solid fa-user fa-bounce"></i> About Me
======
I'm currently a second year Master student in [School of Computer Science Technology](https://cs.fudan.edu.cn/main.htm), 
[Fudan University](https://www.fudan.edu.cn/), advised by Prof. [Jin Zhao](https://jinzhaofd.github.io/). I received my
B.Eng. from [Northeastern University](http://www.neu.edu.cn/) in 2019.

<i class="fa-solid fa-magnifying-glass fa-beat"></i> Research Interests
======
My research interest lies in computer networking and systems. Below are the main projects I have participated.
- Deep Packet Inspection(DPI) Accelerating. As an intern in Intel from Feb. 2022 to now, I'm a developer of [Hyperscan](https://github.com/intel/hyperscan), 
the fastest regular expression matching engine running on modern CPUs. I would take advantage of SIMD to accelerate the
multi-literal matching process, a critical step in Hyperscan's workflow. Hyperscan has been integrated into famous DPI 
applications such as Snort and Suricata. It dramatically increases their real-time packet processing capability. Our 
works have been published in [NSDI](https://dl.acm.org/doi/10.5555/3323234.3323286), [ICPP](https://dl.acm.org/doi/abs/10.1145/3472456.3473512), 
and [INFOCOM](https://github.com/haoxufd/haoxufd.github.io/tree/master/files/Harry.pdf)(Authored by me | To be published).
- SDN. I used to work in [Sangfor](https://www.sangfor.com/) for a year, where I developed the control plane of an SDN system.
- P4 Gateway Testbed. I worked in [Bytedance](https://www.bytedance.com/en/) as an intern from May 2021 to Aug. 2021, 
supervised by [Chuanxiong Guo](https://sysnetome.com/index.html). I built a testbed to test the functionality and 
performance of P4 gateway. The testbed utilizes a single server to simulate multiple network topologies(e.g. gateway 
connecting with switches, gateway connecting with servers, gateway connecting with both switches and servers).

<i class="fa-solid fa-book fa-bounce"></i> Publications
======
- <strong><u>Hao Xu</u></strong>, Harry Chang, Wenjun Zhu, Yang Hong, Geoff Langdale, Kun Qiu, Jin Zhao, “[Harry: A Scalable SIMD‑based 
Multi‑literal Pattern Matching Engine for Deep Packet Inspection](https://github.com/haoxufd/haoxufd.github.io/tree/master/files/Harry.pdf)”. 
In IEEE International Conference on Computer Communications <strong>(INFOCOM’23)</strong>. Acceptance Rate: 252/1312=19%. <p style="color: red;">[Deployed in Hyperscan]</p>
