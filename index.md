---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
author_profile: true
---
<h2> Recent Posts </h2>
{% for post in site.posts %}
 {% include archive-single.html %}
{% endfor %}
