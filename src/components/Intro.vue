<template>
  <section class="intro" style="background-image: url(/static/img/intro/intro-bg.jpg);">
    <div class="gradient"></div>
    <div class="container">
      <div class="column-wrap">

        <!-- Left Column -->
        <div class="column c-left">
          <!-- Social Buttons -->
          <div class="social-buttons">
            <a href="https://www.facebook.com/AppStreetr/?ref=bookmarks" target="_blank" class="sb-facebook"><i class="bi-facebook"></i></a>
            <a href="https://www.instagram.com/streetr.fr/" target="_blank" class="sb-instagram"><i class="bi-instagram"></i></a>
            <!-- <a href="#" class="sb-behance"><i class="bi-behance"></i></a> -->
            <!-- <a href="#" class="sb-bitbucket"><i class="bi-bitbucket"></i></a> -->
            <!-- <a href="#" class="sb-codepen"><i class="bi-codepen"></i></a> -->
            <!-- <a href="#" class="sb-deviantart"><i class="bi-deviantart"></i></a> -->
            <!-- <a href="#" class="sb-digg"><i class="bi-digg"></i></a> -->
            <!-- <a href="#" class="sb-dribbble"><i class="bi-dribbble"></i></a> -->
            <!-- <a href="#" class="sb-dropbox"><i class="bi-dropbox"></i></a> -->
            <!-- <a href="#" class="sb-flickr"><i class="bi-flickr"></i></a> -->
            <!-- <a href="#" class="sb-foursquare"><i class="bi-foursquare"></i></a> -->
            <!-- <a href="#" class="sb-github"><i class="bi-github"></i></a> -->
            <!-- <a href="#" class="sb-instagram"><i class="bi-instagram"></i></a> -->
            <!-- <a href="#" class="sb-jsfiddle"><i class="bi-jsfiddle"></i></a> -->
            <!-- <a href="#" class="sb-lastfm"><i class="bi-lastfm"></i></a> -->
            <!-- <a href="#" class="sb-linkedin"><i class="bi-linkedin"></i></a> -->
            <!-- <a href="#" class="sb-paypal"><i class="bi-paypal"></i></a> -->
            <!-- <a href="#" class="sb-pinterest"><i class="bi-pinterest-circled"></i></a> -->
            <!-- <a href="#" class="sb-reddit"><i class="bi-reddit"></i></a> -->
            <!-- <a href="#" class="sb-skype"><i class="bi-skype"></i></a> -->
            <!-- <a href="#" class="sb-soundcloud"><i class="bi-soundcloud"></i></a> -->
            <!-- <a href="#" class="sb-stackoverflow"><i class="bi-stackoverflow"></i></a> -->
            <!-- <a href="#" class="sb-steam"><i class="bi-steam"></i></a> -->
            <!-- <a href="#" class="sb-stumbleupon"><i class="bi-stumbleupon"></i></a> -->
            <!-- <a href="#" class="sb-trello"><i class="bi-trello"></i></a> -->
            <!-- <a href="#" class="sb-tumblr"><i class="bi-tumblr"></i></a> -->
            <!-- <a href="#" class="sb-twitch"><i class="bi-twitch"></i></a> -->
            <!-- <a href="#" class="sb-vimeo"><i class="bi-vimeo-squared"></i></a> -->
            <!-- <a href="#" class="sb-vine"><i class="bi-vine"></i></a> -->
            <!-- <a href="#" class="sb-vk"><i class="bi-vkontakte"></i></a> -->
            <!-- <a href="#" class="sb-wechat"><i class="bi-wechat"></i></a> -->
            <!-- <a href="#" class="sb-wordpress"><i class="bi-wordpress"></i></a> -->
            <!-- <a href="#" class="sb-xing"><i class="bi-xing"></i></a> -->
            <!-- <a href="#" class="sb-yahoo"><i class="bi-yahoo"></i></a> -->
            <!-- <a href="#" class="sb-yelp"><i class="bi-yelp"></i></a> -->
            <!-- <a href="#" class="sb-youtube"><i class="bi-youtube"></i></a> -->
          </div>

          <!-- Scroll for More Button -->
          <a href="#features" class="scroll-more scroll" data-offset-top="80">
            <i class="icon"></i>
            <span>Scroll for more</span>
          </a>
        </div>

        <!-- Middle Column-->
        <div class="column c-middle">
          <h1 class="logo">
            <img src="/static/img/logo-big.png" alt="Streetr">
            Streetr
            <span> 🌎 Explorer 📌 Découvrir  🥇 Contribuer</span>
          </h1>
          <div class="phone">
            <img src="/static/img/intro/screen.png" alt="App Screen">
          </div>
        </div>

        <!-- Right Column-->
        <div class="column c-right">
          <!-- Navi -->
          <div class="navi">
            <div class="nav-toggle" data-offcanvas="open"><i class="flaticon-list26"></i></div>
          </div>
          <!-- Features -->
          <div class="intro-features">
            <div class="icon-block icon-block-horizontal light-color" data-transition-delay="100">
              <div class="icon"><i class="flaticon-globe14"></i></div>
              <div class="text">
                <h3>Explorer</h3>
                <p>
                  Streetr vous permet de découvir des oeuvres de street art, selon votre localisation.
                </p>
              </div>
            </div>
            <div class="icon-block icon-block-horizontal light-color" data-transition-delay="300">
              <div class="icon"><i class="flaticon-star51"></i></div>
              <div class="text">
                <h3>Découvrir</h3>
                <p>Voyez d'un autre oeil vos parcours habituels</p>
              </div>
            </div>
            <div class="icon-block icon-block-horizontal light-color" data-transition-delay="500">
              <div class="icon"><i class="flaticon-add63"></i></div>
              <div class="text">
                <h3>Contribuer</h3>
                <p> Ajoutez des oeuvres succeptibles d'attirer l'attention de la communauté Streetr</p>
              </div>
            </div>
          </div>
          <!-- Download Button -->
          <div class="download">
            <a href="https://goo.gl/forms/j9XFNLFeqnK4wqMp1" target="_blank" class="btn btn-default btn-app-store">
              <i class="bi-apple"></i>
              <div>
                <span>Télécharger sur</span>
                App Store
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section><!-- Intro Section End -->

</template>

<script>
  export default {
    name: 'Intro',
    data () {
      return {
      }
    }
  }
</script>
