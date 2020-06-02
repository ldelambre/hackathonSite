
---
title: ET-Drive
subtitle: Drive system for Victor Hugo and Charles Dickens buildings
date: '2019-04-30'
thumb_image: images/projets/ET-Drive_thumb.jpg
image: images/projets/ET-Drive.jpg
layout: project
---

## Contexte

Nos 2 terminaux ont chacun un bâtiment abritant des commerces et des restaurants. Les clients peuvent s'y rendre après avoir passé les péages, avant les contrôles frontaliers en UK et après en FR.  Les tarifs pratiqués dans les boutiques sont souvent attractifs et, avec le Brexit, il est possible que le duty free revienne (On croise le doigts) 

## Objectifs

Le but du projet est d'apporter le système de la vente à emporter en ne quittant pas sa voiture, système que l'on retrouve dans la grande distribution, certaines pharmacies et dans les fast foods.

 1. Limiter les contacts
Actuellement, lors des achats, il y a contact potentiel avec les autres clients ainsi qu'avec les employés. Le contexte actuel impose de limiter au maximum ces contacts, surtout si on est une personne à risque. 
Ici, la commande se fait via Internet et les marchandises sont déposées directement dans le coffre => Contactless!

 2. Gain de temps
Si le client ne prévoit pas d'arriver un peu en avance ou s'il est retenu sur la route ou dans les contrôles frontaliers, il embarquera directement sans pouvoir passer en boutiques et ratera de superbes affaires!
Avec le Drive, quelques minutes suffisent pour récupérer ses achats.

## Workflow (WIP)

1. Le client réserve sa traversée et est invité à faire ses emplettes ou réserver ses repas sur les sites des boutiques participantes. Les sites des partenaires nous envoies les références des commandes avec les numéros de réservation associés.
2. Lorsque le client passe au péage, le système vérifie s'il y a des commandes associées et notifie les partenaires que le client est arrivé sur le terminal. Pour le terminal FR, on peut essayer de fournir un temps approximatif de traversée des contrôles.
3. Un numéro de place est fourni au client sur le cintre.
4. Le client arrive devant la barrière contrôlant l'accès au drive, la plaque est reconnue (ou alors il scanne son cintre à une borne)
5. Le système notifie le(s) partenaire(s) de l'arrivée du client
6. Le client se gare à la place assignée,  ouvre son coffre et retourne dans sa voiture.
7. Le(s) employé(s) déposent les commandes dans le coffre et scanne(nt) le cintre (ou un autre élément envoyé par email au client au préalable), puis ferme le coffre.
8. Le client reprend sa traversée
9. Le système notifie le système du partenaire que la commande a été retirée.

## Difficultés

1. Le partenaire doit:

 - Avoir un site permettant de passer commande
 - Le site doit pouvoir demander et stocker le numéro de réservation de la traversée
 - Un système d'API doit être mis en place entre le système du partenaire et celui du Drive

2. Infra
- Des places proches des bâtiments doivent être réservées au Drive à la fois pour le SD et le DD
- Le marquage au sol doit être fait du péage au bâtiment pour guider les clients
- Des barrières et des bornes doivent être installées pour contrôler l'accès aux zones Drive
