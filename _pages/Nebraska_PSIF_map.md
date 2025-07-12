---
title: Nebraska PSIF Map
permalink: /maps/
layout: single
---

<style>
  /* remove margins/padding on the page so the iframe truly fills */
  .map-fullscreen { margin: 0; padding: 0; }
  .map-fullscreen iframe {
    position: fixed;
    top:    0;
    left:   0;
    width:  100vw;
    height: 100vh;
    border: none;
    z-index: 1;
  }
  /* hide the rest of the page */
  .map-fullscreen body > *:not(.map-fullscreen) { display: none; }
</style>

<div class="map-fullscreen">
  <iframe src="/maps/Nebraska_PSIF.html"></iframe>
</div>

