<script>
  import { scrollto } from "svelte-scrollto";
</script>

<main>
  <div
    class="flex lg:flex-row flex-col gap-2 w-[98%] fixed top-4 mx-4 left-0 justify-between bg-card-black bg-opacity-40 lg:px-24 py-4 items-center rounded-full backdrop-blur-xl"
  >
    <div
      use:scrollto={"top"}
      class="font-bold text-primary-dark text-3xl cursor-pointer"
    >
      Ravishanker
    </div>
    <div class="flex justify-evenly font-semibold items-center gap-2 lg:gap-16">
      <div use:scrollto={"#about"} class="header">About</div>
      <div use:scrollto={"#portfolio"} class="header">Portfolio</div>
      <a
        href="https://blog.fosslover.dev/shows"
        target="_blank"
        rel="noreferrer"
        class="header">Blog</a
      >
      <div use:scrollto={"#resume"} class="header">Resume</div>
      <button
        use:scrollto={"#contact"}
        class="lg:px-4 lg:py-1 px-2 py-1 bg-primary-dark rounded-lg text-sm lg:text-lg"
        >Contact</button
      >
    </div>
  </div>
</main>

<style>
  .header {
    color: var(--text);
    cursor: pointer;
    padding: 0.25rem 0.25rem;
    border-radius: 0.5rem;
  }
  .header:hover {
    color: var(--primary);
    cursor: pointer;
    background-color: #7e7efc41;
    padding: 0.25rem 0.25rem;
  }
</style>
