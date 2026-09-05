# Provenance des effets sonores

Sons choisis par Tristan le 2026-07-09. Sources Pixabay
(**Pixabay Content License**) et freesound.org (**CC0**) — dans les
deux cas : utilisation commerciale libre, sans attribution requise
(créditée ici par courtoisie).

- `place.mp3` : « Placing playing card » d'oxidvideos (id 522514).
  Joué à chaque MANIPULATION locale du brouillon : carte posée depuis la
  main, sélection déplacée (bouton « Déplacer » ou « Valider la pose »
  avec des cartes sélectionnées), carte déplacée d'une combinaison à une
  autre. PAS de son quand on valide un brouillon déjà en place.
- `draw.mp3` : « Taking playing card 2 » d'oxidvideos (id 522516).
  Joué quand on reçoit sa carte (pioche automatique de début de tour).
  Remplace aussi l'ancien carillon « à toi de jouer » (supprimé).
- `sort.mp3` : première seconde de « Card mixing » de
  freesound_community (id 48088), découpée par tool/trim_mp3.dart.
  Joué au bouton « Trier » (pas au tri automatique de la donne).
- `opp_place1.mp3` / `opp_place2.mp3` : « Taking playing card »
  (id 522520) et « Taking playing card 3 » (id 522513) d'oxidvideos.
  Pose ADVERSE : une occurrence par combinaison touchée, variante
  tirée au hasard, occurrences espacées de 300 ms.
- `select1.mp3` à `select6.mp3` : pack « Pick up cards » de
  SilverDubloons sur freesound.org (sons 817546-817551, licence CC0,
  aperçus HQ 128 kbit/s). Sélection d'une carte (main ou tapis) :
  variante tirée au hasard, rien à la désélection.
- `refus.wav` : synthèse maison, aucun droit à suivre (générateur
  app/assets-reserve/sons-meldfall/gen_sons_meldfall.mjs, bloc REFUS).
  Joué quand une pose est REFUSÉE (message "error" des salles), jamais
  au didacticiel — la bulle d'Athéna y explique au lieu de sanctionner.
