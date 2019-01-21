---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

---
<h2>I'm Amber Hsu...</h2>

<p>I am currently a Junior studying English and Biochemistry at the University of Washington. In the past few years I've developed an interest in the field of digital marketing, particularly in the workings of digital copy and content strategy. I have experience writing professional copy for everything from Facebook marketing posts and outreach emails to Residential Advisor newsletters and chemistry lab reports.</p>

---
<h2>Skills</h2>

- Professional copy for varied purposes and audiences
- Social media marketing strategy on various platforms
  - Facebook, Instagram, Snapchat
- Inter-organizational outreach and work coordination
- Large and small scale event planning and facilitation
- Education management platforms
  - Exxat, Filemaker, Catalyst, Canvas
- Adobe Photoshop and Illustrator
- Written and spoken English and Chinese (Mandarin)

<h2>Projects</h2>

<ul>
    {% for post in site.posts %}
        {% if post.projects %}
			<li><a href ="{% if post.externalLink %}{{ post.externalLink }}{% else %}{{ site.url }}{{ post.url }}{% endif %}"> {{ post.title }} </a></li>
        {% endif %}
    {% endfor %}
	<!-- <li><a href="https://amberhsuu.github.io/UW-Night-Market-2017/">UW Night Market 2017</a></li>
	<li><a href="https://amberhsuu.github.io/UW-Night-Market-2018/">UW Night Market 2018</a></li>
	<li><a href="https://amberhsuu.github.io/TSA-Clash-of-Clubs/">TSA Clash of Clubs</a></li>
	<li><a href="https://amberhsuu.github.io/HCASB/">Healthcare Alternative Spring Break</a></li> -->
	<br/>
	<a href="/">Go to Project Page ></a>
</ul>
