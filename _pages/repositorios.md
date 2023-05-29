---
layout: page
title: Repositorios Github
permalink: /repositorios
---

<h2 class="mb-4 text-2xl font-extrabold leading-none tracking-tight text-gray-900 md:text-3xl lg:text-4xl dark:text-white">Minhas estatísticas:</h2>
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repositories/repo_user.html %}
</div> 

---

<h2 class="mb-4 text-2xl font-extrabold leading-none tracking-tight text-gray-900 md:text-3xl lg:text-4xl dark:text-white">Repositorios <span class="text-[#35D758] dark:text-[#35D758]">GitHub</span>:</h2>
<div>
{% if site.whoisclebs.repositories %}

<div class="grid grid-cols-2">
    {% for repo in site.whoisclebs.repositories %} 
            {% include repositories/repo.html repository=repo %} 
        {% endfor %}
</div>
{% endif %}
</div>