---
title: Projects
---

{% for projects in site.projects %}
    ## [{{ project.title }}]({{ project.url }})

    {{project.excert}}
{% endfor %}
