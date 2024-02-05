---
title: Full-stack Optimization of Ultra-low-power TPGs for Intelligent Cyberphysical Systems (FOUTICS)
layout: archive
toc: true
---

![Foutics](/assets/images/foutics-logo_color_large.png)

FOUTICS is funded by ANR, the French project-based funding agency in France, under contract [ANR-22-CE25-0005](https://anr.fr/Project-ANR-22-CE25-0005), from 2022 to 2026.

## Abstract

The aim of the FOUTICS project is to propose full-stack, open-source methods and tools to train and infer ultra-lightweight AIs, by extending, implementing, and optimizing Tangled Program Graphs (TPGs), a recent light-by-construction machine learning technique based on genetic programming principles. Exploiting the TPG efficiency and integrating energy optimization at its core, FOUTICS will create methodologies to implement energy efficient AI, capable of nanoseconds reaction time on hardware platforms ranging from Ultra-Low Power embedded devices to reconfigurable devices. Extending TPGs to new learning environments, FOUTICS will enable real world Cyber-Physical System use cases and will optimize energy use from training to physical execution on the factory floor.

## Contributors

### Coordinator

- [Mickaël Dardaillon, Associate professor](http://dardarel.github.io/)

### Researchers

- [Nicolas Beuve, Associate professor](http://www.beuve.net/)
- [Karol Desnos, Associate Professor](http://kdesnos.fr/)
- [Thibaut Marty, Associate Professor](https://thibautmarty.fr/)

### PhDs

- Paul Allaire, PhD
- Quentin Vacher, PhD

## Updates

{% for post in site.tags["foutics"] %}
    {% include archive-single.html type=entries_layout %}
{% endfor %}