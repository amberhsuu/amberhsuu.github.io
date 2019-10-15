---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

---
<h2>I'm Amber Hsu...</h2>

<p>I am currently a Senior studying English and Biochemistry at the University of Washington. I have experience optimizing and creating email engagement campaigns and writing professional copy for everything from Facebook marketing posts and newspaper articles to Residential Advisor newsletters. With my past experience in digital marketing and content strategy, I aim to help companies create personalized marketing campaigns that reach the right audience. I am currently seeking new grad and full-time opportunities. </p>

---
<h2>Skills</h2>

- Content and targeting segmentation development for email nurtures
  - Familiarity with email service provider Adobe Marketo
- Professional copy for varied purposes and audiences
- Social media marketing strategy on various platforms incl. FB and IG
- Large and small scale event planning and facilitation
- Native fluency in English and Chinese (Mandarin)

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
