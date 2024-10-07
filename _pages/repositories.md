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
  <a href="https://github.com/AbdullahVanlioglu/Modular-GenAI" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">Modular-GenAI</a>
</div>

<br>

**Modular-Baselines**

Modular-Baselines is a library designed for Reinforcement Learning (RL) research. Our goal is to provide a flexible, easy-to-use set of components that can be combined in various ways to enable experimentation with different RL algorithms.

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/AbdullahVanlioglu/Modular-Baselines" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">Modular-Baselines</a>
</div>

<br>

**You can find all of my repositories on my Github**

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/AbdullahVanlioglu/" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">GitHub</a>
</div>


{% for post in site.repositories reversed %}

    {% include archive-single.html %}

{% endfor %}
