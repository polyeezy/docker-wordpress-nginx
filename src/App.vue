<template>
  <div id="app">
    <div id="preloader">
      <div class="logo">
        <img src="/static/img/logo-middle.png" alt="Streetr">
        <span>Streetr</span>
      </div>
    </div>

    <!-- Fake scrollbar (when open popups/modals) -->
    <div class="fake-scrollbar"></div>

    <!-- Off-canvas Navigation -->
    <Header></Header>

    <!--Modal (Signin/Signup Page)-->
    <div class="modal fade" id="signin-page">
      <div class="modal-dialog">
        <div class="container">
          <div class="modal-form">
            <div class="tab-content">
              <!-- Sign in form -->
              <form class="tab-pane transition scale fade in active" id="signin-form" autocomplete="off">
                <div class="form-group space-top-2x">
                  <label for="si_email" class="sr-only">Email</label>
                  <input type="email" class="form-control" name="si_email" id="si_email" placeholder="Email" readonly onfocus="$(this).removeAttr('readonly');" required>
                  <span class="error-label"></span>
                  <span class="valid-label"></span>
                </div>
                <div class="form-group">
                  <label for="si-password" class="sr-only">Password</label>
                  <input type="password" class="form-control" name="si-password" id="si-password" placeholder="Password" readonly onfocus="$(this).removeAttr('readonly');" required>
                  <a class="helper-link" href="#">Forgot password?</a>
                  <span class="error-label"></span>
                  <span class="valid-label"></span>
                </div>
                <label class="checkbox">
                  <input type="checkbox"> Remember me
                </label>
                <div class="space-top-2x clearfix">
                  <button type="button" class="btn-round btn-ghost btn-danger pull-left" data-dismiss="modal"><i class="flaticon-cross37"></i></button>
                  <button type="submit" class="btn-round btn-ghost btn-success pull-right"><i class="flaticon-correct7"></i></button>
                </div>
                <!-- Switching forms (Fake nav tab) -->
                <div class="form-switch helper-text space-top-2x">Don`t have an account? <a href="#form-1">Sign up for Streetr</a></div>
              </form>
              <!-- Sign up form -->
              <form class="tab-pane transition scale fade" id="signup-form">
                <h3 class="modal-title">Sign Up</h3>
                <div class="form-group space-top-2x">
                  <label for="su-email" class="sr-only">Email</label>
                  <input type="email" class="form-control" name="su-email" id="su-email" placeholder="Email" required>
                  <span class="error-label"></span>
                  <span class="valid-label"></span>
                </div>
                <div class="form-group">
                  <label for="su-password" class="sr-only">Password</label>
                  <input type="password" class="form-control" name="su-password" id="su-password" placeholder="Password" required>
                  <span class="error-label"></span>
                  <span class="valid-label"></span>
                </div>
                <div class="form-group">
                  <label for="su-password-repeat" class="sr-only">Repeat password</label>
                  <input type="password" class="form-control" name="su-password-repeat" id="su-password-repeat" placeholder="Repeat password" required>
                  <span class="error-label"></span>
                  <span class="valid-label"></span>
                </div>
                <label class="checkbox">
                  <input type="checkbox"> Subscribe for our news
                </label>
                <div class="space-top-2x clearfix">
                  <button type="button" class="btn-round btn-ghost btn-danger pull-left" data-dismiss="modal"><i class="flaticon-cross37"></i></button>
                  <button type="submit" class="btn-round btn-ghost btn-success pull-right"><i class="flaticon-correct7"></i></button>
                </div>
                <!-- Switching forms (Fake nav tab) -->
                <div class="form-switch helper-text space-top-2x">Already have an account? <a href="#form-2">Sign in</a></div>
              </form>
            </div>
            <!-- Hidden real nav tabs -->
            <ul class="nav-tabs hidden">
              <li id="form-1"><a href="#signup-form" data-toggle="tab">Sign up</a></li>
              <li id="form-2"><a href="#signin-form" data-toggle="tab">Sign in</a></li>
            </ul>
          </div>
        </div>
      </div><!-- /.modal-dialog -->
    </div><!-- /.modal -->

    <Intro/>
    <div class="content-wrap">
      <HeaderSticky/>
      <Blog></Blog>
      <Features></Features>
    </div>
    <Footer></Footer>
    <router-view/>
  </div>
</template>

<script>

  import Header from './components/Header'
  import HeaderSticky from './components/HeaderSticky'
  import Features from './components/Features'
  import FeaturesDescription from './components/FeaturesDescription'
  import Intro from './components/Intro'
  import Blog from './components/Blog'
  import Footer from './components/Footer'

  export default {
  name: 'App',
    components: { Header,HeaderSticky, Intro,Blog, Features, FeaturesDescription, Footer},
}
</script>

<style>

</style>
