<script>
    import ris from '$lib/assets/ris.jpg';
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="recovery">Återhämtning efter träning the asian way</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-08-15</em></p>
    <p class="my-4 md:my-6 mx-1">Som rubriken säger: The asian way (med lite italiensk inspiration). Recept: Jasmin-ris + olivolja + sojasås. Glutenfritt såklart! Testa! det är jättegott. Jag lovar!</p>
    <img class="m-4 md:w-64 mx-auto" alt="the rice is right" src={ris} />

<Utterances {reponame} {issueTerm} {theme} />
</div>