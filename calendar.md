---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

{% for module in site.modules %}
<details closed markdown="block">
<summary> {{module.title}} </summary>
{{ module }}
</details>
{% endfor %}
