---
title: Allometry of the Corpus Callosum
description: a project with a background image
img: /img/projects/rinsel.png
img-caption: Small brains and large brains differ in how much connective tissue exists. Does this affect how the two sides of the brain interconnect?
permalink: /projects/rinsel/
weight: 3
---


<p>
    <b><u>Interhemispheric connectivity across species</u></b><br/>
    It has been argued that the hemispheres
    are asymmetric particularly in humans because our hemispheres are more independent than in other
    mammals.  We hypothesize that the opposite must be true - in order for the two sides to do
    different things, they <i>must</i> be able to talk with each other.
    </p>

<p>
	In this project, <b>we showed that a connectivity between the two hemispheres is stable across species, and is in fact stronger than the average connection.</b> In the process, we shoed that previous reports of decreased connectivity between the hemispheres
    in large-brained animals were based on incorrect assumptions.
</p>

<p>
    The previous report measured brain-related surface areas from 13 primate species
    to estimate connections counts.
    We mined the literature for values needed to estimate actual connection counts from the
    surface area data.
</p>

<div style="width: 100%; padding: 15px; padding-top: 25px; height: 220px;">
    <div class="one left"><img style="height: 200px;" src="{{ '/img/projects/rinsel/w_fig1e_raw.png' | prepend: site.baseurl }}"></div>
    <div class="one left caption" style="height: 200px; vertical-align: middle">
    <p>&nbsp;</p>
    <p>&nbsp;</p>
        Original and parsed figures.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </div>
    <div class="one left"><img style="height: 200px;" src="/img/projects/rinsel/w_fig1e_parsed.png"></div>
</div>

<p>
    To mine the data, I manually annotated over 20 figures from the literature,
    then implementing basic image parsing code to estimate values from the figures. I
    validated the data by comparing summary statistics of my parsed data to those reported
    in the figure, as well as re-creating the figures. All <a href="https://github.com/bcipolli/CallosalData">data and code</a> have been posted to Github.
</p>

<p>
    Representative posters and talks:
    <ul>
        <li>SfN 2014 (<a href="docs/posters/Cipollini_Cottrell_SfN_2014_Rinsel.pdf">Poster</a>)</li>
    </ul>
</p>
