---
layout: page
permalink: /news/
title: news
description: Recent news
weight: 2
---


<div style="width: 70%; float: left">
<ul class="post-list">
{% for news_item in site.news reversed %}
    <li>
        <h2><a class="poem-title" href="{{ news_item.url | prepend: site.baseurl }}">{{ news_item.title }}</a></h2>
        <p class="post-meta">{{ news_item.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
</div>

<div style="width:30%;float: left; position: relative; top:-100px;">
<a class="twitter-timeline" data-dnt="true" href="https://twitter.com/mrquickowl" data-widget-id="663525213989003264">Tweets by @mrquickowl</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");
</script>
</div>