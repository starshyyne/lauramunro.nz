---
layout: page
title: "Blog"
permalink: blog
---

<ul class="blog">

    {% for post in site.posts %}
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
