---
layout: archive
title: "Repositories"
permalink: /repositories/
author_profile: true
---

{% include base_path %}
**Modular-GenAI**

A modular and clean research framework for Generative AI, based on popular open-source repositories like Transformers, TRL, Diffusions, and CleanRL.

[**Modular-GenAI**](https://github.com/AbdullahVanlioglu/Modular-GenAI)

<br>

**Modular-Baselines**

Modular-Baselines is a library designed for Reinforcement Learning (RL) research. Our goal is to provide a flexible, easy-to-use set of components that can be combined in various ways to enable experimentation with different RL algorithms.

[**Modular-Baselines**](https://github.com/AbdullahVanlioglu/Modular-Baselines)

<br>

<div style="display: flex; gap: 10px;">
  <a href="https://github.com/" class="btn btn-primary" style="text-decoration: none; padding: 10px 20px; background-color: #333; color: #fff; border-radius: 5px;">GitHub</a>
  <a href="https://arxiv.org/" class="btn btn-secondary" style="text-decoration: none; padding: 10px 20px; background-color: #f16624; color: #fff; border-radius: 5px;">arXiv</a>
</div>

**You can find all of my repositories on my Github**

[**Github**](https://github.com/AbdullahVanlioglu)


{% for post in site.repositories reversed %}

    {% include archive-single.html %}

{% endfor %}
