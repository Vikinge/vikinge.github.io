# Midwater


### Blogger



<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | timeago }}<br>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
