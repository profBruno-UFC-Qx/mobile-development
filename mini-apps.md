---
title: Mini-apps
nav_order: 22
---

### Mini-apps

A ideia dos mini-apps é realizar práticas focados em poucos conteúdos para fornece um base
sólida de conhecimento prático que no futuro será utilizado no projeto final.

Os aplicativos que serão desenvolvidos, não precisam ser extramente polidos no ponto de vista UI/UX.
O mais importante é que eles sejam funcionais e entreguem os requisitos definidos na documentação.


<table>
 <thead>
    <tr>
        <th> Nome </th>
        <th> Peso </th>
        <th> Relato </th>
        <th> Data de entrega </th>
    </tr>
 </thead>
 <tbody>
{% assign atividades = site.atividades | sort: "numero" %}
{% for atividade in atividades %}
    <tr>
        <td> <a href="{{ atividade.link }}" target="_blank">{{ atividade.nome }}</a></td>
        <td> {{ atividade.peso }} </td>
        <td> <a href="{{ atividade.formulario }}" target="_blank">Formulário </a></td>
        <td> {{ atividade.prazo }} </td>
    </tr>
{% endfor %}
  </tbody>
</table>

