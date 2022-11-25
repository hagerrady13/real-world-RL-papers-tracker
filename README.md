# [WIP] RL For Real World Applications - Papers Tracker

Every time i wanna learn about a new topic, I wish it was possible to find a place with all papers/previous work done in this area. As I am learning about RL, I was curious to know further about applications of RL in the real world, other than the games or simulated environments. Here is a place where i am hoping to make an active tracker of where RL can be applied in the real world.

[2020]
Deep Reinforcement learning for Chip design  
[Paper](https://arxiv.org/pdf/2004.10746.pdf)  
[Blog post](https://ai.googleblog.com/2020/04/chip-design-with-deep-reinforcement.html?m=1)  
Main idea: As one of the most complex and time consuming processes in chip design, they shape the chip placement process as a Reinforcement Learning (RL) problem and train an agent to place the nodes of a chip netlist onto a chip canvas. To enable the RL policy to generalize to unseen blocks, they ground representation learning in the supervised task of predicting placement quality. While existing baselines require human experts in the loop and take several weeks, the agent learns to minimize PPA (power, performance, and area) and can generate placements that are superhuman or comparable on modern accelerator netlists in 6 hours!


http://www.openreview.net/pdf?id=Syx7A3NFvH

[11 Nov 2022]
Controlling Commercial Cooling Systems Using Reinforcement Learning
[Paper](https://arxiv.org/pdf/2211.07357.pdf)
This paper is a technical overview of DeepMind and Google’s recent work on reinforcement learning for
controlling commercial cooling systems. Building on expertise that began with cooling Google’s data
centers more efficiently, we recently conducted live experiments on two real-world facilities in partnership with Trane Technologies, a building management system provider. These live experiments had a variety of challenges in areas such as evaluation, learning from offline data, and constraint satisfaction.
Our paper describes these challenges in the hope that awareness of them will benefit future applied RL
work. We also describe the way we adapted our RL system to deal with these challenges, resulting in
energy savings of approximately 9% and 13% respectively at the two live experiment sites.
