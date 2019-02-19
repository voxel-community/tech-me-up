<template>
  <div>
    <!-- NAVBAR CON TRE PULSANTI -->
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item">
          <h1 class="title">Girlscodeit</h1>
        </a>
        <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item">Home</a>
          <a class="navbar-item" href="/#blog">Blog</a>
          <nuxt-link to="contatti" class="navbar-item">Contatti</nuxt-link>
        </div>
      </div>
    </nav>

    <!-- SEZIONE HERO COLORATA  -->
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Ciao!</h1>
          <h2 class="subtitle">Questo è un blog</h2>
        </div>
      </div>
    </section>


    <!-- SEZIONE TITOLO: BLOG -->
    <section class="section" id="blog">
      <div class="container">
        <h1 class="title">Blog</h1>
      </div>
    </section>

    <!-- 2 COLONNE CON 2 CARD DEI POST -->
    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column">
            <nuxt-link to="posts/arduino">

              <!-- CARD CON COLLEGAMENTO AL PRIMO POST -->
              <div class="card">
                <div class="card-image">
                  <figure class="image is-4by3">
                    <img
                      src="https://images.unsplash.com/photo-1548065822-2cd6b99550f8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60"
                      alt="Placeholder image">
                  </figure>
                </div>
                <div class="card-content">
                  <div class="content">
                    <h1>Arduino</h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Phasellus nec iaculis mauris.
                    <a>@girlscodeit</a>.
                    <a href="#">#css</a>
                    <a href="#">#responsive</a>
                    <br>
                    <time datetime="2016-1-1">11:09 PM - 1 Jan 2019</time>
                  </div>
                </div>
              </div>
            </nuxt-link>
          </div>
          <div class="column">
            <nuxt-link to="posts/stem">

             <!-- CARD CON COLLEGAMENTO AL SECONDO POST -->
              <div class="card">
                <div class="card-image">
                  <figure class="image is-4by3">
                    <img
                      src="https://images.unsplash.com/photo-1548125544-2d4cad80de29?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1502&q=80"
                      alt="Placeholder image">
                  </figure>
                </div>
                <div class="card-content">
                  <div class="content">
                    <h1>STEM</h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Phasellus nec iaculis mauris.
                    <a>@girlscodeit</a>.
                    <a href="#">#css</a>
                    <a href="#">#responsive</a>
                    <br>
                    <time datetime="2016-1-1">11:09 PM - 1 Jan 2019</time>
                  </div>
                </div>
              </div>
            </nuxt-link>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

