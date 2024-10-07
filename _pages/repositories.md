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

[**odular-Baselines**](https://github.com/AbdullahVanlioglu/Modular-Baselines)


**You can find all of my repositories on my Github**

[**Github**](https://github.com/AbdullahVanlioglu)


{% for post in site.repositories reversed %}

    {% include archive-single.html %}

{% endfor %}
