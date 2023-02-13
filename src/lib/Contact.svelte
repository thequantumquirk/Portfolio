<script>
  import Textfield from "@smui/textfield";
  let fullName = "";
  let Email = "";
  let Subject = "";
  let Message = "";
</script>

<main class="py-32">
  <div
    id="contact"
    class="lg:px-32 w-screen flex flex-col justify-center items-center"
  >
    <div class="flex lg:gap-32 gap-8 items-center justify-between">
      <div
        class="border border-primary-dark opacity-50 h-0"
        style="width: 60vw"
      />
      <h1 class="text-primary-dark lg:text-4xl text-2xl font-bold">
        Contact
      </h1>
    </div>
  </div>
  <div
    class="lg:mx-64 lg:mt-16 mx-12 mt-8 lg:text-xl lg:text-lg flex flex-col justify-start gap-4"
  >
    <div>
      <span class="text-primary-dark font-bold mr-1">Phone: </span> +91 78689 78957
    </div>
    <div>
      <span class="text-primary-dark font-bold mr-1">Email: </span> fosslover@duck.com
    </div>
    <div>
      <div class="text-primary-dark font-bold mb-2">Social Media:</div>
      <a
        href="https://www.github.com/fosslover69"
        target="_blank"
        rel="noreferrer"
      >
        <i class="fab fa-github lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
      <a
        href="https://www.linkedin.com/in/fosslover69"
        target="_blank"
        rel="noreferrer"
      >
        <i class="fab fa-linkedin lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
      <a
        href="https://www.telegram.dog/fosslover"
        target="_blank"
        rel="noreferrer"
      >
        <i class="fab fa-telegram lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
      <a
        href="https://blog.fosslover.dev/shows"
        target="_blank"
        rel="noreferrer"
      >
        <i class="fab fa-dev lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
      <a href="mailto:fosslover@duck.com" target="_blank" rel="noreferrer">
        <i class="fas fa-envelope lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
      <a
        href="https://www.youtube.com/@IntrovertedTechie"
        target="_blank"
        rel="noreferrer"
      >
        <i class="fab fa-youtube lg:fa-3x fa-2x lg:mr-4 mr-2" />
      </a>
    </div>
    <!-- <div>
      <div class="text-primary-dark font-bold mt-4">Ping Me:</div>
      <div class="flex items-center flex-col justify-center">
        <div>
          <div class="flex lg:flex-row flex-col lg:gap-6 gap-4 mt-4 form">
            <Textfield
              class="shaped-outlined lg:w-1/2"
              variant="outlined"
              bind:value={fullName}
              label="Full Name"
            />
            <Textfield
              class="shaped-outlined lg:w-1/2"
              variant="outlined"
              bind:value={Email}
              label="Email"
            />
          </div>
          <div class="flex flex-col form">
            <Textfield
              class="shaped-outlined mt-4"
              variant="outlined"
              bind:value={Subject}
              label="Subject"
            />
            <Textfield
              class="shaped-outlined mt-4"
              input$rows={6}
              variant="outlined"
              textarea
              bind:value={Message}
              label="Message"
            />
          </div>
          <button
            class="lg:px-4 px-2 font-bold lg:py-2 py-1 mt-4 bg-primary-dark rounded-lg text-sm lg:text-base"
            >Submit</button
          >
        </div>
      </div>
    </div> -->
  </div>
</main>

<style>
  .form {
    width: 65vw;
  }
  @media (max-width: 768px) {
    .form {
      width: 80vw;
    }
  }
</style>
