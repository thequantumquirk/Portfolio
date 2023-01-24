<main class="py-40">
    <div id="contact" class="px-32 w-screen flex flex-col justify-center items-center">
        <div class="flex gap-32 items-center justify-between">
            <div class="border border-primary-dark opacity-50 h-0" style="width: 60vw"></div>
            <div class="text-primary-dark text-4xl font-bold">Contact</div>
        </div>
    </div>
    <div class="mx-64 mt-16 text-xl">
        <div><span class="text-primary-dark font-bold mr-1">Phone: </span> +91 78689 78957</div>
        <div><span class="text-primary-dark font-bold mr-1">Email: </span> fosslover@duck.com</div>
        <div><span class="text-primary-dark font-bold mr-1">Social Media: </span></div>
        <div>
            <div class="text-primary-dark font-bold mt-4">Ping Me:</div>
            <div>
                <div class="flex gap-6 mt-4">
                    <div class="w-full">
                    <Textfield
                    class="shaped-outlined w-full"
                    variant="outlined"
                    bind:value={fullName}
                    label="Full Name"
                    >                        
                    </Textfield>
                </div><div  class="w-full">
                    <Textfield
                    class="shaped-outlined w-full"
                    variant="outlined"
                    bind:value={Email}
                    label="Email"
                    >                        
                    </Textfield>
                </div>
                </div>
                <Textfield
                class="shaped-outlined w-full mt-4"
                variant="outlined"
                bind:value={Subject}
                label="Subject"
                >                        
                </Textfield>
                <Textfield
                class="shaped-outlined mt-4"
                style="width: 100%;"
                input$rows={6}
                helperLine$style="width: 100%;"
                variant="outlined"
                textarea
                bind:value={Message}
                label="Message"
                >                        
                </Textfield>
                <button class="px-4 font-bold py-2 mt-4 bg-primary-dark rounded-lg">Submit</button>
            </div>
        </div>
    </div>
</main>
<script>
    import Textfield from '@smui/textfield';
    import HelperText from '@smui/textfield/helper-text';
    let fullName = "";
    let Email = "";
    let Subject = "";
    let Message = "";
</script>