---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<<<<<<< HEAD
#{% bibliography --article %}
=======
{% bibliography --article %}
>>>>>>> parent of 8e1e406... Revert "First vesion to go live"
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
