# PEPEGAME HUB – Game Design (MVP)

## Vision
Super app PEPE avec deux mini-jeux (tap-to-earn + flappy) qui génèrent des points virtuels "PEPE POINTS". Les points servent à mesurer l’engagement et, plus tard, à débloquer des récompenses PEPE réelles.

## Monnaie interne
- Nom : PEPE POINTS
- Gagnés en jouant aux mini-jeux et via missions quotidiennes.
- Pas de token crypto réel au début, tout est off-chain (base de données).

## Jeu 1 – Tap-to-earn PEPE
- Écran avec une grosse mascotte PEPE.
- Chaque tap sur PEPE = +1 PEPE POINT.
- Énergie :
  - 100 points d’énergie max.
  - 1 tap consomme 1 énergie.
  - Recharge : +1 énergie toutes les 30 secondes (même hors ligne).
- Missions quotidiennes :
  - 1 000 taps dans la journée → +500 points.
  - 3 pubs vidéo regardées → boost x2 points pendant 10 minutes.
- Limite journalière :
  - Au-delà de 10 000 PEPE POINTS/jour : les gains sont divisés par 2 pour limiter les bots.

## Jeu 2 – Flappy PEPE
- Gameplay type flappy/runner à un bouton (saut).
- Partie dure 20–40 secondes en moyenne.
- Score brut = distance parcourue + pièces collectées.
- Conversion score → PEPE POINTS :
  - 100 points de score = +10 PEPE POINTS.
- Bonus record du jour :
  - Si le joueur bat son meilleur score du jour → +100 PEPE POINTS.
- Classement :
  - Classement “Top 100 du jour” basé sur le meilleur score.

## Hub / Navigation
- Page Hub :
  - Affichage du pseudo.
  - Solde de PEPE POINTS.
  - Bouton “Tap-to-earn PEPE”.
  - Bouton “Flappy PEPE”.
  - Accès au classement global.
- Page Profil :
  - Historique des points gagnés.
  - Statistiques (taps totaux, meilleur score flappy, etc.).

## Futur (non MVP)
- Connexion MetaMask pour lier une adresse au profil joueur.
- Smart contract de récompenses PEPE avec un pool limité par jour/semaine.
- Échange d’une petite partie des PEPE POINTS contre de vrais PEPE.
