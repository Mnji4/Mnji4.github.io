---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Research Interests

Reinforcement Learning · Sequential Decision Making · Embodied AI / Vision-Language-Action Models · Reasoning in Foundation Models

## Education

**Sun Yat-Sen University** | Guangzhou, China  
*M.Eng. in Computer Technology* | Sep. 2020 – Jul. 2022  
School of Software Engineering

**Sun Yat-Sen University** | Guangzhou, China  
*B.Eng. in Traffic Engineering* | Sep. 2015 – Jul. 2019  
School of Intelligent Systems Engineering

## Manuscript

**Trajectory-Based Credit Assignment for Multi-Intersection Traffic Signal Control**  
*Zenian Liang*  
Under review at NeurIPS 2026

- Formulated Trajectory-based Credit Assignment (TCA) for cooperative multi-agent reinforcement learning in entity-flow scenarios, addressing the noise-myopia trade-off by aggregating delayed feedback along entity trajectories.
- Demonstrated robust, plug-and-play performance gains across complex traffic-load scales without requiring policy or network architectural modifications.

## Research & Engineering Experience

**Parametrix.ai** | Shenzhen, China  
*Machine Learning Engineer* | Jul. 2022 – Mar. 2026

### MOBA Game AI

- Formulated a goal-conditioned hierarchical reinforcement learning framework that factorized the policy space into high-level macro-strategy and low-level micro-control for long-horizon decision making under partial observability.
- Designed multi-stage reward shaping, curriculum learning, and self-play schemes to guide policy evolution from simple heuristics to complex cooperative behaviors.
- Empirically validated convergence and sample efficiency, achieving competitive performance against high-level human baselines.

### Sim-to-Real Drone Navigation

- Constructed a neural world simulator by integrating Instant-NGP reconstructions into physics-based engines to reduce the sim-to-real visual domain gap.
- Trained a closed-loop sensorimotor control policy using vision-based reinforcement learning and behavior cloning from expert demonstrations.
- Achieved zero-shot sim-to-real transfer in physical quadrotor navigation experiments.

### High-Fidelity Speech Generation

- Developed a hybrid generative pipeline combining an autoregressive Transformer for semantic sequence modeling and a Flow Matching network for acoustic synthesis.
- Designed a scalable cross-modal data-processing pipeline for a 200k-hour multi-speaker speech corpus.
- Introduced a reinforcement-learning-based Generative Alignment framework that optimized sequence-level audio quality against a learned evaluator model.
- Demonstrated improvements in subjective MOS and objective metrics for speech naturalness and acoustic consistency over open-source baselines.

## Selected Projects

**KDD Cup 2021 City Brain Challenge** | Jul. 2021 – Sep. 2021

- Controlled 859 traffic signals to optimize cumulative delay for more than 120k vehicles within one hour.
- Explored policies with distinct objectives independently and integrated them via weighted policy distillation.
- Achieved a **Top 4%** ranking on the final leaderboard.

**DAI 2020 SMARTS Autonomous Driving Challenge — Multi-Agent Track** | Sep. 2020 – Oct. 2020

- Coordinated multiple autonomous vehicles in scenarios including T-junctions and intersections.
- Implemented multi-agent reinforcement learning algorithms under the CTDE paradigm.
- Ranked **6th overall** and achieved **1st place** in specific map scenarios.

## Patents

- **Method for Game Territory Construction, Computer and Storage** | Sep. 2025  
  CN120695451A
- **AI Model Learning Medium, Server and Computer-Readable Storage Medium** | Jan. 2024  
  CN117391179A
- **Traffic Light Control Method and System Considering Travel Time and Fairness** | Apr. 2022  
  CN114299732A

## Technical Skills

Kubernetes · Docker · Ray · MS-Swift · Redis · Git
