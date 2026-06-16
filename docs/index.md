---
layout: page
title: SilentFlareGToS
permalink: /
---

{% capture gtos_markdown %}
{% include_relative ../GToS.md %}
{% endcapture %}

{{ gtos_markdown | markdownify }}
