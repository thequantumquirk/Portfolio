<script lang="ts">
  import About from "./lib/About.svelte";
  import Contact from "./lib/Contact.svelte";
  import Header from "./lib/Header.svelte";
  import Portfolio from "./lib/Portfolio.svelte";
  import Resume from "./lib/Resume.svelte";
</script>

<main>
  <link rel="stylesheet" href="./smui.css" />
  <link href="./../node_modules/@fortawesome/fontawesome-free/css/all.min.css" rel="stylesheet">
  <div class="fixed">
    <Header />
  </div>
  <About />
  <Portfolio />
  <Resume />
  <Contact />
</main>