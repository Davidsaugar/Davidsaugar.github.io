---
layout: page
title: "Juegos Mundialmente Conocidos"
category: deportes, videojuegos, eSports

layout: page
title: "Aprende a Protegerte con Juegos"
category: seguridad, juegos, protección

layout: page
title: "Negocios y Juegos"
category: negocios, juegos, simulación
---
<style>
  body {
    background-color: #ffffff; 
  }
</style>

<h2>Juegos mundialmente conocidos</h2>

<ul>
    {% for example in site.data.juegosmundialmenteconocidos %}
      <li>
        <strong>{{ example.name }}</strong> (<span>{{ example.type }}</span>) - {{ example.description }}
      </li>
    {% endfor %}
</ul>

<h2>Data base aprende a protegerte con juegos</h2>

<ul>
  {% for example in site.data.aprendeaprotegerteconjuegos %}
    <li>
      <strong>{{ example.name }}</strong> (<span>{{ example.type }}</span>) - {{ example.description }}
    </li>
  {% endfor %}
</ul>

<h2>Negocios y juegos</h2>

<ul>
  {% for example in site.data.negociosyjuegos %}
    <li>
      <strong>{{ example.name }}</strong> ({{ example.type }}) - {{ example.description }}
    </li>
  {% endfor %}
</ul>

