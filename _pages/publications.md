---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Publications: 
1. "Overreaction in Football Wagers" with Gary Smith (Pomona), Big Data, 2018, 6(4): 262-270.

## Working Papers:
2. ["Insider CEOs: Lucky or Good?,"](/files/CHHL_InsiderCEOs.pdf) joint with Barton Hamilton (WashU), Andrés Hincapié (UNC), and Noah Lyman (Warwick), submitted.

## Research topics in progress:
Hospital-at-home (HaH) care; noncompete agreements and labor market frictions; health care price transparency; marginal emissions on electrical grids; rural hospital closures; employer-sponsored health insurance bargaining.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
