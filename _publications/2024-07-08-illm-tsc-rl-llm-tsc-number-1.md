---
title: "iLLM-TSC: Integration of Reinforcement Learning and Large Language Model for Traffic Signal Control Policy Improvement"
collection: publications
category: preprint
permalink: /publication/2024-07-08-illm-tsc-rl-llm-tsc
authors: "Aoyu Pang, Maonan Wang, Man-On Pun, Chung Shue Chen, Xi Xiong"
date: 2024-07-08
venue: "arXiv preprint arXiv:2407.06025"
paperurl: "https://arxiv.org/abs/2407.06025"
slidesurl: ""
bibtexurl: ""
abstract: >
  Urban congestion remains a critical challenge, with traffic signal control (TSC) emerging as a potent solution. 
  TSC is often modeled as a Markov Decision Process problem and then solved using reinforcement learning (RL), which has proven effective. 
  However, existing RL-based TSC systems often overlook imperfect observations caused by degraded communication, such as packet loss, delays, and noise, 
  as well as rare real-life events not included in the reward function, such as unconsidered emergency vehicles. 
  To address these limitations, we introduce a novel integration framework that combines a large language model (LLM) with RL. 
  This framework is designed to manage overlooked elements in the reward function and gaps in state information, thereby enhancing the policies of RL agents. 
  In our approach, RL initially makes decisions based on observed data. Subsequently, LLMs evaluate these decisions to verify their reasonableness. 
  If a decision is found to be unreasonable, it is adjusted accordingly. 
  Additionally, this integration approach can be seamlessly integrated with existing RL-based TSC systems without necessitating modifications. 
  Extensive testing confirms that our approach reduces the average waiting time in degraded communication conditions compared to traditional RL methods, 
  underscoring its potential to advance practical RL applications in intelligent transportation systems. 
  The related code can be found at [GitHub](https://github.com/Traffic-Alpha/iLLM-TSC).
citation: "Pang, A., Wang, M., Pun, M.-O., Chen, C.S., Xiong, X. (2024). iLLM-TSC: Integration of Reinforcement Learning and Large Language Model for Traffic Signal Control Policy Improvement. <i>arXiv preprint arXiv:2407.06025</i>."
---