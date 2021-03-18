# TicTac Boom Tutorial

## Principe du jeu
### Principe du jeu
Le tic-tac-boom fonctionne avec 2 cartes.
- Une carte est sur le bord du terrain.
- Une carte est dans le ballon.
Si le ballon tombe à terre, un certain temps, 
la carte affiche une tête de mort et l'équipe qui a laissé tombé la balle a perdu.

## Changer la mélodie 
### Pour changer la mélodie 
Remplacer ces briques par d'autres briques Orange
```blocks
music.playTone(262, music.beat(BeatFraction.Quarter))
music.playTone(330, music.beat(BeatFraction.Quarter))
```
```blocks
music.playTone(262, music.beat(BeatFraction.Half))
music.playTone(196, music.beat(BeatFraction.Half))
music.playTone(165, music.beat(BeatFraction.Half))
music.playTone(131, music.beat(BeatFraction.Breve))
```

## Réglages du jeu
### Pour régler le temps de relance
Remplacer les valeurs dans cette brique mathématique
```blocks
Compteur = randint(7, 15)
```

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>