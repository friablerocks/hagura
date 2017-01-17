---
layout: default
---
<style>.home{display:none;}</style>
# {{site.title}}

{% for post in site.posts %}
### [{{post.title}}]({{post.url | prepend: site.baseurl}})
{% endfor %}
