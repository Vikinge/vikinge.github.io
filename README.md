# Midwater.com

### Blog Postings

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_long_string  }}<br>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
