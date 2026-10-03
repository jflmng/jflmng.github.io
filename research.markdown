---
layout: single
title: Research
permalink: /research/
toc: true
toc_label: "On this page"
---

Our group works where control theory meets machine learning. We design controllers
that make good decisions in real time, respect safety constraints, and cope with
uncertainty, and we test them on vehicles, robots and energy systems.

<!-- TODO: add one image or short video per theme (e.g. motorcycle rig, vehicle trials, plots). -->

## Safe predictive control

Many important problems in industry involve optimising performance while never
violating safety-critical constraints. Model predictive control (MPC) does this by
predicting and optimising a system's future behaviour. To handle uncertainty without
prohibitive computation, we develop methods that reason about **sets** of predicted
states, giving robust controllers with formal guarantees.

**Applications:**
*   **Driver assistance:** cutting vehicle energy use by anticipating traffic.
*   **Connected vehicles:** control of heterogeneous vehicle platoons.
*   **Motorcycles:** gyroscopic stabilisation for safer riding.
*   **Offshore wind:** control of large floating wind turbines.

## Learning-enabled control

Reinforcement learning can learn control policies automatically but offers no safety
guarantees. MPC offers guarantees but takes expert effort to design. We bridge the
gap by making MPC **differentiable**, so safe controllers can be trained inside
reinforcement-learning frameworks.

### Project: Learning of Safety-Critical MPC for Autonomous Systems
**EPSRC New Investigator Award** · [Project details](https://gtr.ukri.org/projects?ref=EP%2FX015459%2F1)

This project develops AI methods that design MPC automatically, for safe motion
control of autonomous vehicles and stability-assisted motorcycles, in partnership
with Dynamotion and the University of Padova. The aim is to cut controller
development time and cost while improving reliability.

## AI for health and behaviour

The same ideas of feedback, prediction and personalisation apply to people. We build
machine-learning systems that decide what support to offer, and when, to help people
manage long-term conditions.

### Project: Holly Health Prevent App
**Innovate UK** · with [Holly Health](https://hollyhealth.io/) and Modality Partnership

A Just-in-Time Adaptive Intervention (JITAI) system that delivers personalised
coaching to people living with multiple chronic conditions, around 30% of UK adults,
aiming to improve health outcomes and reduce pressure on the NHS.

## Work with us

We welcome collaboration with industry and other research groups.
[Get in touch](/contact/){: .btn .btn--primary} [Join the group](/join/){: .btn .btn--inverse}
