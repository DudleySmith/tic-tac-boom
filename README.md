
> Ouvrir cette page à [https://dudleysmith.github.io/tic-tac-boom/](https://dudleysmith.github.io/tic-tac-boom/)

# TIC, TAC, BOOOOOM !!!!!
Ce jeu se joue à deux équipes sur un terrain séparé en 2 parties.

Chaque équipe se renvoie la balle, d'un camp à l'autre.

Si la balle reste à terre trop longtemps, vous avez perdu !!!!

## Détails
Pour démarrer la démo, brancher les cartes Micro::bits avec leur bloc de piles.

Il y a une carte dans la chaussette, qui relance le compteur de 10 sec à chaque fois qu'on la lance (en envoyant un message BlueTooth).

Sur l'étagére, la seconde carte recoit le message et relance son propre compteur.

A chaque seconde, la carte émet un top.

Lorque l'on a perdu, 
- la carte sur l'étagère fait une jingle indiquant la fin du jeu.
- les 2 cartes affchent une tête de mort.

## Pour modifier les mélodies
Intervertir les briques Orange avec d'autres

![Mélodie 1](/Melodie1.png)
![Mélodie 2](/Melodie2.png)

## Pour modifier le timing
Modifier le code dans la fonction "Relancer Compteur"
![Timing](/Timing.png)

## Pour télécharger
Appuyer sur le bouton "télécharger" sous l'émulateur

Copier / Uploader le fichier.hex dans la carte Micro::bit (Celle ci apparait dans l'explorateur de fichier sous le nom MICROBIT)

Appuyer sur le bouton "télécharger" sous l'émulateur.

<img src="Simulateur.png" width="25%"/>
<img src="TelechargerIci.png" width="50%"/>
