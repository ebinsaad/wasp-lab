---
layout: page
title: Resilience Engineering & Autonomous Systems
permalink: /research/resilience-engineering/
nav: false
description: WASP Lab research on resilience engineering, chaos engineering, autonomous systems, and cyber-physical systems.
---

<link rel="stylesheet" href="{{ '/assets/css/wasp-custom.css' | relative_url }}">

[Research Overview]({{ '/research/' | relative_url }}) &rarr; Resilience Engineering & Autonomous Systems

<section class="wasp-theme-hero">
  <span class="wasp-eyebrow">RESEARCH THEME 03</span>
  <h1>Resilience Engineering<br><span>&amp; Autonomous Systems</span></h1>
  <p>
    Understanding failures and engineering resilience in intelligent,
    autonomous, and cyber-physical systems through experimental
    testing, controlled failure injection, and systematic
    resilience assessment.
  </p>
</section>

## Research Overview

Autonomous and cyber-physical systems increasingly integrate software, artificial intelligence, sensors, communication networks, and physical components to operate in complex and dynamic environments.

These systems introduce challenges that extend beyond traditional software reliability and security. Failures may arise from unexpected environmental conditions, sensor inaccuracies, communication disruptions, software defects, adversarial interference, or interactions among intelligent and physical components.

At WASP Lab, we investigate how these failures emerge, interact, and propagate, and how autonomous systems can be engineered to maintain safe, dependable, and resilient operation under uncertainty.

Our research emphasizes **experimental validation, failure-oriented testing, and the systematic engineering of resilience**.

---

## Established Research Foundations

Our research builds on three complementary areas.

### System Security & Resilience Assessment

We investigate the security, dependability, and resilience of computing systems under operational disturbances and adversarial conditions.

Our work includes experimental security assessment, evaluation of system vulnerabilities, and investigation of how disruptions affect system behavior and operational continuity.

A central objective is to move beyond evaluating systems exclusively under expected conditions toward understanding their behavior when assumptions, components, or operating conditions fail.

### Adaptive Security & Fault Mitigation

We investigate approaches that enable computing systems to respond to changing threats, operational disturbances, and unexpected conditions.

Our work explores adaptive security mechanisms, dynamic defense strategies, and techniques for mitigating the consequences of security incidents and system failures.

These foundations support the development of systems capable of maintaining essential functionality or recovering when normal operating conditions are disrupted.

### Experimental Evaluation of Intelligent Systems

We investigate experimental approaches to evaluating intelligent systems and their behavior under varying operational conditions.

Our work combines empirical analysis, system instrumentation, controlled experimentation, and performance assessment to identify limitations and characterize system behavior.

This foundation supports the development of reproducible methods for evaluating the reliability and resilience of increasingly autonomous platforms.

---

## Current Research: Chaos Engineering for Autonomous Systems

Chaos engineering provides a systematic approach to evaluating system resilience by introducing controlled disturbances and observing how systems respond.

Originally developed primarily for distributed computing environments, chaos engineering offers opportunities for investigating complex cyber-physical and autonomous systems whose behavior depends on interactions among software, hardware, sensors, communication networks, AI models, and physical environments.

At WASP Lab, we investigate how chaos engineering can be adapted to the distinctive characteristics of autonomous systems.

Our research focuses on three interconnected challenges.

<div class="wasp-failure-class-grid">

  <div class="wasp-failure-class-card">
    <span class="wasp-stage-number">01</span>
    <h3>Failure Characterization</h3>
    <p>Understanding how sensor faults, communication disruptions, software failures, AI limitations, and environmental disturbances affect autonomous system behavior.</p>
  </div>

  <div class="wasp-failure-class-card">
    <span class="wasp-stage-number">02</span>
    <h3>Controlled Failure Injection</h3>
    <p>Designing reproducible experiments that introduce controlled disturbances to test system assumptions, expose vulnerabilities, and investigate failure propagation.</p>
  </div>

  <div class="wasp-failure-class-card">
    <span class="wasp-stage-number">03</span>
    <h3>Resilience Assessment &amp; Recovery</h3>
    <p>Measuring the consequences of failures and evaluating system detection, containment, adaptation, degraded operation, and recovery capabilities.</p>
  </div>

