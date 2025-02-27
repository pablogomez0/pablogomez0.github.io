---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for post in site.posts %}
  <h3>{{ post.title }}</h3>
  <p>{{ post.excerpt }}</p>
  <h3><a href="{{ post.url }}">click to read further...</a></h3>

  ---
{% endfor %}

{% include dark-theme.html %}
