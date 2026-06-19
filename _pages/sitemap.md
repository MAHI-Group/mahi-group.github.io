---
layout: single
title: "Sitemap"
permalink: /sitemap/
author_profile: true
sitemap: false
---

A list of the pages on this site. For crawlers, there is also an
<a href="/sitemap.xml">XML version</a>.

<h2>Pages</h2>
<ul>
{% for post in site.pages %}
  {% if post.title and post.permalink and post.sitemap != false %}
  <li><a href="{{ post.permalink }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

{% for collection in site.collections %}
  {% if collection.label != "posts" and collection.docs.size > 0 %}
<h2>{{ collection.label | capitalize }}</h2>
<ul>
  {% for post in collection.docs %}
  <li><a href="{{ post.permalink }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
  {% endif %}
{% endfor %}
