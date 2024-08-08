<script>
    import playStore from '$lib/assets/play store 48px.png';
    import appStore from '$lib/assets/app store 48px.png';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">
    <h1 class="text-3xl font-bold my-4 md:my-6 mx-1">Missa inga inlägg!</h1>
    <p class="my-4 md:my-6 mx-1">
        Vill man prenumerera på mina bloggposter så man inte missar inlägg från mig så kan man göra detta genom
        att installera en mobilapp (feedly) som hanterar nyheter för dig:
    </p>
    <div class="flex justify-center mb-4">
        <a target="_blank" rel="noopener noreferrer" href="https://play.google.com/store/apps/details?id=com.devhd.feedly">
            <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Ladda ned Android-app" src={playStore} />
        </a>
        <a target="_blank" rel="noopener noreferrer" href="https://apps.apple.com/us/app/feedly-smart-news-reader/id396069556">
            <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Ladda ned Iphone-app" src={appStore} />
        </a>
    </div>
    <p class="my-4 md:my-6 mx-1">
        Efter installation av appen så är det bara att logga in med google eller apple alternativt skapa ett konto.
        Sök sedan på wushulin.se och lägg till bloggen med +. Man startar bara appen och om det finns nya inlägg så borde man få notifikationer
    </p>
    <p class="my-4 md:my-6 mx-1">
        Använder man inte en mobil så kan man skapa ett konto på <a target="_blank" rel="noopener noreferrer" href="https://feedly.com/news-reader" class="text-sky-500 no-underline hover:underline ...">feedly.com</a>
    </p>
    <h1 class="text-3xl font-bold my-4 md:my-6 mx-1">Bloggposter!</h1>
    <hr>

    <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
        <a class="text-blue-700 underline" href="/blog/backsweep 540">540 någonting?!</a>
    </h2>
    <p class="my-4 md:my-6 mx-1">Mina tankar kring bakåtsvep inom wushu</p>
    <hr>

    <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
        <a class="text-blue-700 underline" href="/blog/first-post">Första bloggposten!</a>
    </h2>
    <p class="my-4 md:my-6 mx-1">Mina tankar kring hemsidan</p>
    <hr>
</div>
