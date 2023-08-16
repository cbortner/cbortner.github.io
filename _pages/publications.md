---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

In my research, I am interested in applications of theoretical mathematics, including graph theory, combinatorics, and algebraic geoemtry, to problems from biology and physics.  Often this work is categorized as being in the field of <i>algebraic statistics</i>.  I love this work because it allows me to use several different areas of math while also having underlying motivation from the real world for the problems that I work on.  Almost every project I do involves some amount of code for testing examples in Python/Sage, Mathematica, and/or Macaulay2.

Students interested in working with me should be comfortable writing proofs, i.e. have taken MATH 3400 "Set Theory and Logic".  We will learn anything else we need along the way!

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
