---
layout: default
---

<section class="mt-4 mb-5">
	<div class="container">
		<nav aria-label="breadcrumb">
			<ol class="breadcrumb">
				<li class="breadcrumb-item"><a href="/awesome-open-data">Inicio</a></li>
				<li class="breadcrumb-item active" aria-current="page">Recurso</li>
			</ol>
		</nav>
		<br>
		{{ content }}
			{% for category in page.categories %}
                <a class="btn btn-sm btn-indigo mt-2" href="{{site.baseurl}}/categorias.html#{{ category | downcase }}">
                	# {{ category | downcase }}
                </a>
            {% endfor %}
	</div>
</section>