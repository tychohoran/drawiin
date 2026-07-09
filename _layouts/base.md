{% include head.html %}
<body>
<div id="wrapper">
	{% include nav.html %}
	<main id="site_main">
		{{ content | markdownify}}
	</main>
	{% include footer.html %}
</div>
{% include javascript.html %}
</body>
