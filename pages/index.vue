<template>
  <div>
    <section class="cream-color d-flex section-1 container">
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
        <img :src="require('~/assets/images/me-on-blue.png')" alt="" />
      </div>
    </section>
    <section class="green-color d-flex section-2 container">
      <div>
        <h1>
          "Think differently. <br />
          Innovate differently. <br />
          Provide solutions rather than discuss problems. <br />
          And while you do these things, remember that your Greatest Strength
          lies in doing things according to your unique abilities." <br />
          These are the words I live and breathe by and I use Web Development as
          one of my tools to continually affirm these beliefs.
        </h1>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style scoped></style>
