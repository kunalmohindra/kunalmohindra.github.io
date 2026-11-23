---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-image-wrapper">
			<img id="intro-image" src="/images/portrait.jpg"></div>
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Hi, I'm Kunal Mohindra</h1>
			<div id="intro-subtitle">I'm a Machine Learning Engineer at Skydance</div>
			<div id="intro-title-socials">
				{% for link in site.data.social-links %}
					{% if link.on-homepage == true %}
						{% include social-link.html link=link %}
					{% endif %}
				{% endfor %}
			</div>
		</div>
	</div>
	<!-- <hr class="l-middle home-hr"> -->
	<div id="everything-else" class="l-middle">
		<a href="{{ site.url }}/cv"><div><i class="fa fa-portrait icon icon-right-space"></i>CV</div></a>
		<a href="{{ site.url }}/cv/#publications"><div><i class="fa fa-list-ul icon icon-right-space"></i>Publications</div></a>
	</div>
	<div>
		I am interested in building <b>systems for machine learning models</b> to increase their <b>overall efficiency</b> so they meet <b>industry constraints </b>. In particular, I'm focused on reducing latency and memory costs for these models without sacrificing their quality.
	</div>
	<div style="height: 1rem"></div>
	<div>
		I received my Bachelor's and Master's in CS from Georgia Tech, where I worked under <a href = "https://flavineducationlab.com/"> Dr. Flavin </a> and <a href = "https://c21u.gatech.edu/directory/person/jeonghyun-jonna-lee"> Dr. Lee</a>.
	</div>
	<div style="height: 1rem"></div>
</div>

<hr class="l-middle home-hr">



<br>




[gt]: http://www.gatech.edu "Georgia Tech"
[coc]: http://www.cc.gatech.edu "Georgia Tech College of Computing"

[cv]: {{ site.url }}/cv
[polo]: http://www.cc.gatech.edu/~dchau/ "Polo Chau"
[poloclub]: http://poloclub.gatech.edu "Polo Club of Data Science"