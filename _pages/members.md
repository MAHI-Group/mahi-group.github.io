---
title: "Members"
permalink: /members/
layout: single
author_profile: false
---

## Principal Investigator
{% for member in site.data.members.principal_investigator %}{% include member-card.html member=member %}{% endfor %}

## Group Members
{% assign current_count = site.data.members.phd_students.size | plus: site.data.members.postdocs.size | plus: site.data.members.project_students.size %}
{% if current_count > 0 %}
{% for member in site.data.members.phd_students %}{% include member-card.html member=member %}{% endfor %}
{% for member in site.data.members.postdocs %}{% include member-card.html member=member %}{% endfor %}
{% for member in site.data.members.project_students %}{% include member-card.html member=member %}{% endfor %}
{% else %}
*None yet. [Opportunities available.](/opportunities/)*
{% endif %}

{% if site.data.members.alumni.size > 0 %}
## Alumni
{% for member in site.data.members.alumni %}{% include member-card.html member=member %}{% endfor %}
{% endif %}