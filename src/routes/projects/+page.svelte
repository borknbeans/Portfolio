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
                        <a href="https://github.com/borknbeans/Portfolio" target="_blank"><img src={github} alt="Source" class="w-6 h-6"></a>
                    </div>
                    
                    <p class="text-gray-500">This website was created using SvelteKit and Tailwind.</p>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md flex flex-col">
                <div class="flex-1">
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Minecraft Sorting Mod</h1>
                        <a href="https://github.com/borknbeans/LightweightInventorySorting" target="_blank">
                            <img src={github} alt="Source" class="w-6 h-6">
                        </a>
                    </div>
                    <p class="text-gray-500">Java mod that allows for a user to sort any inventory with a variety of customization options.</p>
                </div>
                <div class="flex items-center justify-between mt-auto">
                    <div class="space-x-2">
                        <a href="https://modrinth.com/mod/lightweight-inventory-sorting" target="_blank" class="bg-gray-100 p-2 rounded-lg border border-gray-300 hover:border-gray-500">Modrinth</a>
                        <a href="https://legacy.curseforge.com/minecraft/mc-mods/lightweight-inventory-sorting" target="_blank" class="bg-gray-100 p-2 rounded-lg border border-gray-300 hover:border-gray-500">CurseForge</a>
                    </div>
                    <div class = "flex flex-row items-center space-x-2">
                        <img src={download} alt="Downloads" class="w-4 h-4">
                        <p class="text-gray-500">24.8k</p>
                    </div>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md flex flex-col">
                <div class="flex-1">
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Jame Gam #36</h1>
                    </div>
                    <p class="text-gray-500">Game Jam submission made in Unity with C#. Ranked 7/122 for fun factor.</p>
                </div>
                <div class="flex items-center justify-between mt-auto">
                    <div class="space-x-2">
                        <a href="https://borknbeans.itch.io/ember" target="_blank" class="bg-gray-100 p-2 rounded-lg border border-gray-300 hover:border-gray-500">Try it out</a>
                    </div>
                </div>
            </li>
            <li class="p-4 rounded-lg bg-white h-48 drop-shadow-md flex flex-col">
                <div class="flex-1">
                    <div class="flex flex-row pb-5 justify-between">
                        <h1 class="font-bold">Stream Listener</h1>
                        <a href="https://github.com/borknbeans/StreamListener" target="_blank">
                            <img src={github} alt="Source" class="w-6 h-6">
                        </a>
                    </div>
                    <p class="text-gray-500">.NET Console Application which listens to my Twitch/Tiktok streams and sets up events for my mods to subscribe to.</p>
                </div>
                <div class="flex items-center justify-between mt-auto">
                    <div class="space-x-2">
                        <a href="https://www.tiktok.com/@borknbean/video/7407955541533674794" target="_blank" class="bg-gray-100 p-2 rounded-lg border border-gray-300 hover:border-gray-500">Demo</a>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</div>
