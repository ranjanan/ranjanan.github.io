---
layout: page
title: projects
permalink: /projects/
---

<!---
{% for project in site.projects %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
-->



- [**Circuitscape.jl**](https://github.com/Circuitscape/Circuitscape.jl): A Julia implementation of the Circuitscape project. Circuitscape borrows ideas from electrical circuit theory to model landscape connectivity.
- [**AlgebraicMultigrid.jl**](https://github.com/JuliaLinearAlgebra/AlgebraicMultigrid.jl): A package that solves sparse linear systems via algebraic multigrid (AMG).
- **Miletus.jl**: A package that models financial contracts and values them using high-performance valuation routines.
- [**ArrayFire.jl**](github.com/JuliaComputing/ArrayFire.jl): A package for heterogeneous computing, which allows you to accelerate code using a simple array interface.