---
title: CKL Project
subtitle: ChecK-in Less Project
date: '2020-05-29'
thumb_image: images/projects/ckl-1.png
image: images/projects/ckl-1.png
layout: project
---
Qui n’a pas connu l’expérience douloureuse de partir en vacances en famille et de se retrouver au péage de Vienne-Reventin sur l’A7 : à l’arrêt. Il fait 36°C. Cela fait environ 7 heures que vous roulez, les enfants, après quatre films Disney enchainées, semblent avoir chopés la myxomatose et commencent à émettre des sons stridents. La pression est à son apogée. 

![péage bondé][ckl-2]

Alors, à la vue des voitures circulants sur la voie de gauche sans soucis aucun, passant ce fameux péage à 30km/h, vous maudissez le fait de ne toujours pas avoir franchi le pas de l’achat du fameux badge de télépéage. 

Ce qui est valable pour les autoroutes, est tout autant valable pour Eurotunnel. Nous n’avons aucun plaisir à attendre, à saisir des informations sur un écran tactile, à attendre qu’une barrière veuille bien se lever.  

Et bien c’est là que le projet CKL prend tout son sens : « **Transformer le smartphone de nos clients en badge télépéage !** » 

 ![check-in][ckl-3]

## Périmètre initial du projet 

Il s’agit dans un premier temps de déporter l’application de voie des péages vers l’application mobile déjà existante et gérant actuellement les réservations de nos clients. 

Ce déport n’est en fait que le prolongement du parcours client sur son smartphone, comme cela se fait déjà dans le domaine aérien. Ainsi, le client est notifié quelques heures/jours avant son passage de la possibilité pour lui de faire un pré-checkin via l’application mobile. 

Nous avons alors essentiellement trois cas de figure :  

 1 L’ensemble des informations issues de la réservation est cohérent par rapport au passage du client (véhicule, heure de la mission, etc.). Dans ce cas, une fois le pré-check-in validé, lorsque le client arrivera en gare de péage, le système de détection de plaque reconnaît le client comme à aujourd’hui mais en lieu et place d’arrêter celui-ci pour lui demander des informations, la barrière va simplement se lever.  Reste alors à trouver une solution de remplacement du cintre qui lui est attribué où figure la lettre correspondant à la mission. Encore une fois, nous pouvons dématérialiser ce cintre et afficher/envoyer un pdf affichable sur le smartphone contenant la lettre de la mission et un QR Code rassemblant l’ensemble des informations de la réservation. Au même titre que ce que nous avons connu avec les attestations de déplacement lors de l’épisode COVID. 
 1 Le client souhaite modifier un paramètre par rapport à sa réservation (horaire, véhicule, etc.). Alors dans ce cas, cela s’apparente simplement à une modification de réservation, déjà faisable sur l’application mobile et effectue son pré-check-in dans la foulée. 
 1 Le système de péage ne reconnait pas l’immatriculation du client. Alors dans ce cas, un écran s’affichera sur la borne du péage, avec deux zones : une identique à aujourd’hui, demandant le numéro de réservation (que l’on pourrait appeler « mode dégradé »), l’autre zone contenant un QRCode pouvant être scanner et ramenant le client sur l’application mobile pour effectuer son check-in. 

![screen 1][ckl-4]![screen 2][ckl-5]

### Pour quels avantages ? 

 + Des temps d’attente avant péage nettement amélioré puisque la majorité des transactions en voie pourraient passer d’une minute à une durée voisine de zéro et donc une fluidité améliorée. 
 ![file camion][ckl-6]
 + Une satisfaction pour nos clients. 
 + Plus de contact physique avec les dalles tactiles des voies, en lien avec l’épisode **COVID**. Contribuant ainsi à rassurer nos clients et pouvant être marketé pour nous différencier de nos concurrents. 
 ![chauffeur touch screen][ckl-7]
 ![voiture arrière check-in][ckl-8]
 + Moins de consommation de carburant, moins d’émission de particules fines. 

### Pic de pollution : il faut changer d'air ! 

Sur ce point, nous pouvons faire un calcul rapide : 

Estimons une consommation de 17l/100km lors du redémarrage du véhicule en moyenne sur les 50 premiers mètres à la sortie du péage. Cela représente une consommation de 0.0085 litre d’essence. 

Estimons ensuite le passage au péage à une allure de 30km/h qui équivaut à une consommation de 0.002 litre. 

La différence est donc le coût en carburant de l’arrêt au péage versus notre proposition soit 0.0065 l. 

Sachant que 1 litre d'essence pèse 750 grammes. L'essence est composée à 87% de carbone (C), ce qui correspond à 652 g de C par litre d'essence. Pour brûler ce C en CO2, 1740 g d'oxygène sont nécessaires. La somme nous donne donc 652 + 1740 = 2392 g de CO2 par litre d'essence. 

Dans notre cas, 0.0065 * 2392 = 15.548 g de CO2 par reprise de vitesse en sortie de péage. 

Sachant que 2.6 millions de voitures sont passés au péage en 2019, nous avons donc un total d’environ 40.4 Tonnes d’émission de C02. 

Je ne compte pas le surcoût de 15% de consommation due à la climatisation durant le temps de la transaction de péage, c’est cadeau. 

Pour les camions, je vous passe les calculs ; on arrive à 74.6 Tonnes d’émission de CO2, et nous ne venons de ne parler que du C02... reste toutes les particules fines type NOx, etc. 

Pour imager un peu cela, la masse volumique du C02 étant à 15°C de 1.87kg/m^3, le total représente environ une **vingtaine de piscine olympique** ! 

C’est ça l’impact environnemental des péages d’Eurotunnel. 


## Et plus si affinité, 

Bien évidemment, les applications mobiles peuvent être enrichies avec le reste du parcours client sur notre terminal. Que ce soit le contrôle aux frontières avec la dématérialisation des « APIs », mais aussi les aspects « Duty Free » ou encore l’appel des clients pour l’embarquement. 

L’idée étant de fournir une application unique regroupant l’ensemble des fonctionnalités nécessaire à une expérience client premium.  

**Le projet CKL, c’est savoir rebondir sur l’épisode COVID pour penser le tunnel du futur.**

**C’est ça notre analyse !**

![voiture arrière check-in][ckl-9]


[ckl-2]: /images/projects/ckl-2.PNG "Img 2"
[ckl-3]: /images/projects/ckl-3.PNG "Img 3"
[ckl-4]: /images/projects/ckl-4.PNG "Img 4"
[ckl-5]: /images/projects/ckl-5.PNG "Img 5"
[ckl-6]: /images/projects/ckl-6.PNG "Img 6"
[ckl-7]: /images/projects/ckl-7.PNG "Img 7"
[ckl-8]: /images/projects/ckl-8.PNG "Img 8"
[ckl-9]: /images/projects/ckl-9.PNG "Img 9"