---
layout: archive
title: "Repositories"
permalink: /repositories/
author_profile: true
---

{% include base_path %}
**Modular-GenAI**

A modular and clean research framework for Generative AI, based on popular open-source repositories like Transformers, TRL, Diffusions, and CleanRL.

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/AbdullahVanlioglu/Modular-GenAI" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">Code</a>
</div>

<br>

**Modular-Baselines**

Modular-Baselines is a library designed for Reinforcement Learning (RL) research. Our goal is to provide a flexible, easy-to-use set of components that can be combined in various ways to enable experimentation with different RL algorithms.

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/AbdullahVanlioglu/Modular-Baselines" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">Code</a>
</div>

<br>

**AgentFlow**

AgentFlow is a modular, multi-agent, framework-agnostic system designed for intelligent document processing and analysis. It is being extended into a generalist AI platform capable of solving complex, long-horizon planning tasks. This evolution will enable AgentFlow to orchestrate specialized agents for reasoning, decision-making, and adaptive execution across diverse domains.


{% for post in site.repositories reversed %}

    {% include archive-single.html %}

{% endfor %}
