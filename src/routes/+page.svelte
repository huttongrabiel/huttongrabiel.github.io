<script>
	import { base } from '$app/paths';
</script>

<body>
	<div class="menu-bar">
		<ul>
			<li class="hutton-grabiel-main"><a href="/">Hutton Grabiel</a></li>
			<li><a href="/portfolio">Portfolio</a></li>
			<li><a href="/about">About</a></li>
		</ul>
	</div>

	<div class="external-links">
		<ul>
			<li><a href="https://www.github.com/huttongrabiel" target="_blank">GitHub</a></li>
			<li>
				<a href="https://www.linkedin.com/in/hutton-grabiel-924856212/" target="_blank">LinkedIn</a>
			</li>
			<li><a href="/pdfs/ObfuscatedHuttonGrabielResume.pdf" target="_blank">Resume</a></li>
		</ul>
	</div>
</body>

<footer>
	<div class="copyright">
		<p>© 2023 Hutton Grabiel</p>
	</div>
</footer>

<style>
	:global(.hutton-grabiel-main) {
		font-family: Iosevka;
		font-weight: bolder;
		font-size: large;
		float: left;
	}

	:global(.hutton-grabiel-main) :hover {
		color: green;
	}

	:global(.menu-bar) {
		border: 10px white;
	}

	:global(.menu-bar ul) {
		list-style: none;
		overflow: hidden;
		font-family: Iosevka;
		margin: 0;
		padding: 0;
		vertical-align: top;
	}

	:global(.menu-bar ul li) :hover {
		color: green;
	}

	:global(.menu-bar ul li a) {
		float: right;
		text-align: center;
		color: black;
		padding: 10px 10px;
		text-decoration: none;
	}

	.external-links {
		padding-top: 20%;
	}

	.external-links ul {
		font-family: Iosevka;
		list-style: none;
		text-align: center;
		text-decoration: none;
	}

	.external-links ul li {
		padding-top: 10px;
	}

	.external-links ul li :hover {
		color: green;
	}

	.external-links ul li a {
		color: black;
	}

	:global(.copyright) {
		font-family: Iosevka;
		font-size: small;
		text-align: center;
		position: fixed;
		bottom: 0;
		width: 100%;
	}
</style>
