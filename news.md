---
layout: page
permalink: /
nav_title: home
title: news
description: Recent news &amp; tweets from San Diego.
weight: 0
---


<div style="width: 67%; float: left; padding-right: 2%">
<ul class="post-list">
{% for news_item in site.news reversed %}
    <li>
        <h2>
        <a class="news-title"{% if news_item.redirect %} href="{{ news_item.redirect }}"{% endif %}>
        {{ news_item.title }}
        </a>
        </h2>
        <p class="post-meta">{{ news_item.date | date: '%B %-d, %Y' }}</p>
        <p>{{ news_item.description }}</p>
      </li>
{% endfor %}
</ul>
</div>

<div style="width:30%;float: left; position: relative; top:-100px;">
<a class="twitter-timeline" data-dnt="true" href="https://twitter.com/mrquickowl" data-widget-id="663525213989003264">Tweets by @mrquickowl</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");
</script>
</div>