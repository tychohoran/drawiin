{% include head.html %}
<body>
<div id="wrapper">
	{% include nav.html %}
	<main id="site_main">
		{{ content | markdownify}}
	</main>
	<main id="site_main_derja">
		{{ page.derja_text | markdownify }}
	</main>
	{% include footer.html %}
</div>
{% include javascript.html %}
</body>
