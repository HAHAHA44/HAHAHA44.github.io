<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}</h3>
    </li>
  {% endfor %}
</ul>