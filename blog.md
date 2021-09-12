---
layout: page
title: "Blog"
---

<ul class="blog">

    {% for post in paginator.posts %}

      <li class="post">
        <div class="post-teaser">
            <h3>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </h3>
            <p class="post-meta">
                <time class="dt-published" datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">
                    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
                    {{ post.date | date: date_format }}
                </time>
            </p>
            <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 500 }}</p>
            <a href="{{ post.url }}">Read this post</a>
            </div>
      </li>
    
    {%- endfor -%}

</ul>

<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}" class="previous">
      Previous
    </a>
  {% else %}
    <span class="previous">Previous</span>
  {% endif %}
  <span class="page_number ">
    Page: {{ paginator.page }} of {{ paginator.total_pages }}
  </span>
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}" class="next">Next</a>
  {% else %}
    <span class="next ">Next</span>
  {% endif %}
</div>
