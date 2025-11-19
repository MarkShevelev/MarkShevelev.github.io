<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
      <div class="entry">
        {{ post.excerpt }} <!-- This displays the small description -->
      </div>
    </article>
  {% endfor %}
</div>
