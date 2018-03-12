---
layout: page
title: Archive
---

{%for post in site.posts%}
<span class="archive">[{{ post.title }}]({{ site.baseurl }}{{post.url  | remove_first: '/'}}) <span class="date">---{{post.date | date: '%-d %B %Y'}}</span></span>
{%endfor%}