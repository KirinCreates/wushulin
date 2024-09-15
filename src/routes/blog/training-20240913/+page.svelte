<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="training-20240830">Kungfu-träning 2024-09-13</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-09-15</em></p>
    <p class="my-4 md:my-6 mx-1">Video på träning:</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-[9/16]" src="https://youtube.com/embed/HwPF65Db5YA?si=PWxBmcKImC2avP6o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>