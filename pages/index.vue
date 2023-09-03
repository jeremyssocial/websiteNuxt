<template>
  <div id="index-content">
    <Cube3d
      front="nr.bln"
      back="near berlin"
      right="fashion"
      left="photography"
      top="developement"
      bottom="social media"
    />

    <div class="max-w-3xl mx-auto px-4">
      <h1 class="text-3xl font-bold mb-4">
        Willkommen, in der Welt von <GlitchText text="nr.bln" />
      </h1>

      <p class="text-lg mb-4">
        Als in Berlin ansässiges Talent bin ich,
        <a
          href="https://www.instagram.com/nr.bln/"
          class="text-blue-500 hover:underline"
          >@nr.bln</a
        >, bekannt für meine einzigartige Perspektive in der Welt der
        Modefotografie. Meine Reise begann als Google Local Guide, und heute
        setze ich meine Leidenschaft für Technologie und Kreativität ein, um
        Wellen in der Modeindustrie zu schlagen.
      </p>

      <h2 class="text-2xl font-semibold mb-2">Meine Geschichte</h2>

      <p class="text-lg mb-4">
        Mein Interesse an Technologie führte mich zu einer Ausbildung als
        Softwareentwickler, wo ich mich in Programmiersprachen wie C++, Python,
        JavaScript, PHP, HTML und CSS vertiefte. Neben der Technologie habe ich
        eine Leidenschaft für Fotografie. Mehr zu meiner Geschichte findet ihr
        auf meinem
        <a
          href="https://www.reddit.com/user/_-J-G-_/comments/14vyt3i/a_bit_about_me_nrbln/"
          class="text-blue-500 hover:underline"
          >Reddit Post</a
        >.
      </p>

      <h2 class="text-2xl font-semibold mb-2">Häufig gestellte Fragen</h2>

      <p class="text-lg mb-4">
        <strong>Q: Wie bin ich zur Modefotografie gekommen?</strong><br />A:
        Meine Reise zur Modefotografie begann mit meiner Arbeit als Google Local
        Guide. Dort habe ich gelernt, ansprechende Bilder zu machen, die
        Aufmerksamkeit erregen. Dieses Talent habe ich auf die Modefotografie
        übertragen, als ich angefangen habe ein größeres Interesse für Fashion
        und Self-care zu entwickeln.
      </p>

      <p class="text-lg mb-4">
        <strong>Q: Was mache ich neben der Fotografie?</strong><br />A: Neben
        der Fotografie bin ich auch ein Technik-Enthusiast. Ich habe einen
        Hintergrund in der Softwareentwicklung und habe Erfahrung im Umgang mit
        einer Vielzahl von Programmiersprachen. Außerdem interessiere ich mich
        für KI-Technologien und bin ein geschlossener Betatester für zahlreiche
        AI-Tools.
      </p>

      <h2 class="text-2xl font-semibold mb-2">Ressourcen</h2>

      <p class="text-lg mb-4">
        Für mehr Informationen, schaue dir meine
        <a
          href="https://www.instagram.com/nr.bln/"
          class="text-blue-500 hover:underline"
          >Instagram-Seite</a
        >
        an. Du kannst auch meine
        <a
          href="https://www.reddit.com/user/_-J-G-_/comments/14vyt3i/a_bit_about_me_nrbln/"
          class="text-blue-500 hover:underline"
          >Reddit-Beiträge</a
        >
        lesen, um mehr über meine Reise zu erfahren.
      </p>

      <h2 class="text-2xl font-semibold mb-2">Featured Podcast Episode</h2>

      <p class="text-lg mb-4">
        In einer besonderen Episode des
        <a
          href="https://www.imdb.com/title/tt23668898/?ref_=tt_ov_inf"
          class="text-blue-500 hover:underline"
          >"Yaya Diamonds Dream Chasers Radio"</a
        >, wurde ich, @nr.bln, hervorgehoben. Yaya Diamond, die Gastgeberin,
        beleuchtete meine Arbeit als modebewusster Straßenfotograf in Berlin.
        <a
          href="https://www.imdb.com/title/tt28593625/"
          class="text-blue-500 hover:underline"
          >Schau dir die Episode an</a
        >
        und erfahre mehr über meine künstlerische Herangehensweise und meine
        unkonventionelle Art der Selbstausdruck.
      </p>

      <p class="text-lg mb-4">
        In der Diskussion wurde auch
        <a
          href="https://www.instagram.com/p/CsyJXbCMsYL/?img_index=1"
          class="text-blue-500 hover:underline"
          >ein Bild</a
        >
        hervorgehoben, das mich beim Spaziergang im Regen zeigt, was die
        einzigartige Charme und Atmosphäre von Berlin einfängt. Es ist diese
        Leidenschaft für das Einfangen von Momenten und das Erzählen von
        Geschichten durch meine Bilder, die meine Arbeit auszeichnet.
      </p>

      <h2 class="text-2xl font-semibold mb-2">Begleite mich</h2>

      <p class="text-lg mb-4">
        Ich freue mich darauf, dich auf meiner Reise durch Mode, Fotografie und
        Technologie mitzunehmen. Zusammen können wir die Grenzen des Möglichen
        erweitern und die Welt der Mode revolutionieren. Mach mit!
      </p>
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
