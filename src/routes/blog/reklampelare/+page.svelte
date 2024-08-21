<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    import reklam from '$lib/assets/reklampelare.jpg';
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="reklam">Levande reklampelare</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-08-21</em></p>
    <p class="my-4 md:my-6 mx-1">Nu har man blivit en levande reklampelare:</p>
    <img class="m-4 md:w-64 mx-auto max-w-64" alt="Reklampelaren Lin" src={reklam} />
    <p class="my-4 md:my-6 mx-1">Alla i familjen är inkluderade.</p>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>