---
layout: ../../../../layouts/project.astro
title: Sekam Engine
devteam: Sekamelica
orderId: 2
categoryId: 1
img: '/assets/projects/sekamengine/sekamengine_1.png'
shortDescription: |
  Moteur de jeu maison réalisé en C# et rendu avec OpenGL
---

<h4><a class="accent">Genre :</a> Moteur de jeu maison</h4>
<h4><a class="accent">Statut :</a> Arrêté en 2022</h4>
<p class="description">
Le Sekam Engine est un moteur de jeu maison réalisé en C# pur a des fins d'expérimentation et d'apprentissage.
<br>
Les seules librairies utilisées sont OpenTK pour OpenGL et Newtonsoft pour la sérialisation/désérialisation Json.
<br><br>
<img style="width: 100%; border: 3px solid var(--c-sekared);" src="/assets/projects/sekamengine/sekamengine_2.png">
<br>
Les fonctionnalités principales sont les suivantes :
<ul>
  <li>
  Gestion d'une fenêtre graphique à l'aide d'OpenTK
  </li>
  <li>
  Gestion de la game loop (boucle d'update logique et boucle de rendu)
  </li>
  <li>
  Gestion des inputs
  </li>
  <li>
  Mathématiques de vector2, vector3, vector4 et matrices 4x4.
  </li>
  <li>
  Organisation de scènes en arborescence contenant des entités qui peuvent elles-mêmes contenir des components qui leur donnent des fonctionnalités.
  </li>
  <li>
  Gestion de shaders et materiaux. Avec entre autres :
    <ul>
      <li>
      Formattage spécial de fichier pour gérer le vertex shader et le fragment shader dans le même fichier (assez similaire à un surface shader dans Unity)
      </li>
      <li>
        Textures et normal maps
      </li>
      <li>
        Lighting (Ambiant, Specular, Diffuse) et Emissives
      </li>
      <li>
        Textes
      </li>
      <li>
        Et donc les buffers d'informations de caméra et lighting sont gérés.
      </li>
    </ul>
  </li>
  <li>
  Caméra orthographique et caméra perspective.
  </li>
  <li>
  Pipeline de rendu type forward rendering : Affichage de modèles 3D, texte et interfaces avec leur matériaux vus par les caméras sur l'écran, en optimisant autant que possible les buffers pour éviter les draw calls.
  </li>
  <li>
  Sérialisation et désérialisation de scènes pour sauvegarder des scènes de jeu.
  </li>
  <li>
  Création d'un importeur de fichier bitmap font file pour gérer les polices d'écritures.
  </li>
  <li>
  Créations de component textes qui génèrent des modèles 3D optimisés pour le rendu.
  </li>
  <li>
  Création d'un importeur de fichiers .obj pour gérer les modèles 3D.
  </li>
  <li>
  Création d'une librairie custom d'immediate mode GUI, gérant quad, textes, toggles, boutons et scrollbars.
  </li>
  <li>
  Audio Player
  </li>
  <li>
  Controller freecam basique pour tester les scènes
  </li>
</ul>
</p>
<br>
