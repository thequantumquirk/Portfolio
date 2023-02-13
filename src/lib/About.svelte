<script>
  import { scrollto } from "svelte-scrollto";
</script>

<main>
  <div
    id="about"
    class="lg:px-32 px-4 pt-44 w-screen flex flex-col justify-center items-center"
  >
    <div class="flex lg:gap-32 items-center gap-8 justify-between">
      <div
        class="border border-primary-dark opacity-50 h-0"
        style="width: 60vw"
      />
      <h1 class="text-primary-dark lg:text-4xl text-2xl font-bold">About</h1>
    </div>
    <div
      class="flex lg:flex-row flex-col items-center lg:px-16 justify-between mx-8 mt-8 gap-8 lg:gap-32 md:mx-32 lg:mt-16"
    >
      <div>
        <div class="lg:text-xl text-base">
          Hello, I'm Ravishanker @ Fosslover, I'm a Front-End Developer and
          UI/UX Designer skilled in Vue and React, with a passion for creating
          beautiful UI designs. I also have an interest in technologies like
          Rust.
        </div>
        <button
          use:scrollto={"#portfolio"}
          class="header lg:px-4 lg:py-2 px-3 py-1 my-4 bg-primary-dark rounded-lg lg:text-base text-sm font-bold"
          >Check out <br /> my Portfolio</button
        >
      </div>
      <img src="./laptop.svg" alt="laptop" width="250px" />
    </div>
  </div>
</main>
