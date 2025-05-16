---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
![Universe icon](/universe.jpeg){: width="400" .center-image border-radius="50%" display="block" margin="0 auto" }

## [Professional Experience](/professional-experience)

## [Education](/education)

---

{% for post in site.posts %}
  <h3>{{ post.title }}</h3>
  <p>{{ post.excerpt }}</p>
  <h3><a href="{{ post.url }}">click to read further...</a></h3>

  ---
{% endfor %}