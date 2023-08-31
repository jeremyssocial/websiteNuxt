<template>
  <div id="index-content">
    <h1><GlitchText text="nr.bln" /></h1>
    <div class="cube-container">
      <div class="cube">
        <div class="face front">nr.bln</div>
        <div class="face back">near berlin</div>
        <div class="face right">fashion</div>
        <div class="face left">photography</div>
        <div class="face top">development</div>
        <div class="face bottom">social media</div>
      </div>
    </div>
  </div>
</template>

<style>
@import "~/assets/style/index/index.css";
</style>
<script>
export default {
  name: "IndexPage",
  head: {
    title: "nr.bln - Captivating Berlin Fashion & Street Photography",
    meta: [
      { charset: "utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
      {
        hid: "description",
        name: "description",
        itemprop: "description",
        content:
          "Dive into the dynamic world of Berlin fashion and street photography with Jeremy. Discover the city through his lens, as featured on the @nr.bln Instagram account.",
      },
      {
        hid: "og:title",
        name: "og:title",
        content: "nr.bln - Captivating Berlin Fashion & Street Photography",
      },
      { name: "og:type", content: "website" },
      { name: "og:url", content: "https://near-berlin.de/" },
      {
        name: "og:image",
        content:
          "https://preview.redd.it/lmhgzfx1bvkb1.jpg?width=1500&format=pjpg&auto=webp&s=884f7c0dc9f94c8ab31d86a2a16db0e1876ffb69",
      },
      {
        hid: "og:description",
        name: "og:description",
        content:
          "Dive into the dynamic world of Berlin fashion and street photography with Jeremy. Discover the city through his lens, as featured on the @nr.bln Instagram account.",
      },
      { name: "og:locale", content: "en_US" },
      {
        name: "og:site_name",
        content: "nr.bln - Captivating Berlin Fashion & Street Photography",
      },
      {
        name: "keywords",
        content:
          "Berlin, Fashion, Street Photography, Urban Style, Jeremy, Instagram, nr.bln, near berlin, Berlin Style",
      },
      { name: "robots", content: "index, follow" },
    ],
  },
};
</script>
