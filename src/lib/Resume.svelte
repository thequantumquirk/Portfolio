<script lang="ts">
  let width = window.innerWidth;
  let skills = [
    "vue",
    "vuetify",
    "nuxt",
    "react",
    "html",
    "css",
    "tailwind",
    "js",
    "ts",
    "git",
    "figma",
    "linux",
  ];
</script>

<div id="resume" class="lg:px-32 px-4 w-screen pt-32">
  <div class="flex lg:gap-32 gap-8 items-center justify-center">
    <div
      class="border border-primary-dark opacity-50 h-0"
      style="width: 60vw"
    />
    <h1 class="text-primary-dark lg:text-4xl text-2xl font-bold">Resume</h1>
  </div>
  <div class="lg:mx-32 mt-12 mx-8">
    <h2 class="lg:text-3xl text-xl text-primary-dark font-bold">
      Professional Experience
    </h2>
    <div class="flex mt-6 gap-4">
      <div class="flex mt-3 flex-col items-center">
        <div
          class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"
        />
        <div class="lg:h-64 h-full w-0 border-l-2 border-primary-dark" />
      </div>
      <div class="flex flex-col gap-2 pb-8">
        <div class="lg:flex gap-2 items-end">
          <div class="lg:text-3xl text-2xl font-bold">FOSSFREAKS</div>
          <div class="text-sm">(May 2022 - Present)</div>
        </div>
        <div class="lg:text-2xl text-xl text-primary-dark font-bold">
          Front-End Developer
        </div>
        <ul class="lg:text-base text-sm">
          <li>
            Actively participated in the front-end development of the projects
            as a member of the team
          </li>
          <li>
            Worked with UI/UX designers to translate design concepts into
            high-quality, pixel-perfect code for user interfaces
          </li>
          <li>
            Maintained effective communication with team members to ensure
            smooth and efficient project progress
          </li>
          <li>
            Demonstrated proficiency in a range of technologies, including
            Vue.js, React.js, Typescript, and JavaScript
          </li>
          <li>
            Utilized version control systems like Git to manage and track code
            changes
          </li>
          <li>
            Leveraged Linux as the primary development environment to create and
            test code
          </li>
        </ul>
      </div>
    </div>
    <div class="flex gap-4 items-top">
      <div class="flex flex-col items-center">
        <div
          class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"
        />
        <div class="lg:h-64 h-full w-0 border-l-2 border-primary-dark" />
      </div>
      <div class="flex flex-col gap-2">
        <div class="lg:flex gap-1 items-end">
          <div class="lg:text-3xl text-2xl font-bold">CORVUS-AOSP</div>
          <div class="text-sm">(Nov 2020 - Present)</div>
        </div>
        <div class="lg:text-2xl text-xl text-primary-dark font-bold">
          AOSP Developer
        </div>
        <ul class="lg:text-base text-sm">
          <li>
            Created and implemented user interfaces and user experiences, as
            well as development, for the website to enhance user engagement and
            functionality
          </li>
          <li>Served as a device developer for the Redmi Note 7 Pro</li>
          <li>
            Demonstrated extensive knowledge and usage of version control
            systems, specifically Git
          </li>
          <li>
            Proficient in utilizing various cloud service providers, such as
            GCP, AWS, and Azure, to build firmware
          </li>
          <li>To know more, Checkout Corvus-AOSP</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="lg:mx-32 lg:mt-16 mt-12 mx-8">
    <h2 class="lg:text-3xl text-2xl text-primary-dark font-bold">
      Education
    </h2>
    <div class="flex mt-6 gap-4">
      <div class="flex flex-col mt-3 items-center">
        <div
          class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"
        />
        <div class="h-full w-0 border-l-2 border-primary-dark" />
      </div>
      <div class="flex flex-col gap-2">
        <div class="lg:flex gap-1 items-end">
          <div class="lg:text-3xl text-2xl font-bold">Bishop Heber College</div>
          <div class="sm:text-sm text-xs">(pursuing)</div>
        </div>
        <div class="lg:text-2xl text-xl text-primary-dark font-bold">
          Bachelor's in Computer Science
        </div>
        <ul class="lg:text-base text-sm">
          <li>Successfully coordinated the Debian Day '22 event</li>
          <li>
            Achieved third place in the DataHack '22 competition, organized by
            devfolio
          </li>
          <li>
            Led the organization and execution of the Hybernitix Symposium
          </li>
          <li>
            Led the Heber Quiz Club and oversaw the planning and execution of
            quiz events
          </li>
        </ul>
      </div>
    </div>
  </div>
  <div class="lg:mx-32 mt-16 mx-8">
    <h2 class="text-3xl text-primary-dark font-bold">Skills</h2>
    <div class="flex mt-8 lg:gap-8 gap-4 flex-wrap">
      {#each skills as logo}
        {#if width>768}
        <img style="height: 75px" src="./skills/{logo}.svg" alt="skill" />
        {:else}
        <img style="height: 50px" src="./skills/{logo}.svg" alt="skill" />
        {/if}
      {/each}
    </div>
  </div>
</div>
