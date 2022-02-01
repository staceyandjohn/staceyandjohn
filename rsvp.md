---
layout: page
title: RSVP
description: 'How to find the venue'
nav-menu: false
image: 'assets/images/t-type/t-type-hollow-dark.jpg'
---

<p>Use this form to let us know who's coming and what your options are for food and drink.</p>

<form action="https://formspree.io/f/mrgjeaka" method="POST">
	<fieldset style="padding:1em;" class="box">
		<h2>Your choices</h2>
		<div class="field half first">
			<label for="name">Name</label>
			<input type="text" name="name" id="name" placeholder="First name" />
		</div>
		<div class="field half">
			<label for="email">Phone number</label>
			<input type="text" name="_replyto" id="email" placeholder="mail@johnhaynes" />
		</div>
		<h3>Starter</h3>
		<div class="field half first" style="margin-bottom: 0;">
			<input type="radio" id="meat1a" name="starter_guest1" value="meat1a">
			<label for="meat1a">
				<h4>Chicken liver parfait</h4>
				<p style="margin-bottom:0;">Burnt onion jam, toasted seed bread</p>
			</label>
		</div>
		<div class="field half" style="margin-bottom: 0;">
			<input type="radio" id="veg1a" name="starter_guest1" value="veg1a">
			<label for="veg1a">
				<h4>Tomato, basil and aubergine stacks</h4>
				<p style="margin-bottom:0;">Finished with vegan pesto (includes mozerella or vegan cheese)</p>
			</label>
		</div>
		<h3>Main course</h3>
		<div class="field half first" style="margin-bottom: 0;">
			<input type="radio" id="meat1b" name="main_guest1" value="meat1b">
			<label for="meat1b">
				<h4>Meat option</h4>
				<p style="margin-bottom:0;">description</p>
			</label>
		</div>
		<div class="field half" style="margin-bottom: 0;">
			<input type="radio" id="veg1b" name="main_guest1" value="veg1b">
			<label for="veg1b">
				<h4>Veg option</h4>
				<p style="margin-bottom:0;">description</p>
			</label>
		</div>
		<div class="field" style="margin-bottom: 0;">
			<h3>Drink</h3>
			<input type="radio" id="red1" name="drink_guest1" value="wine1">
			<label for="red1">
				<h4>Red</h4>
			</label>
			<input type="radio" id="white1" name="drink_guest1" value="wine1">
			<label for="white1">
				<h4>White</h4>
			</label>
			<input type="radio" id="na1" name="drink_guest1" value="wine1">
			<label for="na1">
				<h4>No alcohol</h4>
			</label>
		</div>
		<div class="field first">
			<label for="diet">Dietary requirements (optional)</label>
			<input type="text" name="diet" id="diet" placeholder="e.g. I am vegan and gluten free" />
		</div>
	</fieldset>
	<fieldset style="padding:1em;" class="box">
		<h2>Second guest</h2>
		<p>Please leave this blank if you're attending on your own</p>
		<div class="field">
			<label for="name">Name</label>
			<input type="text" name="name" id="name" placeholder="First name" />
		</div>
		<h3>Starter</h3>
		<div class="field half first" style="margin-bottom: 0;">
			<input type="radio" id="meat2a" name="starter_guest2" value="meat2a">
			<label for="meat2a">
				<h4>Chicken liver parfait</h4>
				<p style="margin-bottom:0;">Burnt onion jam, toasted seed bread</p>
			</label>
		</div>
		<div class="field half" style="margin-bottom: 0;">
			<input type="radio" id="veg2a" name="starter_guest2" value="veg2a">
			<label for="veg2a">
				<h4>Tomato, basil and aubergine stacks</h4>
				<p style="margin-bottom:0;">Finished with vegan pesto (includes mozerella or vegan cheese)</p>
			</label>
		</div>
		<h3>Main course</h3>
		<div class="field half first" style="margin-bottom: 0;">
			<input type="radio" id="meat2b" name="main_guest2" value="meat2b">
			<label for="meat2b">
				<h4>Meat option</h4>
				<p style="margin-bottom:0;">description</p>
			</label>
		</div>
		<div class="field half" style="margin-bottom: 0;">
			<input type="radio" id="veg2b" name="main_guest2" value="veg2b">
			<label for="veg2b">
				<h4>Veg option</h4>
				<p style="margin-bottom:0;">description</p>
			</label>
		</div>
		<div class="field" style="margin-bottom: 0;">
			<h3>Drink</h3>
			<input type="radio" id="red2" name="drink_guest2" value="wine2">
			<label for="red2">
				<h4>Red</h4>
			</label>
			<input type="radio" id="white2" name="drink_guest2" value="wine2">
			<label for="white2">
				<h4>White</h4>
			</label>
			<input type="radio" id="na2" name="drink_guest2" value="wine2">
			<label for="na2">
				<h4>No alcohol</h4>
			</label>
		</div>
		<div class="field first">
			<label for="diet">Dietary requirements (optional)</label>
			<input type="text" name="diet" id="diet" placeholder="e.g. I am vegan and gluten free" />
		</div>
	</fieldset>
	<!-- <div class="field">
		<label for="message">Dietary Requirements</label>
		<textarea name="message" id="message" rows="6"></textarea>
	</div> -->
	<ul class="actions">
		<li><input type="submit" value="Send RSVP"  /></li>
		<!-- <li><input type="reset" value="Clear" /></li> -->
	</ul>
</form>