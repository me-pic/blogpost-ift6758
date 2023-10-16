---
layout: page
title: About
---

Ce blog contient les avancements du projet réalisé dans le cadre du cours IFT6758 - Science des données (Automne 
2023). Ce projet est réalisé par :

{% for author in site.authors %}
    {{ author[1].name }} -- {{ author[1].email }}
{% endfor %}

Ce projet se base sur les données provenant de l'API des statistiques de la LNH. Les données des saisons 
2016-2017 à 2020-2021 exclusivement sont incluses dans ce projet.