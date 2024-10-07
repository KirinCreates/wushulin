<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="training-20240830">Kungfu-träning 20241005 hoppsparkar</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-10-07</em></p>
    <p class="my-4 md:my-6 mx-1">Varit lite sjuk så inte laddat upp på ett tag men nu är man friskare och det var ett tag sedan som man körde lite hoppsparkar. Video på träning:</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-[9/16]" src="https://youtu.be/t-3j_JHOw28?si=CyhzPnUl-hdZUrJb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>