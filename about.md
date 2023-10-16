---
layout: page
title: About
---

Ce blog contient les avancements du projet réalisé dans le cadre du cours IFT6758 - Science des données (Automne 
2023). Ce projet est réalisé par :

{% for author in site.authors %}
    {{ author[1].name }} -- {{ author[1].email }}
{% endfor %}

Ce projet se base sur les données provenant de l'API des statistiques de la LNH. Les données des saisons 2016-2017 à 2020-2021 inclusivement sont incluses dans ce projet.

## Configuration du projet

Pour utiliser le code générer dans ce projet, suivez les instructions suivantes dans votre terminal:

1- Clonez le projet :

```
git clone git@github.com:mathieupelo/ift6758-A08.git
```

2- Créez un environnement virtuel :

```
python3 -m venv <venv_name>
source <venv_name>/bin/activate
```

3- Installez les dépendances:

```
cd ift6758-A08
pip install -r requirements.txt
```