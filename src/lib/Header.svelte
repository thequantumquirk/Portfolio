<script>
    import { scrollto } from "svelte-scrollto";
</script> 
<main>
    <div class="flex w-screen fixed top-0 left-0 justify-between px-24 py-8 items-center" style="backdrop-filter: blur(10px)">
        <div use:scrollto={'top'} class="font-bold text-primary-dark text-4xl">Ravishanker</div>
        <div class="flex justify-evenly font-semibold items-center gap-16">
            <a use:scrollto={'#about'} class="header">About</a>
            <a use:scrollto={'#portfolio'} class="header">Portfolio</a>
            <a use:scrollto={'#'} class="header">Blog</a>
            <a use:scrollto={'#resume'} class="header">Resume</a>
            <button use:scrollto={'#contact'} class="header px-4 py-2 bg-primary-dark rounded-lg">Contact</button>
        </div>
    </div>
</main>