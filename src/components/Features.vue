<template>
  <section class="fw-bg bg-align-bottom feature-tabs" style="background-image: url(/static/img/features/bg.jpg);" id="features">
    <!-- Heading when columns stack -->
    <div class="block-heading light-color visible-when-stack">
      <h2>Pourquoi est-ce si spécial ?</h2>
      <span>Regardez ce que Streetr peut offir</span>
    </div>
    <div class="clearfix">
      <!-- Devices -->
      <div class="devices">
        <div class="tablet">
          <img src="/static/img/features/ipad.png" alt="iPad">
          <div class="mask">
            <ul class="screens">
              <li class="active in" id="ts01"><img src="static/img/features/tablet/screen.png" alt="Screen 01"></li>
              <li id="ts02"><img src="static/img/features/tablet/screen.png" alt="Screen 02"></li>
              <li id="ts03"><img src="static/img/features/tablet/screen.png" alt="Screen 03"></li>
              <li id="ts04"><img src="static/img/features/tablet/screen.png" alt="Screen 04"></li>
            </ul>
          </div>
        </div>
        <div class="phone">
          <img src="/static/img/features/iphone.png" alt="iPhone">
          <div class="mask">
            <ul class="screens">
              <li class="active in" id="ps01"><img src="/static/img/features/phone/screen.png" alt="Screen 01"></li>
              <li id="ps02"><img src="/static/img/features/phone/screen1.png" alt="Screen 02"></li>
              <li id="ps03"><img src="/static/img/features/phone/screen2.png" alt="Screen 03"></li>
              <li id="ps04"><img src="/static/img/features/phone/screen3.png" alt="Screen 04"></li>
            </ul>
          </div>
        </div>
      </div>
      <!-- Tabs -->
      <div class="tabs light-color text-center">
        <div class="block-heading hidden-when-stack">
          <h2>Pourquoi est-ce si spécial ?</h2>
          <span>Regardez ce que Streetr peut offir</span>
        </div>
        <!-- Nav Tabs -->
        <!-- Remove data-autoswitch="true" to disable automatic tabs change. -->
        <ul class="nav-tabs" data-autoswitch="true" data-interval="3000">
          <li class="active"><a href="#video-player" data-toggle="tab" data-tablet="#ts01" data-phone="#ps01"><i class="flaticon-film22"></i></a></li>
          <li><a href="#settings" data-toggle="tab" data-tablet="#ts02" data-phone="#ps02"><i class="flaticon-settings20"></i></a></li>
          <li><a href="#file-sharing" data-toggle="tab" data-tablet="#ts03" data-phone="#ps03"><i class="flaticon-layers4"></i></a></li>
          <li><a href="#chat" data-toggle="tab" data-tablet="#ts04" data-phone="#ps04"><i class="flaticon-speech38"></i></a></li>
        </ul>
        <!-- Tab panes -->
        <!-- Use different transitions: 'scale', 'scaleup', 'top', 'bottom', 'left', 'right' and 'flip' -->
        <div class="tab-content">
          <div class="tab-pane transition scale fade in active" id="video-player">
            <h3>Explorez vos alentours</h3>
            <p>Streetr classe les lieux référencés par la communauté par proximité</p>
          </div>
          <div class="tab-pane transition scale fade" id="settings">
            <h3>Ajoutez des lieux</h3>
            <p>Contribuez en ajoutant des lieux</p>
          </div>
          <div class="tab-pane transition scale fade" id="file-sharing">
            <h3>Ajoutez des analyses</h3>
            <p>Partagez votre point de vue sur une oeuvre avec les autres utilisateurs</p>
          </div>
          <div class="tab-pane transition scale fade" id="chat">
            <h3>Gagnez des points</h3>
            <p>Contribuer sur Streetr vous permet de gagner des StreetrPoints, permettant de débloquer des fontionnalités</p>
          </div>
        </div>
      </div>
    </div>
  </section><!-- Feature Tabs End -->
</template>

<script>

  export default {
    name: 'Features',
  }
</script>
