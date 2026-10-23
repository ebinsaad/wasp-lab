---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
description: Research vision, methodology, and research themes of WASP Lab.
---

<link rel="stylesheet" href="{{ '/assets/css/wasp-custom.css' | relative_url }}">

<section class="wasp-research-hero">
  <div class="wasp-research-hero-content">
    <span class="wasp-eyebrow">OUR RESEARCH VISION</span>
    <h1>Understanding Failures.<br><span>Engineering Resilience.</span></h1>
    <p>
      Advancing <strong>Reliable, Dependable, and Resilient (RDR) Computing</strong>
      through the systematic investigation of failures in emerging
      computing technologies.
    </p>
  </div>
</section>

## Our Research Vision

Modern computing systems are increasingly intelligent, autonomous, interconnected, and deeply integrated into critical operations. While these technologies introduce new capabilities, they also create sources of uncertainty and failure that cannot always be anticipated through conventional testing, verification, and security assessment.

At WASP Lab, we investigate **why computing systems fail, how failures emerge and propagate, and how systems can be engineered to remain secure, dependable, and resilient under uncertainty**.

Our research combines fundamental investigation, experimental systems engineering, and empirical validation. Rather than focusing exclusively on individual technologies or isolated vulnerabilities, we seek to understand failure mechanisms and develop generalizable methods for engineering resilience.

---

## The Changing Nature of Computing Failures

### From Technical Faults to Emergent Sociotechnical Failures

The increasing adoption of AI, autonomous agents, and intelligent decision-making is expanding the complexity of computing failures. Traditional technical faults remain important, but new failure mechanisms can arise from uncertain reasoning, autonomous interactions, and the integration of intelligent technologies into human and organizational processes.

<div class="wasp-failure-evolution">

  <div class="wasp-failure-stage">
    <span class="wasp-stage-number">01</span>
    <h3>Technical &amp; System Failures</h3>
    <p>Software defects, hardware faults, network disruptions, configuration errors, and security vulnerabilities.</p>
  </div>

  <div class="wasp-evolution-arrow" aria-hidden="true">&#8594;</div>

  <div class="wasp-failure-stage">
    <span class="wasp-stage-number">02</span>
    <h3>Intelligent &amp; Autonomous System Failures</h3>
    <p>Model limitations, unreliable reasoning, incomplete context, agent coordination, and environmental uncertainty.</p>
  </div>

  <div class="wasp-evolution-arrow" aria-hidden="true">&#8594;</div>

  <div class="wasp-failure-stage wasp-future-stage">
    <span class="wasp-stage-number">03 &middot; EMERGING</span>
    <h3>Sociotechnical Failures</h3>
    <p>Interactions among intelligent technologies, human operators, organizational processes, and operational constraints.</p>
  </div>

</div>

This progression represents an **expansion of failure complexity**, not a replacement of traditional technical failure models. Technical, intelligent, and sociotechnical failure mechanisms can coexist and interact within the same system.

---

## Our Research Methodology

Our research follows an iterative, evidence-driven approach built around four complementary activities.

<div class="wasp-methodology-grid">

  <div class="wasp-method-card">
    <span class="wasp-method-number">01</span>
    <h3>Characterize</h3>
    <p>Identify failure modes, contributing conditions, causal mechanisms, and pathways through which failures emerge and propagate.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">02</span>
    <h3>Quantify</h3>
    <p>Develop metrics, benchmarks, datasets, and experiments to measure failure likelihood, severity, impact, and propagation.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">03</span>
    <h3>Mitigate</h3>
    <p>Design and evaluate mechanisms to prevent, detect, contain, tolerate, and recover from failures.</p>
  </div>

  <div class="wasp-method-card">
    <span class="wasp-method-number">04</span>
    <h3>Validate</h3>
    <p>Evaluate proposed methods under representative operational conditions, including uncertainty, adversarial behavior, and environmental disturbances.</p>
  </div>

</div>

<p class="wasp-methodology-note">
  <strong>Iterative research process:</strong> Experimental evidence informs
  the continuous refinement of failure models, mitigation mechanisms,
  and validation strategies.
</p>

Our methodological toolkit includes empirical software and security analysis, artificial intelligence, knowledge engineering, experimental testbeds, adversarial testing, and chaos engineering.

---

## Our Research Themes

Our research is currently organized around three complementary themes.

<div class="row row-cols-1 row-cols-md-3 g-4 mt-2 wasp-research">

  <div class="col">
    <a href="{{ '/research/intelligent-cybersecurity/' | relative_url }}" class="wasp-research-link">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title">Intelligent Cybersecurity &amp; Security Operations</h5>
          <p class="card-text">Advancing cybersecurity through intelligent threat detection, security analytics, cyber threat intelligence, and AI-driven automation of security operations.</p>
          <span class="wasp-card-more">Explore research &rarr;</span>
        </div>
      </div>
    </a>
  </div>

  <div class="col">
    <a href="{{ '/research/trustworthy-ai/' | relative_url }}" class="wasp-research-link">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title">Trustworthy &amp; Secure AI</h5>
          <p class="card-text">Investigating vulnerabilities, adversarial threats, and reliability challenges in machine learning, large language models, and autonomous AI agents.</p>
          <span class="wasp-card-more">Explore research &rarr;</span>
        </div>
      </div>
    </a>
  </div>

  <div class="col">
    <a href="{{ '/research/resilience-engineering/' | relative_url }}" class="wasp-research-link">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title">Resilience Engineering &amp; Autonomous Systems</h5>
          <p class="card-text">Understanding failures and developing testing, mitigation, and recovery approaches for intelligent systems and cyber-physical platforms.</p>
          <span class="wasp-card-more">Explore research &rarr;</span>
        </div>
      </div>
    </a>
  </div>

</div>

---

## Future Research Directions

### Toward Sociotechnical Resilience

As WASP Lab expands its interdisciplinary research activities, we aim to extend RDR Computing beyond the technical properties of individual systems toward the resilience of technology-enabled operations.

Our emerging research agenda includes:

- Human–AI collaboration and oversight in high-stakes operational environments.
- Reliability and accountability of autonomous decision-making within organizations.
- Interactions between technical failures, human decisions, and organizational processes.
- Operational resilience of AI-enabled cybersecurity and information systems.
- Sociotechnical methods for evaluating the trustworthiness and resilience of intelligent systems.

These directions build on our technical research foundations and represent an expanding interdisciplinary research agenda.

---

## Research Projects and Outcomes

Our work combines fundamental research with experimental prototypes, testbeds, empirical studies, datasets, and collaborations with academic and industry partners.

Explore our [research projects]({{ '/projects/' | relative_url }}) and [publications]({{ '/publications/' | relative_url }}) to learn more.
