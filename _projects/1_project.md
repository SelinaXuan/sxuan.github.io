---
layout: page
title: GIDEA: Generative AI-powered platform for HCI research
img: assets/img/system_overview.png
importance: 1
category: work
related_publications: true
---

GIDEA is an AI-driven simulation platform that streamlines human-computer interaction (HCI) experiments by automating user interactions and experiment management. Traditional HCI studies require extensive manual effort, but GIDEA accelerates this process using <strong>large language models (LLMs)</strong> to generate realistic interaction scenarios dynamically.

<h2>Key Features</h2>

<ul>
  <li><strong>LLM-Driven Virtual Participants:</strong> Simulated avatars with unique personalities engage in real-time interactions based on structured research prompts.</li>
  <li><strong>Real-Time Experiment Control with Unity:</strong> Researchers define objectives, control environments, and monitor experiments dynamically.</li>
  <li><strong>Virtual Reality (VR) Integration:</strong> GIDEA supports immersive experimentation with VR setups, enabling embodied interaction studies.</li>
  <li><strong>Case Study Validation:</strong> The platform has been tested against real-world HCI studies, demonstrating statistically consistent results.</li>
</ul>

<h2>Showcase</h2>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/unity_panel.png" title="Unity-based Simulation" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/avatar.jpg" title="AI-Generated Avatar Interaction" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/vr_demo.jpg" title="VR Experiment Setup" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  Left: The Unity-based simulator running a case study. <br>
  Middle: AI-generated avatars engaging in interactions. <br>
  Right: A VR user participating in an experiment.
</div>

<p>
  Say you wanted to describe how your system works before showing its workflow. Here is a quick overview:
</p>

<h2>Experiment Workflow</h2>

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/workflow_diagram.jpg" title="GIDEA Workflow Overview" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/agent_roles.jpg" title="Multi-Agent Roles" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  You can also have 2/3 + 1/3 styled images. Left: overall system pipeline. Right: agent roles that evolve during training.
</div>

<ol>
  <li><strong>Define Research Questions:</strong> Specify experiment goals and design.</li>
  <li><strong>Simulate Interactions:</strong> LLM-driven avatars participate based on scenario prompts.</li>
  <li><strong>Monitor & Adjust:</strong> Researchers observe and intervene in real time.</li>
  <li><strong>Analyze & Compare:</strong> Results are compared to human-study baselines for validation.</li>
</ol>

<p>
  With <strong>GIDEA</strong>, researchers can conduct scalable, efficient, and adaptive HCI studies, accelerating intelligent system evaluation. You can also cite related works using {% raw %}{% cite somekey2024 %}{% endraw %}.
</p>
