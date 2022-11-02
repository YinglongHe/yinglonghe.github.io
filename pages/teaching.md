---
layout: page
title: ""
meta_title: "Dr He - Teaching"
header: no
permalink: "/teaching/"
---

<h1>Teaching</h1> <br>

----

<h3>Undergraduate Modules</h3> <br>

<ul>
    {% for post in site.tags.module_ug_current %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" target="_blank">{{ post.title }}</a></li>
    {% endfor %}
</ul>

----

<h3>Links</h3> <br>

- <a href="https://surreylearn.surrey.ac.uk/d2l/home" target="_blank">SurreyLearn</a> (Virtual Learning Environment)