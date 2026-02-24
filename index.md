---
layout: default
title: Inicio
---

<h2>Bienvenido a mi blog</h2>
<p>Este es un espacio creado desde cero con HTML y CSS.</p>

<h3>Mis Entradas:</h3>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>