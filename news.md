---
layout: page
permalink: /
pub-type: news
document-class: news
nav-class: main
title: news &amp; blog
description: Recent news &amp; tweets from ... all the things.
weight: 0
---

<div style="width:100%">
    <div style="width: 62%; float: left; padding-right: 7%">
        <p>Follow links above for info about my thoughts and work across the private, public, and social sectors!</p>
        {% assign posts=site.news|sort:"date"|reverse %}
        {% include publications-list.html %}
    </div>

    <div style="width:30%;float: left; position: relative; top:-75px">
        <a class="twitter-timeline" data-dnt="true" href="https://twitter.com/mrquickowl" data-widget-id="663525213989003264">Tweets by @mrquickowl</a>
        <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");
        </script>
    </div>
</div>
