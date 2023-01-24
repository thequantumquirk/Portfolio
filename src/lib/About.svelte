<script>
    import { scrollto } from "svelte-scrollto";
</script> 
<main>
<div id="about" class="px-32 pt-44 w-screen flex flex-col justify-center items-center">
    <div class="flex gap-32 items-center justify-between">
        <div class="border border-primary-dark opacity-50 h-0" style="width: 60vw"></div>
        <div class="text-primary-dark text-4xl font-bold">About</div>
    </div>
    <div class="flex items-center justify-between gap-32 mx-32 mt-16">
        <div>
        <div class="text-xl">Hello, I am a Front-End Developer and UI/UX Designer skilled in Vue and React, with a passion for creating beautiful UI designs. I also have an interest in technologies like Rust.</div>
        <a use:scrollto={'#portfolio'}><button class="header px-4 py-2 my-4 bg-primary-dark rounded-lg font-bold">Check out my Portfolio</button></a>

    </div>
        <img src="./laptop.svg" alt="laptop" width="250px" />
    </div>
</div>
</main>