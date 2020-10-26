---
title: Hi, my name is Tania.
layout: landing
description: 
image: assets/images/banner.jpg
nav-menu: null
---

<!-- Main -->
<div id="main">

<!-- One -->
<a id="about-me"></a>
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>About Me</h2>
		</header>
		<p>I'm a web developer in Toronto. I like solving problems, learning new things (and new ways of doing old things), and pizza. 🍕</p>
	</div>
</section>

<!-- Two -->
<a id="projects"></a>
<div class="inner">
	<header class="major">
		<h2>Projects</h2>
	</header>
		<p>Check out what I've been working on.</p>
</div>
<section id="two" class="spotlights">
	<section>
		<div class="image">
			<img src="{% link assets/images/moodify.png %}" alt="" data-position="center center" />
		</div>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Moodify</h3>
				</header>
				<p>Single-page React app that allows users to filter through their Spotify playlists using custom filtering based on Spotify's audio features data.</p>
				<p><b>Tech stack:</b> NodeJS, Express, ReactJS, Styled-Components, PostgreSQL</p>
				<ul class="actions">
					<li><a href="https://moodify.ca" class="button">Moodify.ca</a></li>
					<li><a href="https://github.com/ScottGrun/moodify" class="button">GitHub Repo</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="{% link assets/images/interviewscheduler.png %}" alt="" data-position="center center" />
		</div>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Interview Scheduler</h3>
				</header>
				<p>React-based single-page meeting scheduler.</p>
				<p><b>Tech stack:</b> ReactJS, Axios, Classnames, Normalize, Storybook, Jest, Cypress</p>
				<ul class="actions">
					<li><a href="https://github.com/rtnrtn/scheduler" class="button">GitHub Repo</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="{% link assets/images/wikimap.png %}" alt="" data-position="center center" />
		</div>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Wiki Map</h3>
				</header>
				<p>Collaborative map creation tool using the Leaflet.js library plus Maptiler and Mapquest APIs.</p>
				<p><b>Tech stack:</b> NodeJS, Express, EJS, jQuery, Ajax, PostgreSQL</p>
				<ul class="actions">
					<li><a href="https://github.com/super8989/WikiMap" class="button">GitHub Repo</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="{% link assets/images/tweeter.png %}" alt="" data-position="center center" />
		</div>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Tweeter</h3>
				</header>
				<p>Single-page Twitter clone.</p>
				<p><b>Tech stack:</b> NodeJS, Express, EJS, jQuery, Ajax, MongoDB</p>
				<ul class="actions">
					<li><a href="https://github.com/rtnrtn/tweeter" class="button">GitHub Repo</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<div class="image">
			<img src="{% link assets/images/tinyapp.png %}" alt="" data-position="center center" />
		</div>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>TinyApp</h3>
				</header>
				<p>RESTful URL shortener.</p>
				<p><b>Tech stack:</b> NodeJS, Express</p>
				<ul class="actions">
					<li><a href="https://github.com/rtnrtn/tinyapp" class="button">GitHub Repo</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Contact Form -->
<a id="contact-me"></a>
<section id="contact">
	<div class="inner">
		<section>
			<header class="major">
				<h2>Contact Me</h2>
			</header>
			<p>Connect with me on LinkedIn, check out my GitHub, follow me on Twitter, or send me a message using the contact form.</p>
			<ul class="icons">
				<li><a href="{{ site.linkedin_url }}" class="icon alt fa-linkedin" target="_blank"><span class="label">LinkedIn</span></a></li>
				<li><a href="{{ site.github_url }}" class="icon alt fa-github" target="_blank"><span class="label">GitHub</span></a></li>
				<li><a href="{{ site.twitter_url }}" class="icon alt fa-twitter" target="_blank"><span class="label">Twitter</span></a></li>
			</ul>
		</section>
		<section>
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
	</div> 
</section>

</div>
