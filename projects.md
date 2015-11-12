---
layout: page
document-class: projects
nav_title: projects
title: projects
description: Research and software projects that I'm working on.
permalink: /projects/
weight: 3
---

{% assign sorted_projects = site.projects | sort:"weight" %}
{% for project in sorted_projects %}
    {% if project.visible != false %}

<div class="project">
    <div class="thumbnail">
        {% if project.redirect %}
        <a href="{{ project.redirect }}" target="_blank">
        {% else %}
        <a href="{{ project.url | prepend:site.baseurl }}">
        {% endif %}
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend:site.baseurl }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}
        <span>
            <h1>{{ project.title | downcase }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
    {% endif %}
{% endfor %}
