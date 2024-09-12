<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="training-20240830">Kungfu-träning 2024-09-09</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-09-12</em></p>
    <p class="my-4 md:my-6 mx-1">Video på träning:</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/pDWsJwkJLuA?si=PvmEir-D_oqnJgGm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">två minuter Mabu. Snacka om hard-core 🤘!:</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/ouSsHtXx-MQ?si=4jSrTlevVWgAjg8B" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>