<script>
    import github from '$lib/assets/github-mark.png';
    import download from '$lib/assets/download-icon.png';
</script>

<div class="flex flex-grow bg-gray-200">
    <div class="flex w-3/4 max-w-screen-md mx-auto p-4 justify-center">
        <ul class="grid grid-cols-2 gap-4 h-min w-full">
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md">
                <div>
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Portfolio Website</h1>
                        <a href="https://github.com/borknbeans/Portfolio" target="_blank"><img src={github} alt="Github" class="w-6 h-6"></a>
                    </div>
                    
                    <p class="text-gray-500">This website was created using SvelteKit and Tailwind.</p>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md flex flex-col">
                <div class="flex-1">
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Minecraft Sorting Mod</h1>
                        <a href="https://github.com/borknbeans/LightweightInventorySorting" target="_blank">
                            <img src={github} alt="Github" class="w-6 h-6">
                        </a>
                    </div>
                    <p class="text-gray-500">Allows for a user to sort any inventory with a variety of customization options.</p>
                </div>
                <div class="flex items-center space-x-2 justify-end mt-auto">
                    <img src={download} alt="Downloads" class="w-4 h-4">
                    <p class="text-gray-500">24.3k</p>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md">
                <div>
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Jame Gam</h1>
                        <a href="https://www.google.com" target="_blank"><img src={github} alt="Github" class="w-6 h-6"></a>
                    </div>
                    
                    <p class="text-gray-500">Jame Gam Project</p>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md">
                <div>
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Project Name</h1>
                        <a href="https://www.google.com" target="_blank"><img src={github} alt="Github" class="w-6 h-6"></a>
                    </div>
                    
                    <p class="text-gray-500">This is the description for my project</p>
                </div>
            </li>
        </ul>
    </div>
</div>
