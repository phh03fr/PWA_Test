---
layout: default
title: Accueil
permalink: /
---

<section class="hero">
  <p class="eyebrow">Jekyll + GitHub Pages</p>
  <h1>Un mini-site simple, rapide et maintenable</h1>
  <p>Le contenu est écrit en Markdown. Le header, le footer et la navigation sont partagés entre toutes les pages.</p>
  <a class="button" href="{{ '/services/' | relative_url }}">Découvrir les services</a>
</section>

<section>
  <h2>Pourquoi cette structure ?</h2>
  <div class="cards">
    <article class="card">
      <h3>Réutilisable</h3>
      <p>Les éléments communs sont placés dans <code>_includes</code>.</p>
    </article>
    <article class="card">
      <h3>Cohérent</h3>
      <p>Le layout <code>default.html</code> fournit la structure de chaque page.</p>
    </article>
    <article class="card">
      <h3>Facile à publier</h3>
      <p>Un push sur GitHub suffit après activation de GitHub Pages...</p>
    </article>
  </div>
</section>
