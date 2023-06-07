<script lang="ts">
  import About from "./lib/About.svelte";
  import Contact from "./lib/Contact.svelte";
  import Header from "./lib/Header.svelte";
  import Portfolio from "./lib/Portfolio.svelte";
  import Resume from "./lib/Resume.svelte";
</script>

<main>
  <link rel="stylesheet" href="./smui.css" />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"
    integrity="sha512-+4zCK9k+qNFUR5X+cKL9EIR+ZOhtIloNl9GIKS57V1MyNsYpYcUrUeQc9vNfzsWfV28IaLL3i96P9sdNyeRssA=="
    crossorigin="anonymous"
  />
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/js/all.min.js"
    integrity="sha512-F5QTlBqZlvuBEs9LQPqc1iZv2UMxcVXezbHzomzS6Df4MZMClge/8+gXrKw2fl5ysdk4rWjR0vKS7NNkfymaBQ=="
    crossorigin="anonymous"
  ></script>
  <div class="absolute z-10">
    <Header />
  </div>
  <About />
  <Portfolio />
  <Resume />
  <Contact />
</main>
