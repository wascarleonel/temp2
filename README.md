<!DOCTYPE html>
<html>
<head>
	<title>My Webpage</title>
	<style>
		body {
			background-color: #011F3B;
			color: white;
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		header {
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 1rem;
			background-color: #0F3867;
		}
		nav a {
			color: white;
			text-decoration: none;
			padding: 0.5rem;
			margin-right: 1rem;
			border-radius: 0.5rem;
			background-color: #3D6CA7;
			transition: background-color 0.2s;
		}
		nav a:hover {
			background-color: #95B8E7;
		}
		.profile {
			width: 5rem;
			height: 5rem;
			border-radius: 50%;
			overflow: hidden;
			margin-right: 1rem;
		}
		.profile img {
			width: 100%;
			height: 100%;
			object-fit: cover;
		}
		.name {
			font-size: 1.2rem;
			font-weight: bold;
			margin-bottom: 0.2rem;
		}
		.title {
			font-size: 0.8rem;
			font-style: italic;
		}
		.section {
			padding: 2rem;
			text-align: center;
		}
		.section h2 {
			font-size: 2rem;
			margin-bottom: 1rem;
		}
	</style>
</head>
<body>
	<header>
		<div class="profile">
			<img src="profile.jpg" alt="Profile picture">
		</div>
		<div class="info">
			<div class="name">Wascar Leonel</div>
			<div class="title">Copywriter | Editor | Educator</div>
		</div>
		<nav>
			<a href="https://example.com">Button 1</a>
			<a href="https://example.com">Button 2</a>
			<a href="https://example.com">Button 3</a>
			<a href="https://example.com">Button 4</a>
		</nav>
	</header>
	<main>
		<section class="section">
			<h2>Section 1</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget lacinia orci. Donec in placerat leo. Ut vel magna enim. Sed vel sem ut mi blandit vehicula. Nunc molestie, quam sit amet vehicula luctus, lectus lacus bibendum augue, vel vehicula augue erat eu velit.</p>
		</section>
		<section class="section">
			<h2>Section 2</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget lacinia orci. Donec in placerat leo. Ut vel magna enim. Sed vel sem ut mi blandit vehicula. Nunc molestie, quam sit amet vehicula luctus, lectus lacus bibendum augue, vel vehicula augue erat eu velit.</p>
		</section>
		<section class="section">
			<h2>Section 3</h2>
