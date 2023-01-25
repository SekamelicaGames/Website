---
layout: ../../../../layouts/project.astro
title: Tokotoko
devteam: Kalank
orderId: 1
categoryId: 2
img: '/assets/projects/tokotoko/tokotoko_1.png'
shortDescription: |
  Jeu d'aventures et de dessin en réalité augmentée
---

<h4><a class="accent">Genre :</a> Jeu d'aventure et de dessin en réalité augmentée</h4>
<h4><a class="accent">Statut :</a> Sorti en 2021</h4>
<h4>
<a class="accent">Plateformes :</a>
<a href="https://play.google.com/store/apps/details?id=com.kalank.tokotokogame&hl=fr&gl=US" class="button_nouppercase">Android</a>
<a href="https://apps.apple.com/fr/app/tokotoko-ar-histoire-cr%C3%A9ative/id1465697956" class="button_nouppercase">iOS</a>
</h4>
<h4><a class="accent">Moteur :</a> Unity</h4>
<p class="description">
Tokotoko est un jeu mobile, développé sur Unity, à destination d'Android et d'iOS pour les mobiles supportant la réalité augmentée.
<br>
Dans Tokotoko, on suit l'histoire d'un groupe de Tokotokos; des personnages créatifs et haut en couleurs; et notamment celle de Hako, qui cherche à devenir une artiste.
Dans cet aventure riche en dialogues, on aide Hako et les autres Tokotokos via des interactions uniques et des puzzles, qui passent surtout par le dessin, qui se fait sur du vrai papier, avec un vrai crayon, en mettant à profit la réaliter augmentée. Les dessins que l'on réalise pourront ainsi débloquer des situations, ou simplement permettre d'exprimer sa créativité en décorant la zone de jeu, ou encore à interagir avec les Tokotokos qui vont réagir et nous donner leurs appréciations !
</p>
<div style="display: grid; grid-template-columns: 1fr 1fr 1fr;">
  <img style="max-width: 300px; border: 3px solid var(--c-sekared);" src="/assets/projects/tokotoko/tokotoko_2.png">
  <img style="max-width: 300px; border: 3px solid var(--c-sekared);" src="/assets/projects/tokotoko/tokotoko_3.png">
  <img style="max-width: 300px; border: 3px solid var(--c-sekared);" src="/assets/projects/tokotoko/tokotoko_4.png">
</div>
<h4><a class="accent">Rôle dans la création du jeu :</a></h4>
<p class="description">
J'ai principalement travaillé sur les points suivants :
<ul>
  <li>
    Architecture du projet
  </li>
  <li>
  Développement d'outils dédiés à la réalité augmenté pour setup une zone de jeu agréable et contextuelle et faciliter au mieux la gestion du placement et déplacement des objets et personnages du jeu dans l'éditeur avec ces contraintes.
  </li>
  <li>
    Développement d'un outil permettant la création de listes d'actions diverses et varier à executer sans avoir à coder, afin de permettre à notre game designer de créer des séquences cinématiques et de gameplay riches et variées, le tout fonctionnant dans un espace en réalité augmenté.
  </li>
  <li>
    Développement d'un système de dialogue (lui-même incluant des listes d'action pour l'enrichir avec des animations)
  </li>
  <li>
    Shader (shader global des tokotokos et éléments de jeux, shaders spécifiques des bulles de dialogues, shaders spécifiques aquatiques, et shaders d'effet de post-processing entre autres)
  </li>
  <li>
    Customisation du pipeline de rendu pour optimiser pour mobile tout en permettant d'avoir les différents effets spécifiques voulus : background réalité augmentée, segmentation réalité augmentée (les mains des personnes peuvent passer devant les éléments virtuels), éléments avec une transparence spéciale pour les souvenirs, éléments de jeu classiques,
    effets aquatiques et effets de filtres photos.
  </li>
  <li>
    Système de sauvegarde
  </li>
  <li>
    Système et outils de localisation
  </li>
  <li>
    UI et inputs tactiles
  </li>
</ul>
</p>