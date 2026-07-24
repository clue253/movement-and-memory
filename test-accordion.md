---
title: Accordion Test
nav_exclude: true
---

{% capture demo %}

This is a test accordion.

- Item 1
- Item 2
- Item 3

{% endcapture %}

{% include accordion.html
id="demo"
title="Accordion Test"
description="Testing the reusable accordion"
open="true"
content=demo
%}