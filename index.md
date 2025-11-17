---
title: Welcome to my blog
---

Well this is test

# Blog

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%b %-d, %Y" }}</li>
{% endfor %}
</ul>

![Green & Black Minimal Geek Glasses Logo.jpg](/uploads/Green%20&%20Black%20Minimal%20Geek%20Glasses%20Logo.jpg)
