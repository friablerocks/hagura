---
layout: default
---
<h1 class="headline">{{site.title}}</h1>
<p>Hello, world!</p>
{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
<style>.home{display:none;}</style>
