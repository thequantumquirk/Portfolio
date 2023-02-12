<script lang="ts">
  let width = window.innerWidth;
</script>

<main>
  <div id="portfolio" class="xl:px-32 w-screen pt-32">
    <div class="flex lg:gap-16 lg:gap-6 gap-3 items-center justify-center">
      <div
        class="border border-primary-dark opacity-50 h-0"
        style="width: 60vw"
      />
      <div class="text-primary-dark lg:text-4xl text-2xl font-bold">
        Portfolio
      </div>
    </div>
    <div
      class="flex lg:flex-row flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16"
    >
      <div class="w-52 h-52 rounded-lg bg-dark-white" />
      <div class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3">
        <div class="flex items-end gap-1">
          <div class="lg:text-4xl text-2xl font-bold">BAKEAHOLICS</div>
          <div>(Front-End)</div>
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
      class="flex lg:flex-row bg-card-black py-8 flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16 mt-8"
    >
      {#if width < 768}
        <div class="w-52 h-52 rounded-lg bg-dark-white" />
      {/if}
      <div class="flex w-3/4 flex-col justify-center lg:gap-6 gap-3">
        <div class="flex lg:flex-row flex-col gap-1 justify-between w-100 items-center">
          <div
            class="flex xl:flex-row flex-col lg:items-end items-center gap-1"
          >
            <div class="lg:text-4xl text-2xl font-bold">CORVUS-AOSP</div>
            <div>(Web Development and UI/UX design)</div>
          </div>
          <div>
            <button class="bg-primary-dark font-bold px-4 py-1 rounded-lg"
              >Site</button
            >
          </div>
        </div>
        <div>
          CorvusOS is a highly modified version of the Android Open Source
          Project, built on top of Android 10 and 11, and packed with
          customizations and features that are carefully selected to enhance the
          user experience. As an open source, non-profit project, it is created
          as a hobby by Android enthusiasts, including myself
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
      {#if width > 768}
        <div class="w-52 h-52 rounded-lg bg-dark-white" />
      {/if}
    </div>
    <div
      class="flex lg:flex-row flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16 mt-8"
    >
      <div class="w-52 h-52 rounded-lg bg-dark-white" />
      <div class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3">
        <div class="flex items-end gap-1">
          <div class="lg:text-4xl text-2xl font-bold">BAKEAHOLICS</div>
          <div>(Front-End)</div>
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
      class="flex lg:flex-row bg-card-black py-8 flex-col items-center justify-between lg:gap-32 lg:mx-32 mt-16 mt-8"
    >
      {#if width < 768}
        <div class="w-52 h-52 rounded-lg bg-dark-white" />
      {/if}
      <div class="flex w-3/4 flex-col lg:items-start items-center lg:gap-6 gap-3">
        <div class="flex lg:flex-row flex-col lg:items-end items-center gap-1">
          <div class="lg:text-4xl text-2xl font-bold">CORVUS-AOSP</div>
          <div>(Web Development and UI/UX design)</div>
        </div>
        <div>
          CorvusOS is a highly modified version of the Android Open Source
          Project, built on top of Android 10 and 11, and packed with
          customizations and features that are carefully selected to enhance the
          user experience. As an open source, non-profit project, it is created
          as a hobby by Android enthusiasts, including myself
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
      {#if width > 768}
        <div class="w-52 h-52 rounded-lg bg-dark-white" />
      {/if}
    </div>
  </div>
</main>
