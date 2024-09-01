<script>
    import "../app.css";
    import { page } from '$app/stores';
</script>

<div class="flex flex-col min-h-screen box-border">
    <nav>
        <div class="w-3/4 max-w-screen-md mx-auto flex items-center justify-between text-lg">
            <div>
                <ul class="flex flex-row p-4">
                    <li class="py-2 px-3 text-nowrap font-semibold">
                        <a href="/">Ethan Bork</a>
                    </li>
                </ul>
            </div>
    
            <div>
                <ul class="flex flex-row p-4">
                    <li class="pr-2">
                        <a href="/projects" class="py-2 px-3 rounded-lg hover:bg-gray-100 {($page.url.pathname === '/projects') ? 'bg-gray-100 border border-gray-300 hover:border-gray-400' : ''}">Projects</a>
                    </li>
                    <li>
                        <a href="/about" class="py-2 px-3 rounded-lg hover:bg-gray-100 {($page.url.pathname === '/about') ? 'bg-gray-100 border border-gray-300 hover:border-gray-400' : ''}">About</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <hr class="h-px bg-gray-300 border-0">
    <slot />
</div>
