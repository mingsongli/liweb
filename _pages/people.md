---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

The Deep-Time Global Change group works on paleoclimate, stratigraphy, paleohydrology, data assimilation, and quantitative methods in geoscience.

## Current Group

<div class="people-groups">
{% for group in site.data.current_group %}
  <section class="people-group" aria-labelledby="current-group-{{ forloop.index }}">
    <h3 id="current-group-{{ forloop.index }}">{{ group.title }}</h3>
    <div class="people-grid">
    {% for member in group.members %}
      <a class="person-card" href="{{ member.url | relative_url }}">
        <img class="person-card__photo" src="{{ member.image | relative_url }}" alt="{{ member.name }}">
        <span class="person-card__body">
          <span class="person-card__name">{{ member.name }}</span>
          <span class="person-card__role">{{ member.role }}</span>
        </span>
      </a>
    {% endfor %}
    </div>
  </section>
{% endfor %}
</div>

## Former Group Members And Visitors

* [Meng Wang](https://english.nigpas.cas.cn/sourcedb/fyjy/202408/t20240823_683839.html), former Boya Postdoctoral Fellow; now Associate Professor, Nanjing Institute of Geology and Palaeontology, Chinese Academy of Sciences
* [Qingqing Jiang](https://qqjiang-edu.github.io/), former M.S. student; now Ph.D. student, University of Munster
* Haoxun Zhang, former M.S. student
* Hanyu Zhu, former undergraduate student; now Ph.D. student, Peking University
* [Yujing Wu](https://www.imcce.fr/recherche/equipes/asd/members), co-supervised doctoral student; now postdoctoral researcher at IMCCE, Observatoire de Paris
* Ciro Climaco Rodrigues, former associate-supervised M.S. student, National Observatory in Rio de Janeiro; now at Petrobras
* Mariana Aragao Fernandes, former associate-supervised M.S. student, National Observatory in Rio de Janeiro

Prospective students interested in deep-time climate, stratigraphy, paleohydrology, or computational methods in geoscience are welcome to contact me by email.
