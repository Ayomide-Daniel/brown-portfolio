<template>
  <div>
    <section class="cream-color d-flex section-1 container section">
      <div class="meta-div">
        <h1 class="lg-text">
          Holla 👋, <br />
          I’m
          <span class="brown-text text-decoration-underline"
            >Brown!
            <!-- <span class=" underline-div"></span> -->
          </span>
        </h1>
        <p><small>“As you dey here so, I don sight you”</small></p>
      </div>
      <div class="img-div">
        <img
          :src="require('~/assets/images/me-on-blue.png')"
          alt=""
          loading="lazy"
        />
      </div>
    </section>
    <section class="green-color section-2 container">
      <div class="meta-div">
        <h1 class="bi bi-lightbulb icon"></h1>
        <h1>Words that inspire me</h1>
      </div>
      <div class="section">
        <div>
          <h2>
            "Think differently.<br />
            Innovate differently.<br />
            Provide solutions rather than discuss problems. <br />
            And while you do these things, remember that your Greatest Strength
            lies in doing things according to your unique abilities."
            <br />
            These are the words I live and breathe by and I use Web Development
            as one of my tools to continually affirm these beliefs.
          </h2>
        </div>
      </div>
    </section>
    <section class="section-3 container d-flex"></section>
  </div>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style scoped>
.section-1 {
  display: block;
}
.section-1 h1 {
  font-weight: 800;
}
.section-1 .meta-div {
  display: block;
  margin-top: -15rem;
}
.section-1 .img-div {
  position: absolute;
  display: flex;
  width: 100vw;
  bottom: 0;
  right: -50px;
  transform: scaleX(-1);
  -webkit-transform: scaleX(-1);
  -moz-transform: scaleX(-1);
  -ms-transform: scaleX(-1);
  -o-transform: scaleX(-1);
}

.section-1 img {
  width: 100%;
  height: auto;
}
.section-2 h2 {
  font-size: 1.3rem;
}
</style>
