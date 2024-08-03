<script>
	import logo from '$lib/assets/logo.webp';
    import "../app.css";
    export let data;
</script>

<div>
    <img class="m-4 mx-auto" alt="The project logo" src={logo} />
    <div class="flex justify-center">
        <nav class="flex flex-wrap justify-center items-center my-1">
            {#each data.navItems as navItem}
                <a href={navItem.url} class="rounded-lg px-3 py-2 text-slate-700 font-medium hover:bg-slate-100 hover:text-slate-900">{navItem.title}</a>
            {/each}
            <!-- <a class="font-medium text-blue-600 dark:text-blue-500 hover:underline" href="/">Hem</a>
            <a class="font-medium text-blue-600 dark:text-blue-500 hover:underline" href="/training-wushu">Träna wushu</a>
            <a class="font-medium text-blue-600 dark:text-blue-500 hover:underline" href="/blog">Blogg</a>
            <a class="font-medium text-blue-600 dark:text-blue-500 hover:underline" href="/about">Om Lin</a> -->
        </nav>
    </div>
</div>

<slot />