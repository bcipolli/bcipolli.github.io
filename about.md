---
layout: page
title: about
permalink: /about/
---

<img class="col one right" src="/img/prof_pic.jpg">

<br/>
Write your biography here. Tell the world about yourself. Link to your favorite <a href="http://reddit.com" target="blank">subreddit</a>. You can put a picture in, too. The code is already in, just name your picture "prof_pic.jpg" and put it in the img folder. 

Link to your social media connections, too. This theme is set up to use <a href="http://fortawesome.github.io/Font-Awesome/" target="blank">Font Awesome icons</a>, like the ones below. Add your facebook, twitter, linkedin, or just disable all of them. 


<br/>
<hr/>
<br/>
<span class="contacticon center">
	{% if site.email %}<a href="mailto:{{ site.email }}"><i class="fa fa-envelope-square"></i></a>{% endif %}
	{% if site.github_username %}<a href="https://github.com/{{ site.github_username }}" target="_blank"><i class="fa fa-github-square"></i></a>{% endif %}
	{% if site.linkedin_url %}<a href="{{ site.linkedin_url }}" target="_blank"><i class="fa fa-linkedin-square"></i></a>{% endif %}
	{% if site.tumblr_username %}<a href="http://{{ site.tumblr_username }}.tumblr.com/" target="_blank"><i class="fa fa-tumblr-square"></i></a>{% endif %}
	{% if site.twitter_username %}<a href="https://twitter.com/{{ site.twitter_username }}" target="_blank"><i class="fa fa-twitter-square"></i></a>{% endif %}
</span>

<div class="col three caption">
	You can even add a little note about which of these is the best way to reach you.
</div>

