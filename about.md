---
title: About
layout: page
---
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %})

<p></p>
I was born in Zhejiang Province, P.R. China on September 20. I am now studying Industrial Enigineering at Zhejiang University.

<p>Here is my <a href="../files/cv.pdf">CV</a>.</p>

<h2>Skills</h2>

<ul class="skill-list">
	<li>Programming: Python, MATLAB, C</li>
	<li>Data platforms: MySQL, Snowflake</li>
	<li>Data visualization: Power BI</li>
	<li>Machine Learning</li>
	<li>Data Analysis</li>
	<li>Language: English(C2), German(B2)</li>
</ul>

<h2>Projects</h2>

<ul>
	<li>Machine Learning for Medical Images: 
	- Adapted 2D Y-Net to the 3D domain
	- Trained the 3D segmentation model in a few-shot setting using meta-learning to tackle the issue of limited medical data availability.
    </li>
	<li>Machine Learning for 3D Reconstruction:
	- Performed shape reconstruction from a single-view image.
	- Employed a classification network to extract global features and combine them with local features derived from the single-view image. This fusion of features enables the 3D network to acquire sufficient information for successful shape reconstruction.
	</li>
	<li>Autonomous Search and Rescue System:
	- Utilized a simulated avalanche scene and UAV model built by Unity
	- Implement Robot Operating System (ROS) for detector simulation, path planning, trajectory planning, and control
	</li>
</ul>