</div>

### Experimental Platforms

Our research explores autonomous and cyber-physical platforms, including:

- **Unmanned aerial vehicles (UAVs):** Investigating security, operational anomalies, sensor integrity, communication disruptions, and resilience in drone systems.
- **Scaled-down autonomous vehicles:** Studying AI-assisted navigation, perception, object tracking, and control under changing environmental and operational conditions.
- **AI-enabled cyber-physical systems:** Examining interactions among machine learning models, software components, sensors, communication infrastructure, and physical processes.

These platforms provide opportunities to investigate failure mechanisms that may be difficult to capture through software-only testing.

### Beyond Simulation-Based Testing

Simulation is an essential tool for autonomous system development and validation. However, simulation models necessarily rely on assumptions about system behavior, environmental conditions, and component interactions.

As systems become more intelligent and operate in increasingly dynamic environments, some failures may arise from interactions that are difficult to anticipate or represent accurately in simulation.

Our research investigates how chaos engineering can **complement simulation, conventional testing, and formal verification** by introducing controlled operational uncertainty and experimentally challenging assumptions about system behavior.

The objective is not to replace existing testing approaches, but to expand the evidence available for evaluating system resilience.

---

## Emerging Research: Resilience of Physical AI

As artificial intelligence becomes more deeply integrated into physical systems, autonomous platforms increasingly rely on learned perception, reasoning, planning, and decision-making.

This introduces new research questions concerning the interaction between AI uncertainty and physical system behavior.

Our emerging research directions include:

- **AI-driven failure propagation:** Understanding how errors in perception, reasoning, or decision-making influence downstream physical actions.
- **Cross-layer resilience:** Investigating dependencies among AI models, software, communication networks, sensors, actuators, and physical environments.
- **Adaptive and graceful degradation:** Developing mechanisms that allow autonomous systems to maintain essential functionality when components or intelligent capabilities become unreliable.
- **Runtime monitoring and recovery:** Detecting abnormal behavior and supporting safe adaptation or recovery during operation.
- **Real-world resilience validation:** Evaluating whether resilience mechanisms remain effective under unexpected operational conditions.

Our long-term objective is to advance engineering methods for **reliable, dependable, and resilient AI-enabled physical systems**.

---

## Research Methodology

This research theme follows WASP Lab's broader RDR Computing methodology:

<div class="wasp-methodology-grid">

  <div class="wasp-method-card">
    <span class="wasp-method-number">01</span>
    <h3>Characterize</h3>
    <p>Identify failure modes, system dependencies, and mechanisms of failure propagation.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">02</span>
    <h3>Quantify</h3>
    <p>Measure failure impact, system degradation, recovery performance, and resilience.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">03</span>
    <h3>Mitigate</h3>
    <p>Develop fault detection, containment, adaptation, and recovery mechanisms.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">04</span>
    <h3>Validate</h3>
    <p>Experimentally evaluate system resilience under controlled disturbances and operational uncertainty.</p>
  </div>

</div>

---

## Research Contributions & Outcomes

Our research aims to produce:

- New knowledge about failure mechanisms and propagation in autonomous systems.
- Experimental methods for applying chaos engineering to cyber-physical systems.
- Reproducible failure injection scenarios and resilience benchmarks.
- Datasets and testbeds supporting security and resilience research.
- Techniques for detecting, mitigating, and recovering from operational failures.
- Engineering practices for dependable AI-enabled autonomous platforms.

---

## Projects & Publications

Explore our [research projects]({{ '/projects/' | relative_url }}) and [publications]({{ '/publications/' | relative_url }}) for related work.

[&larr; Back to Research Overview]({{ '/research/' | relative_url }})
