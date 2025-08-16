---
layout: default
permalink: /sample/
title: Sample
---

<!-- Include il widget Netlify Identity -->
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js" type="text/javascript"></script>

<script>
  window.onload = function() {
    if (!window.netlifyIdentity || !window.netlifyIdentity.currentUser()) {
      // Se l'utente non è autenticato, reindirizza alla pagina di login
      netlifyIdentity.open();
    }
  };
</script>

<!-- Contenuto della pagina protetta -->
<h1>Pagina protetta - Solo per utenti autenticati</h1>
<p>Questo contenuto è visibile solo se sei loggato!</p>
