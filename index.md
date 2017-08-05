---
title: Testing GitHub Pages
permalink: index.html
---
## Posts

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . </small></p>
  </li>
  {% endfor %}
</ul>

## Go Away

This site is garbage while i learn how use Jekyll with github pages.
It will likely be garbage when it is done so spend your time so wisely,
somewhere else.

## Support

Having trouble with this site? Too bad, I told you it was garbage!
