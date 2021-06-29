---
title: "Technology"
tags: Science
cardimage: "images/technology.jpg"
---

Technology is an expanded concept that deals with a species' usage and knowledge of tools and crafts, and how it affects a species' ability to control and adapt to its environment. In human civilization, it is a consequence of science and engineering, although several technological advances predate the formalization of these two disciplines. The term can either be applied generally or to specific areas – examples include construction technology, medical technology, or state-of-the-art technology. 

I hope you like it!

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}