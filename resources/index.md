---
title: Resources
redirect_from:
  - /webservers
  - /software
  - /apps
---

# <i class="fas fa-tools"></i>Resources

All of our software, tools, datasets, etc. are 100% open-source, and free for anyone around the world to use and modify.
We strive to make resources that are high quality in every aspect:
cleanly written, robustly constructed and tested, well-documented, easy-to-use, accessible, customizable, and as effective as possible in real-world use.

<!-- section break -->

## Featured

{% capture html %}
{% include resource-list.html type="featured" size="large" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## More

{% capture html %}
{% include resource-list.html type="more" size="small" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Affiliated Organizations

{% capture html %}
{% include resource-list.html type="other" size="medium" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Legacy

{% capture html %}
{% include resource-list.html type="legacy" size="small" %}
{% endcapture %}

{% include centerer.html html=html %}
