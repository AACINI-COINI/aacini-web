---
layout: pages
title: Autoridades
permalink: /autoridades/
menu: 3
---

La **AACINI** es una Asociación Civil sin fines de lucro y de carácter educativo cultural, cuya Comisión Directiva está integrada por:

<table>
  <tbody>
  {% for autoridad in site.data.autoridades %}
    <tr>
      <td>{{ autoridad.posicion }}</td>
      <td>{{ autoridad.nombre }}</td>
    </tr>
  {% endfor %}
  </tbody>
</table>
