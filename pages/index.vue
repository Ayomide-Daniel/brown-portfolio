<template>
  <div>
    <section class="cream-color d-flex home container section">
      <div class="meta-div">
        <h1 id="home" class="lg-text">
          Holla <span class="wave">👋</span>, <br />
          I’m
          <span class="brown-text text-decoration-underline"
            >Brown!
            <!-- <span class=" underline-div"></span> -->
          </span>
        </h1>
        <p>“As you dey here so, I don sight you”</p>
      </div>

      <div class="img-div">
        <img
          :src="require('~/assets/images/me-on-blue.png')"
          alt=""
          loading="lazy"
        />
      </div>
    </section>
    <section class="green-color motivation container">
      <div class="meta-div">
        <h1 class="bi bi-lightbulb icon"></h1>
        <h1 id="motivation">Words that inspire me</h1>
      </div>
      <div class="section">
        <div>
          <h2>
            "Think differently.<br />
            Innovate differently.<br />
            Provide solutions rather than discuss problems. <br />
            And while you do these things, remember that your Greatest Strength
            lies in doing things according to your unique abilities."
            <br /><br />
            These are the words I live and breathe by and I use Web Development
            as one of my tools to continually affirm these beliefs.
          </h2>
        </div>
      </div>
    </section>
    <section class="jobs container">
      <div class="meta-div">
        <h1 class="bi bi-briefcase icon"></h1>
        <h1 id="motivation">My works</h1>
      </div>
      <div class="section">
        <div class="content">
          <div class="img-div">
            <img :src="require('~/assets/images/fuoye360-logo.png')" alt="" />
          </div>
          <div class="content-meta">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nobis quo
            optio necessitatibus dolorem molestias harum hic id perspiciatis
            autem. Quidem, ad. Beatae delectus eos veritatis ipsa molestiae
            dolorum id tenetur?
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style scoped>
.home {
  display: block;
}
.home h1 {
  font-weight: 800;
}
.home .meta-div {
  display: block;
  margin-top: 10rem;
}
.home .img-div {
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
.home .wave {
  animation: waving ease-in-out infinite alternate 2s;
}
@keyframes waving {
  from {
    transform: scale(0.5);
    /* transform: rotate(15deg); */
  }
  to {
    transform: scale(2);
    /* transform: rotate(-15deg); */
  }
}
.home img {
  width: 100%;
  height: auto;
}
.motivation h2 {
  font-size: 1.3rem;
}
.jobs .content .img-div {
  display: flex;
}
.jobs .content img {
  object-fit: cover;
  width: 100%;
  height: 100px;
  border-radius: 1rem 1rem 0 0;
}
.jobs .content-meta {
  padding: 1rem;
  border-radius: 0 0 1rem 1rem;
}
</style>
