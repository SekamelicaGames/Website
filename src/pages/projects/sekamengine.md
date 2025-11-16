---
layout: ../../layouts/project.astro
title: Sekam Engine
devteam: Sekamelica
banner: '/assets/projects/sekamengine/banner.png'
bannerStyle: 'project-media-box-accent bannerstyle-default'
genre: Game Engine
status: Abandoned (2022)
platforms: Windows
engine: Sekam Engine
shortDescription: |
  Homemade game engine made in C# and rendered with OpenGL.
---
<div class="center_flex" style="display: block;">
  <p class="description" >
      The Sekam Engine is a game engine made in C# to learn and experiment.<br/>
      The only libraries used are OpenTK for OpenGL and Newtonsoft for Json serialization.
      <br/><br/>
      Features:
    </p>
    <ul style="text-align: left;">
        <li>Handle graphical window using OpenTK.</li>
        <li>Game loop (logic/render).</li>
        <li>Inputs handling.</li>
        <li>Maths (Vector2, Vector3, Vector4, 4x4 Matrixes).</li>
        <li>Scene tree with entities with components.</li>
        <li>
        Shader and materials handling. They features:
          <ul>
            <li>Special file format to handle vertex shader and fragment shader in the same file (similar to Unity's surface shader).</li>
            <li>Textures and normal maps.</li>
            <li>Lighting (Ambiant, Specular, Diffuse) and Emissive.</li>
            <li>Text rendering.</li>
            <li>Camera and lighting data buffers.</li>
          </ul>
        </li>
        <li>Orthographic and perspective cameras.</li>
        <li>Forward rendering pipeline: Display 3D models, texts, and user interfaces with their materials seen by cameras on screen, optimizing as much as possible the buffers to avoid draw calls.</li>
        <li>Serialization and deserialization of scenes to save game scenes.</li>
        <li>Creating a bitmap file importer to handle text fonts.</li>
        <li>Creating text components generating 3D models of text optimized for rendering.</li>
        <li>Creating an .obj file importer to handle 3D models.</li>
        <li>Creating a custom immediate mode GUI library handling quad, texts, toggles, buttons and scrollbars.</li>
        <li>Audio Player.</li>
        <li>Basic freecam controller to test scenes.</li>
      </ul>
</div>
<h4><a class="accent">Screenshots<br></a></h4>
<img class="project-media-box" alt="sekamengine pic 1" src="/assets/projects/sekamengine/pic_1.png">