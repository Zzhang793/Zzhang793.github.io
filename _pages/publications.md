---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Parameter Estimation

* **Ziheng Zhang**, and Nan Chen. Parameter Estimation of Partially Observed Turbulent Systems Using Conditional Gaussian Path- Wise Sampler. Computation 9.8 2021. Full text available at <a href="https://www.mdpi.com/2079-3197/9/8/91/htm"> JGR </a>.

## Inverse Problems

* Upcoming paper on: "Covariance Estimation via Learning the Generalized Whittle-Matérn Model"

* Upcoming paper on: "Hessian Approximation of Inverse Problem via Generalized Whittle-Matérn Model"



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
