<div id="resume" class="px-32 w-screen pt-40">
    <div class="flex gap-32 items-center justify-center">
        <div class="border border-primary-dark opacity-50 h-0" style="width: 60vw"></div>
        <div class="text-primary-dark text-4xl font-bold">Resume</div>
    </div>
    <div class="mx-32 mt-16">
        <div class="text-3xl text-primary-dark font-bold">Professional Experience</div>
        <div class="flex mt-8 gap-4">
            <div class="flex mt-3 flex-col items-center">
                <div class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"></div>
                <div class="h-64 w-0 border-l-2 border-primary-dark"></div>
            </div>
            <div class="flex flex-col gap-2">
                <div class="flex gap-2 items-end">
                    <div class="text-3xl font-bold">FOSSFREAKS</div>
                    <div class="text-sm">(May 2022 - Present)</div>
                </div>
                <div class="text-2xl text-primary-dark font-bold">Front-End Developer</div>
                <ul>
                    <li>Actively participated in the front-end development of the projects as a member of the team</li>
                    <li>Worked with UI/UX designers to translate design concepts into high-quality, pixel-perfect code for user interfaces</li>
                    <li>Maintained effective communication with team members to ensure smooth and efficient project progress</li>
                    <li>Demonstrated proficiency in a range of technologies, including Vue.js, React.js, Typescript, and JavaScript</li>
                    <li>Utilized version control systems like Git to manage and track code changes</li>
                    <li>Leveraged Linux as the primary development environment to create and test code</li>
                </ul>
            </div>
        </div>
        <div class="flex gap-4 items-top">
            <div class="flex flex-col items-center">
                <div class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"></div>
                <div class="h-64 w-0 border-l-2 border-primary-dark"></div>
            </div>
            <div class="flex flex-col gap-2">
                <div class="flex gap-2 items-end">
                    <div class="text-3xl font-bold">CORVUS-AOSP</div>
                    <div class="text-sm">(Nov 2020 - Present)</div>
                </div>
                <div class="text-2xl text-primary-dark font-bold">AOSP Developer</div>
                <ul>
                    <li>Created and implemented user interfaces and user experiences, as well as development, for the website to enhance user engagement and functionality</li>
                    <li>Served as a device developer for the Redmi Note 7 Pro</li>
                    <li>Demonstrated extensive knowledge and usage of version control systems, specifically Git</li>
                    <li>Proficient in utilizing various cloud service providers, such as GCP, AWS, and Azure, to build firmware</li>
                    <li>To know more, Checkout Corvus-AOSP</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="mx-32 mt-16">
        <div class="text-3xl text-primary-dark font-bold">Education</div>
        <div class="flex mt-8 gap-4">
            <div class="flex flex-col mt-3 items-center">
                <div class="w-4 h-4 rounded-sm border-4 border-primary-dark rotate-45"></div>
                <div class="h-40 w-0 border-l-2 border-primary-dark"></div>
            </div>
            <div class="flex flex-col gap-2">
                <div class="flex gap-2 items-end">
                    <div class="text-3xl font-bold">Bishop Heber College</div>
                    <div class="text-sm">(August 2021 - Present)</div>
                </div>
                <div class="text-2xl text-primary-dark font-bold">Bachelor's in Computer Science</div>
                <ul>
                    <li>Successfully coordinated the Debian Day '22 event</li>
                    <li>Achieved third place in the DataHack '22 competition, organized by devfolio</li>
                    <li>Led the organization and execution of the Hybernitix Symposium</li>
                    <li>Led the Heber Quiz Club and oversaw the planning and execution of quiz events</li>
                </ul>
            </div>
        </div>
        </div>
        <div class="mx-32 mt-16">
        <div class="text-3xl text-primary-dark font-bold">Skills</div>
        <div class="flex mt-8 gap-8 flex-wrap">
            {#each skills as logo}
                <img style="height: 75px" src="../../public/skills/{logo}.svg" alt="skill" />
            {/each}
        </div>
    </div>
</div>
    <script lang="ts">
        let skills = ["vue","vuetify","nuxt","react","html","css","tailwind","js","ts","git","figma","linux"]
    </script>