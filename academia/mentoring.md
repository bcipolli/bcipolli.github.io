---
layout: page
document-class: mentoring
nav-class: academia
nav-title: mentoring
title: mentoring
permalink: /academia/mentoring/
weight: 5
---
{% assign students=site.data.map-students|sort:"first-name"|sort:"last-name" %}

<img class="col one right" src="{{ '/img/map.png' | prepend:site.baseurl }}">

<a name="MAP"></a>
<p>
  From November 2015 through May 2016, I will be working with 12 high school students
  from the <a href="http://education.sdsc.edu/studenttech/?page_id=879" target="_blank">Mentor Assist Program</a> (MAP). This program is a new joint
  program between UCSD and SDSU, aiming to provide scientific mentorship to advanced
  junior-standing students.
</p>

<p>
  We are using <a href="https://piazza.com/class/igiuh1qf14a2al">Piazza</a> to work as a group and to keep in touch.
  We are using Google Docs to create <a href="">project plans</a>,
  <a href="">log our working hours</a>,
  and to <a href="">keep meeting notes</a>.
</p>

<p>
  Three students are working with me to advance research projects.
  <ul>
  {% for student in students %}
    {% if student.type == 'research' %}
      {% include map-student-list-item.html %}
    {% endif %}
  {% endfor %}
  </ul>
<p>

<p>
  Eight students are working on independent projects. I am meeting
  with them once every two weeks for some basic training, status updates, and
  overall group support.

  <ul>
  {% for student in students %}
    {% if student.type == 'project' %}
    <li>
      {% include map-student-list-item.html %}
    </li>
    {% endif %}
  {% endfor %}
  </ul>
</p>

<p>
</p>
