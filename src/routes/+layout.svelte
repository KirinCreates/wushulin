<script>
	import logo from '$lib/assets/logo.webp';
    import yt from '$lib/assets/yt logo 48px.png';
    import insta from '$lib/assets/insta logo 48px.png';
    import "../app.css";
    export let data;
</script>

<div>
    <img class="m-4 md:w-64 mx-auto" alt="The project logo" src={logo} />
    <div class="flex justify-center md:text-lg lg:text-xl">
        <nav class="flex flex-wrap justify-center items-center my-1">
            {#each data.navItems as navItem}
                <a href={navItem.url} class="rounded-lg px-3 py-2 text-slate-700 font-medium hover:bg-slate-200 hover:text-slate-900">{navItem.title}</a>
            {/each}
        </nav>
    </div>
    <div class="flex justify-center">
        <a target="_blank" rel="noopener noreferrer" href="https://www.youtube.com/@Wushulin">
            <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Wushulin youtube page" src={yt} />
        </a>
        <a target="_blank" rel="noopener noreferrer" href="https://www.instagram.com/linloiwushu/">
            <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Wushulin isntagram page" src={insta} />
        </a>
    </div>
</div>

<slot />