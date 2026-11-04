---
title: "Babl"
summary: "Un GROS projet : Babelio recrutez moi svp."
#externalUrl: ""
cover : "cover.jpg"
showSummary: true
date: 2026-04-11
draft: false
---

## Origine du projet

Cela fait plus d'un an que je rentre minutieusement mes lectures sur Babelio avec mes notes, mes critiques, etc... (onglet "Réseaux" du site si jamais). Bref, c'est pas le sujet.

Sur Babelio, il y a un évènement particulièrement alléchant : [les opérations masse critique](https://www.babelio.com/massecritique.php). Pour faire simple, c'est un évènement mensuel avec plusieurs centaines de livres que vous pouvez "demander", et qu'on vous envoie gratuitement en échange d'une critique. Dit comme ça, c'est plutôt simple mais dans les faits je n'ai encore jamais reçu de livre avec ce processus.

A chaque fois, plusieurs centaines de livres sont listés, et il n'est pas question de demander des livres au hasard: imaginez que j'en reçoive un qui n'est pas du tout à mes goûts, la lecture serait très ennuyeuse. Donc chaque mois, je me retrouve à lire les titre et résumés de tous ces livres pour ne demander que ceux qui pourraient potentiellement m'intéresser... 

C'est très fastidieux.

## L'idée

J'ai une petite formation en IA (pas sur les *méchants* LLMs mais plutôt pour utiliser des modèles de Machine Learning pour l'analyse de données) et je code en Python sur mon temps libre. C'est un passe temps utile pour se créer de petits outils logiciels.

Du coup, je me suis dit que c'était l'occasion de créer une interface pour faire cette sélection à ma place ! Il suffit d'annoter quelques livres que j'ai lus pour apprendre à un modèle ce que j'aime/n'aime pas. Ensuite, il devrait pouvoir en tirer un pattern et prédire quels livres des [opérations masse critique](https://www.babelio.com/massecritique.php) pourraient m'intéresser ! 

Bon. Alors. Cela parait facile sur le papier mais c'était en réalité une bien belle galère pour plein de raisons presque toutes liées à la mise en forme des données (comme tout bon projet en science des données finalement). Mais après plus d'un mois de développement, j'ai finalisé une application qui se trouve être bien mieux finie que ce à quoi je m'attendais au départ !

## Le résultat

Je ne vais pas essayer d'expliquer le fonctionnement ici puisque tout est disponible sur GitHub, mais pour faire simple l'application regroupe :
- 🏷️ Un outil d'annotation pour indiquer les livres que vous aimez ou pas
- 💡 Un outil de recommandation pour plus de 50 000 livres
- 💡 Un outil de recommandation pour les [opérations Masse Critique](https://www.babelio.com/massecritique.php)

{{< github repo="loic-lhf/Babl" showThumbnail=true >}}

C'est (normalement) accessible à tous, alors j'espère que ça servira à d'autres !

**_Humainement, la bise. LL._**