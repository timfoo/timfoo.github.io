---
title: "Posts"
layout: archive
permalink: /blog/
collection: blog
author_profile: true
---
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}


{% for post in site.posts %}

{% include archive-single.html %}  

{% endfor %}
