<script lang="ts">
  let width = window.innerWidth;
  window.addEventListener("resize", () => {
    width = window.innerWidth;
  });
  let projects = [
    {
      name: "SnapStash",
      description:
        "SnapStash is a powerful Chrome extension that allows you to capture, store, and transform web content with ease. Whether it's capturing text snippets, saving web conent, or generating creative outputs, SnapStash empowers you to enhance your web browsing experience and fuel your inspiration.",
      techStacks: ["React", "Chrome Extenison", "Figma"],
      image: "./snapstash.svg",
      domain: "FrontEnd Development",
      buttons: [
        {
          name: "Project",
          link: "https://github.com/fosslover69/snapstash",
        },
        {
          name: "Demo",
          link: "https://user-images.githubusercontent.com/67329471/239474112-148064a2-22f2-4227-93c6-843eb4a07f89.mp4",
        },
      ],
    },
    {
      name: "Habitat Hive",
      description:
        "Habitat Hive is a project that's aimed to solve rental finding problems. Habitat Hive uses a Habitability Index which ranks properties based on the living well-being around the property.",
      techStacks: ["Sveltekit", "Flask", "Python", "Figma"],
      image: "./habitat.svg",
      domain: "Full Stack Development / Machine Learning",
      buttons: [
        {
          name: "Project",
          link: "https://github.com/fosslover69/habitat-hive",
        },
        {
          name: "Demo",
          link: "https://user-images.githubusercontent.com/67329471/230719124-d3511eff-04b1-4487-b2a8-f2587efb2a8a.mp4",
        },
        {
          name: "Site",
          link: "https://hive.fosslover.dev/",
        },
      ],
    },
    {
      name: "CORVUS-AOSP",
      description:
        "CorvusOS is a highly modified version of the Android Open Source Project, built on top of Android 10 and 11, and packed with customizations and features that are carefully selected to enhance the user experience. As an open source, non-profit project, it is created as a hobby by Android enthusiasts, including myself",
      techStacks: ["Sveltekit", "Figma", "Netlify"],
      image: "./corvus.svg",
      domain: "Web Development and UI/UX design",
      buttons: [
        {
          name: "Project",
          link: "https://github.com/Corvus-Aosp",
        },
        {
          name: "Site",
          link: "https://fosslover.corvus.dev/",
        },
      ],
    },
    {
      name: "SemScape",
      description:
        "The main goal of SemScape is to reduce the friction experienced by students while learning and preparing for semester exams. The name 'Sem-Scape' reflects this goal - to provide an escape from the pain of semesters. Many institutions have their own syllabi and patterns for their semesters, making it difficult for students to find relevant materials online. SemScape aims to solve this problem by providing a personalized and centralized place for institutions to manage study materials.",
      domain: "WIP",
      techStacks: ["Supabase", "Svelte", "Figma"],
      image: "./semscape.svg",
      buttons: [
        {
          name: "Blog",
          link: "https://blog.fosslover.dev/show/19752/a-cms-to-solve-the-stress-of-students",
        },
      ],
    },
    {
      name: "Fun Stuffs",
      description:
        "I love to create fun stuffs in my free time. I have created a few projects that are currently live and are being used by people around the world. I have also created a few projects that are still in development.",
      domain: "FrontEnd Development",
      techStacks: ["React", "JS", "Figma"],
      image: "./fun.svg",
      buttons: [
        {
          name: "Snake Game",
          link: "https://snake.fosslover.dev/",
        },
        {
          name: "Pig Translator",
          link: "https://pig.fosslover.dev/",
        },
      ],
    },
  ];
</script>

<main>
  <div id="portfolio" class="xl:px-32 w-screen pt-32">
    <div class="flex lg:gap-28 gap-3 items-center justify-center">
      <div
        class="border border-primary-dark opacity-50 h-0"
        style="width: 60vw"
      />
      <h1 class="text-primary-dark lg:text-4xl text-2xl font-bold">
        Portfolio
      </h1>
    </div>
    <div class="lg:px-16">
      {#each projects as project, index}
        <div
          class="flex lg:flex-row flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16 {index %
            2 ==
          0
            ? 'bg-card-black lg:p-8 py-8 rounded-xl'
            : ''} "
        >
          {#if width < 1024 || index % 2 != 0}
            <div class="w-52 h-52 rounded-lg" style="background-color: #fff;">
              <img
                src={project.image}
                alt={project.name}
                class="w-full h-full p-8"
              />
            </div>
          {/if}
          <div
            class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3"
          >
            <div
              class="flex flex-col lg:flex-row justify-center items-center w-full lg:justify-between"
            >
              <div class="flex items-end gap-1">
                <div class="lg:text-4xl text-2xl font-bold">{project.name}</div>
                <div>({project.domain})</div>
              </div>
              <div class="flex lg:gap-2 gap-1">
                {#each project.buttons as button}
                  <a
                    href={button.link}
                    target="_blank"
                    rel="noopener noreferrer"
                    ><button
                      class="p-2 rounded-lg bg-primary-dark font-bold text-sm text-white"
                    >
                      {button.name}
                    </button>
                  </a>
                {/each}
              </div>
            </div>
            <div>
              {project.description}
            </div>
            <div class="flex md:gap-2 gap-1 items-center">
              <div class="md:text-base text-sm">Tech Stacks Used:</div>
              {#each project.techStacks as techStack}
                <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
                  {techStack}
                </div>
              {/each}
            </div>
          </div>
          {#if width > 1024 && index % 2 == 0}
            <div class="w-52 h-52 rounded-lg" style="background-color: #fff;">
              <img
                src={project.image}
                alt={project.name}
                class="w-full h-full p-8"
              />
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</main>
