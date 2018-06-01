---
layout: home
---

## Sections

{% for item in site.presentations %}
* [{{item.title}}]({{ site.baseurl }}{{ item.url }})
{% endfor %}
