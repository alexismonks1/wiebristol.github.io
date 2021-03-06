---
layout: default
landing: true
title: Home
order: -1
---

<section class="content medium">
	<div class="container">
		{% include /partials/major-heading headline="Aims & Actions" strapline="We have set specific goals for the society and this is how we aim to achieve them." %}

		<div class="boxes">
			<section class="box">
				<h3>Demystify engineering</h3>
				<p>By having talks, discussions and group meet-ups to discuss various types of engineering.</p>
			</section>
			<section class="box">
				<h3>Remain inclusive</h3>
				<p>You do not have to identify as a women to attend our events, we welcome all 
				like-minded engineers.</p>
			</section>
			<section class="box">
				<h3>Break down stereotypes</h3>
				<p>By increasing exposure overall to the benefits of studying and working in engineering.</p>
			</section>
			<section class="box">
				<h3>Provide opportunities</h3>
				<p>By putting on regular events with industrial partners in order to forge connections and provide information.</p>
			</section>
		</div>

		<header class="major bottom0">
			<br>
			<br>
			<h2>Find out more by visiting us on <a href="http://www.facebook.com/womeninengbristol">Facebook</a> </h2>
			<br>
			<br>
			<a href="http://www.facebook.com/womeninengbristol">
        {% include image image="fb.png" %}
			</a>
		</header>
	</div>
</section>

{% include committee contain=true %}

<section class="content">
	<div class="container" style="text-align: center">
		<p>Find out more by visiting our committee page!</p>
		<ul class="actions">
			<li>
				<a href="{{ "/committee/" | prepend: site.base_url }}" class="button big">See the Committee</a>
			</li>
		</ul>
		<p>Or see what we have on at our events page!</p>
		<ul class="actions">
			<li>
				<a href="{{ "/events/" | prepend: site.base_url }}" class="button big">See the Events</a>
			</li>
		</ul>
	</div>
</section>
