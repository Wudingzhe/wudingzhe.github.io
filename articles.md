---
layout: default
title: Articles
---
<div class = "articles">

<h2> Articles </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "article" %}
        <li>
            <a href="{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>

</div> 