<template>
  <div class="about">
    <p class="about__text">
      Hi, my name is
      <a class="about__link" href="#">Alex</a>
    </p>
    <p class="about__text">
      I’m a front-end
      <a class="about__link" href="#">engineer</a>,
    </p>
    <p class="about__text">
      passionate for the
      <a class="about__link" href="#">web</a>,
    </p>
    <p class="about__text">
      &amp;
      <a class="about__link" href="#">solution archicture</a>
    </p>
    <p class="about__text">
      <prismic-link :field="$store.state.menu.menu_links[1].link">
        {{ $store.state.menu.menu_links[1].link.uid }}
      </prismic-link>
    </p>
  </div>
</template>

<script>
export default {
  name: "about-text",
  mounted() {
    // console.log(`AboutText.vue - 43 - 🔥`, this.$store.state.menu.menu_links);
  },
};
</script>

<style></style>
