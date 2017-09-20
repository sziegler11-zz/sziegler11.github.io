# Hi.

My name is Sam Ziegler. This page will contain my writings about mathematics, machine learning, books, and more.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>