<script lang="ts">
  let width = window.innerWidth;
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
      <div
        class="flex lg:flex-row flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16"
      >
        <div class="w-52 h-52 rounded-lg" style="background-color: #fff">
          <img
            src="./bakeaholicks.svg"
            alt="bakeaholics"
            class="w-full h-full p-4"
          />
        </div>
        <div
          class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3"
        >
          <div
            class="flex flex-col lg:flex-row justify-center items-center w-full lg:justify-between"
          >
            <div class="flex items-end gap-1">
              <div class="lg:text-4xl text-2xl font-bold">BAKEAHOLICS</div>
              <div>(Front-End)</div>
            </div>
          </div>
          <div>
            Bakeaholicks is a professionally designed website for a bakery that
            specializes in the art of bread baking. Utilizing the Vue.js and
            Vuetify frameworks, this site was crafted to provide an exceptional
            user experience for patrons seeking information about the bakery's
            offerings and services.
          </div>
          <div class="flex md:gap-2 gap-1 items-center">
            <div class="md:text-base text-sm">Tech Stacks Used:</div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Vue.js
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Vuetify
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Vuex
            </div>
          </div>
        </div>
      </div>
      <div
        class="flex lg:flex-row bg-card-black lg:p-8 py-8 flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16"
      >
        {#if width < 1024}
          <div class="w-52 h-52 rounded-lg" style="background-color: #fff;">
            <img src="./corvus.svg" alt="corvus" class="w-full h-full p-8" />
          </div>
        {/if}
        <div class="flex w-3/4 flex-col justify-center lg:gap-6 gap-3">
          <div
            class="flex lg:flex-row flex-col gap-1 justify-between w-100 items-center"
          >
            <div
              class="flex 2xl:flex-row flex-col lg:items-end items-center gap-1"
            >
              <div class="lg:text-4xl text-2xl font-bold">CORVUS-AOSP</div>
              <div>(Web Development and UI/UX design)</div>
            </div>
            <div>
              <a
                href="https://github.com/Corvus-Aosp"
                target="_blank"
                rel="noreferrer"
              >
                <button
                  class="bg-primary-dark font-bold px-4 py-1 rounded-lg mt-2"
                  >Project</button
                >
              </a>
            </div>
          </div>
          <div class="w-11/12">
            CorvusOS is a highly modified version of the Android Open Source
            Project, built on top of Android 10 and 11, and packed with
            customizations and features that are carefully selected to enhance
            the user experience. As an open source, non-profit project, it is
            created as a hobby by Android enthusiasts, including myself
          </div>
          <div class="flex md:gap-2 gap-1 items-center">
            <div class="md:text-base text-sm">Tech Stacks Used:</div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Nuxt.js
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Vuetify
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Figma
            </div>
          </div>
        </div>
        {#if width > 1024}
          <div
            class="w-52 h-52 rounded-lg bg-dark-white"
            style="background-color: #fff"
          >
            <img src="./corvus.svg" alt="corvus" class="w-full h-full p-8" />
          </div>
        {/if}
      </div>
      <div
        class="flex lg:flex-row flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16"
      >
        <div class="w-52 h-52 rounded-lg" style="background-color: #fff;">
          <img src="./semscape.svg" alt="semscape" class="w-full h-full p-8" />
        </div>
        <div
          class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3"
        >
          <div
            class="flex flex-col lg:flex-row justify-center items-center w-full lg:justify-between"
          >
            <div class="flex items-end gap-1">
              <div class="lg:text-4xl text-2xl font-bold">SemScape</div>
              <div>(WIP)</div>
            </div>
            <div>
              <a
                href="https://blog.fosslover.dev/show/19752/a-cms-to-solve-the-stress-of-students"
                target="_blank"
                rel="noreferrer"
              >
                <button
                  class="bg-primary-dark font-bold px-4 py-1 rounded-lg mt-2"
                  >Blog</button
                >
              </a>
            </div>
          </div>
          <div>
            The main goal of SemScape is to reduce the friction experienced by
            students while learning and preparing for semester exams. The name
            "Sem-Scape" reflects this goal - to provide an escape from the pain
            of semesters. Many institutions have their own syllabi and patterns
            for their semesters, making it difficult for students to find
            relevant materials online. SemScape aims to solve this problem by
            providing a personalized and centralized place for institutions to
            manage study materials.
          </div>
          <div class="flex md:gap-2 gap-1 items-center">
            <div class="md:text-base text-sm">Tech Stacks Used:</div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Svelte
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Supabase
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Figma
            </div>
          </div>
        </div>
      </div>
      <div
        class="flex lg:flex-row bg-card-black lg:p-8 py-8 lg:rounded-lg flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16"
      >
        {#if width < 1024}
          <div class="w-52 h-52 rounded-lg" style="background-color: #fff;">
            <img src="./fun.svg" alt="fun" class="w-full h-full" />
          </div>
        {/if}
        <div
          class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3"
        >
          <div
            class="flex flex-col lg:flex-row justify-center items-center w-full lg:justify-between"
          >
            <div
              class="flex lg:flex-row flex-col lg:items-end items-center gap-1"
            >
              <div class="lg:text-4xl text-2xl font-bold">Fun Stuffs</div>
              <div>(Side Hustles)</div>
            </div>
            <div class="mt-2">
              <a
                href="https://pig.fosslover.dev"
                target="_blank"
                rel="noreferrer"
              >
                <button
                  class="px-1 py-1 mr-1 bg-primary-dark rounded-lg text-sm font-bold"
                  >Pig Translator</button
                ></a
              >
              <a
                href="https://snake.fosslover.dev"
                target="_blank"
                rel="noreferrer"
              >
                <button
                  class="px-1 py-1 mr-1 bg-primary-dark rounded-lg text-sm font-bold"
                  >Snake Game</button
                >
              </a>
            </div>
          </div>
          <div>
            I love to create fun stuffs in my free time. I have created a few
            projects that are currently live and are being used by people around
            the world. I have also created a few projects that are still in
            development.
          </div>
          <div class="flex md:gap-2 gap-1 items-center">
            <div class="md:text-base text-sm">Tech Stacks Used:</div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              JS/TS
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              HTML/CSS
            </div>
            <div class="p-1 text-sm font-bold rounded-lg bg-primary-dark">
              Fun
            </div>
          </div>
        </div>
        {#if width > 1024}
          <div
            class="w-52 h-52 rounded-lg bg-dark-white"
            style="background-color:#fff"
          >
            <img src="./fun.svg" alt="fun" class="w-full h-full" />
          </div>
        {/if}
      </div>
    </div>
  </div>
</main>
