---
title: Public Access to Neuro-imaging Data
description: Public data for the masses.
img: /img/projects/nidata.png
img-caption: nidata is an open-source project for making public neuroimaging data easy to find, download, and understand how to use.
permalink: /projects/nidata/
weight: 1
---

<p>
	<a href="{{ '/philosophy/' | prepend: site.baseurl }}"> Data must be open</a>--public, easy to access, and well-documented--to be scientific. As a data analyst interested in examining brain images, I found it virtually impossible to locate datasets, let alone download them, understand what data was contained, and figure out how to processess them.
</p>

<p>
	I created the open-source <a href="http://github.com/nidata/nidata">nidata</a> project to accomplish these goals. The project aims to aggregate all the different databases where data exist, provide each with a simple method to access the data (downloads if necessary), and provides documentation with a working example on how to use the data.
</p>

<p>
	The code works from code developed in the <a href="http://github.com/nilearn/nilearn">nilearn</a> project, which uses machine learning to analyze neuroimaging data. I have extended the code, added new databases, and contributed back code to nilearn whenever possible.
</p>

