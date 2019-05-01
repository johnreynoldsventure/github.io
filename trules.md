Trules is a suite of tools to help online deliberations stay on track and produce good decisions.

![Craftsman working](assets/images/craftsman.jpg)

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
