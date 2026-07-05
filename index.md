---
layout: default
title: Home
---

# Journal

Raw notes on JAX/PyTorch fundamentals and RL post-training prep. The fleshed-out version of anything here eventually shows up on [my main blog](https://shimboi.hashnode.dev).

<ul>
{% for post in site.posts %}
  <li>
    <strong>{{ post.date | date: "%b %d, %Y" }}</strong> —
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
