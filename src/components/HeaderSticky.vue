<template>
  <header class="navbar gray navbar-sticky">
    <div class="container">
      <!-- Logo -->
      <a href="#" class="logo scrollup">
        <img src="/static/img/logo-small.png" alt="Streetr">
        Streetr
      </a>
      <!-- Social Buttons -->
      <div class="social-buttons">
        <a href="#" class="sb-instagram"><i class="bi-instagram"></i></a>
        <a href="#" class="sb-facebook"><i class="bi-facebook"></i></a>
      </div>
      <!-- Toolbar -->
      <div class="toolbar">
        <a href="https://testflight.apple.com/join/2Qitz0zZ" target="_blank" class="btn btn-ghost btn-primary icon-left"><i class="bi-apple"></i> Télécharger</a>
        <div class="nav-toggle" data-offcanvas="open"><i class="flaticon-list26"></i></div>
      </div>
    </div>
  </header><!-- Navbar End -->
</template>

<script>

  export default {
    name: 'HeaderSticky',
  }
</script>
