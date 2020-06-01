---
title: Touch Avoider
date: '2020-06-01'
thumb_image: images/TouchAvoider.jpg
image: images/TouchAvoider.jpg
layout: project
---

## Comment ça, il y a un problème ?

Les bornes tactiles, c'est comme les oreilles : ça se lave ! Ou pas.

Avec la COVID-19, nombreux sont ceux qui auront peur de mettre leurs doigts sur un écran public. Les voilà privés de cafés, de burgers, de traversée de la Manche, voire de l'appartement du siècle.
Mais, avant **ce** *coronavirus*, il y en avait d'autres : réovirus, pneumovirus, enterovirus...
Et puis aussi des bactéries : colibacille, streptocoque, et autres horreurs. Et puis la bonne vieille graisse, les bouts de peau, et nous vous épargnons le reste.

Bref, aucune personne éduquée ne souhaite mettre ses doigts sur un écran prévu à cet effet.

## Les solutions

Il y a déjà des solutions à ce problème.
- Les solutions hydroalcooliques.
- Mettre des gants, si on sait les enlever sans se contaminer.
- Avoir sa boîte de lingettes et faire le ménage partout où on passe. Sympa, mais chronophage.
- Passer par le site web ou par l'appli, pour ne pas toucher la borne. A condition que le site existe...

Hep ?! Il n'y aurait pas une idée, là ?

## **La** solution : Touch Avoider

Ben oui ! Voilà ! Il suffit de faire un site web pour chaque borne. Et on va mettre un QR Code sur un autocollant appliqué sur la borne, pour que l'utilisateur puisse trouver le site facilement.


![QR Code](/images/projects/qrcode.png)

> "Bonne idée, mais c'est trop cher."
> <cite>-- Le Directeur Financier</cite>

## OK, on va faire moins cher.

Pour faire moins cher, on va faire un site web avec **une** interaction. Aussi simple que ce qu'on fait d'habitude sur **un** écran d'une borne tactile.

Et qui va faire le site web ? Ben, heu... le concepteur de la borne ? Nous ? Les deux ? Mais *moins cher* : c'est une exigence.

Jouons les *think tankers* : il faut distinguer deux cas.

### Premier cas : la machine à café

Il n'y a pratiquement pas de possibilité pour la machine de communiquer via l'Internet. En fait, il n'y a peut-être même pas d'écran. Dans ce cas, le QR code est sur un autocollant, et la totalité du geste doit se faire sur notre site web.

L'objectif, dans ce cas, c'est de pouvoir développer le site au plus simple :
- Pas de fioritures web. Une courte série de formulaires, avec une interaction par formulaire.
- La série de formulaires est conçue en observant la borne.
- En fin d'interaction, le serveur web (c) Touch Avoider appelle la borne, directement ou via le système d'information du propriétaire de la borne.

### Deuxième cas : le péage du Tunnel (ou la vente de burgers)

Le propriétaire de la borne est volontaire et compétent techniquement : il peut mettre un petit logiciel à côté de son propre logiciel. Ce petit logiciel (c) Touch Avoider communique avec le serveur web
(c) Touch Avoider avec lequel le téléphone de notre brave utilisateur interagit.
Là, c'est formidable, parce que le petit logiciel (c) Touch Avoider simule les actions sur la borne, à la place de l'utilisateur !

## Synthèse : c'est simple

Si vous n'avez pas tout compris, rassurez-vous. L'équipe planche ferme sur le sujet. La preuve ? Un diagramme qui devrait **tout** clarifier.

![Diagramme de séquence à la limite du langage UML, accessible à bac+8 en Beaux Arts](/images/projects/ta_cinematique.png)

