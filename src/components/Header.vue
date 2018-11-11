<template>
  <!-- Off-canvas Navigation -->
  <div class="offcanvas-nav">
    <!-- Head (Fixed Part) -->
    <div class="nav-head">
      <div class="top-bar">
        <div class="nav-toggle" data-offcanvas="close"><i class="flaticon-list26"></i></div>
        <div class="social-buttons">
          <a href="https://www.facebook.com/AppStreetr/?ref=bookmarks" target="_blank" class="sb-facebook"><i class="bi-facebook"></i></a>
          <a href="https://www.instagram.com/streetr.fr/" target="_blank" class="sb-instagram"><i class="bi-instagram"></i></a>
        </div>
      </div>
      <a href="#" class="offcanvas-logo scrollup">
        <div class="icon"><img src="static/img/logo-big.png" alt="Streetr"></div>
        <div class="title">
          Streetr
          <span>Explorez, Découvrez, Contribuez</span>
        </div>
      </a>
      <a href="https://testflight.apple.com/join/2Qitz0zZ" target="_blank" class="btn btn-ghost btn-light icon-left"><i class="bi-apple"></i> Télécharger</a>
    </div>
    <!-- Body (Scroll Part) -->
    <div class="nav-body">
      <div class="overflow">
        <div class="inner">
          <!-- Navigation -->
        </div>
          <!-- Twitter/Blog Tabs -->
      </div>
    </div>
  </div><!-- Off-canvas Navigation End -->
</template>

<script>
  export default {
    name: 'Header',
    data () {
      return {
      }
    }
  }
</script>
