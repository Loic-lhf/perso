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

Cela fait plus d'un an que je rentre minutieusement mes lectures sur Babelio avec mes notes, mes critiques, etc... Et l'application fonctionne vraiment très bien mais ce n'est pas le sujet.

Sur Babelio, il y a un évènement particulièrement alléchant : [les opérations Masse Critique](https://www.babelio.com/massecritique.php). Pour faire simple, c'est un évènement mensuel dans lequel plusieurs centaines de livres peuvent être envoyés gratuitement à des lecteurs de l'application, en échange d'une critique. Il suffit de demander un des livres de la liste, et on a une chance d'être sélectionné dans l'opération. (Bon, dit comme ça, ça parait simple mais dans les faits je n'ai encore jamais été sélectionné... Pas de chance je suppose).

Donc chaque mois, plusieurs centaines de livres sont listés, la plupart totalement inconnus (c'est le but, de rajouter des critiques à ces livres).

Personnellement, je trouve qu'il serait idiot de demander des livres de la list au hasard, ou en nombre. Si je reçois un livre gratuitement et que je dois le critiquer, je préfère que celui-ci me plaise. Donc chaque mois, je me retrouve à lire la fiche de chaque livre de l'opération Masse Critique en cours : auteur, titre, résumé, notes, ...

C'est très fastidieux.

## L'idée

Je code en Python sur mon temps libre et j'ai une petite formation en IA (pas sur les *méchants* LLMs, mais plutôt pour utiliser des modèles de *Machine Learning* qui permettent de faire de l'analyse de données). C'est un passe temps comme un autre, mais que je trouve utile pour se créer de petits outils logiciels.

Du coup, je me suis dit que c'était l'occasion de créer une interface pour faire cette sélection des livres de Masse Crtiique à ma place ! Il suffit d'annoter quelques livres que j'ai lus pour enseigner à un modèle basique ce que j'aime/n'aime pas. Ensuite, il devrait pouvoir en tirer un pattern et prédire quels livres des [opérations masse critique](https://www.babelio.com/massecritique.php) pourraient m'intéresser ! 

Bon. Alors. 

Cela parait facile sur le papier mais c'était en réalité une bien belle galère pour plein de raisons presque toutes liées à la mise en forme des données (comme tout bon projet en science des données finalement). Mais après plus d'un mois de développement, j'ai finalisé une application qui se trouve être bien mieux finie que ce à quoi je m'attendais au départ !

## Le résultat

Je ne vais pas essayer d'expliquer le fonctionnement ici puisque tout est disponible sur GitHub, mais pour faire simple l'application regroupe :
- 🏷️ Un outil d'annotation pour indiquer les livres que vous aimez ou pas
- 💡 Un outil de recommandation pour plus de 50 000 livres
- 💡 Un outil de recommandation pour les [opérations Masse Critique](https://www.babelio.com/massecritique.php)

{{< github repo="loic-lhf/Babl" showThumbnail=true >}}

C'est (normalement) accessible à tous, alors j'espère que ça servira à d'autres !

**_A la prochaine, la bise. LL._**