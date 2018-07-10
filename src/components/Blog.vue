<template>
  <section class="gallery padding-top-3x padding-bottom-3x" id="gallery">
    <div class="container">
      <div class="row">
        <div class="col-md-3 col-sm-4">
          <div class="block-heading text-right">
            <h2>Récent sur Streetr</h2>
            <span>Dernières contributions de la communauté Streetr</span>
          </div>
        </div>
        <div class="col-lg-8 col-lg-offset-1 col-md-9 col-sm-8">
          <div class="tab-content">
            <div class="tab-pane fade in active" id="screens">
              <div class="scroller app-gallery">
                <div class="item">
                  <a href="/static/img/gallery/01.jpg">
                    <img src="/static/img/gallery/01.jpg" alt="Thumbnail">
                  </a>
                </div>
                <div class="item">
                  <a href="/static/img/gallery/02.jpg">
                    <img src="/static/img/gallery/02.jpg" alt="Thumbnail">
                  </a>
                </div>
                <div class="item">
                  <a href="/static/img/gallery/03.jpg">
                    <img src="/static/img/gallery/04.jpg" alt="Thumbnail">
                  </a>
                </div>
                <div class="item">
                  <a href="/static/img/gallery/05.jpg">
                    <img src="/static/img/gallery/05.jpg" alt="Thumbnail">
                  </a>
                </div>
                <div class="item">
                  <a href="/static/img/gallery/06.jpg">
                    <img src="/static/img/gallery/06.jpg" alt="Thumbnail">
                  </a>
                </div>
              </div>
            </div>
            <div class="tab-pane fade" id="video-prev">
              <div class="embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="//player.vimeo.com/video/113575647?title=0&amp;byline=0&amp;portrait=0&amp;color=007aff" width="500" height="281" allowfullscreen></iframe>
              </div>
            </div>
            <div class="tab-pane fade" id="proto">
              <img src="img/gallery/prototype.png" alt="Prototype">
            </div>
          </div>
        </div>
      </div>
    </div>
  </section><!-- App Gallery End -->

</template>

<script>

  export default {
    name: 'Blog',
  }
</script>
