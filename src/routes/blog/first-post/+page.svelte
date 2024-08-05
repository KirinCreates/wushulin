<script>
    import pubu from '$lib/assets/pubulogga.jpg';
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">
    <h1 class="text-3xl font-bold my-4 md:my-6 mx-1" id="första-bloggposten">Första bloggposten</h1>
    <blockquote>
    <p class="my-4 md:my-6 mx-1">Datum skrivet: 2024-07-30</p>
    </blockquote>
    <p class="my-4 md:my-6 mx-1">Hemsidan <a href="http://www.wushulin.se">www.wushulin.se</a> är nu lanserad! Hemsidan är just nu i skrivande stund “work in progress”. Jag kommer senare att lägga till mer innehåll. T.ex. mina favorit-wushu-videoklipp och diverse användbara appar kopplat till wushu samt snyggare layout.</p>
    <p class="my-4 md:my-6 mx-1">Bild som användes till loggan:</p>
    <p class="my-4 md:my-6 mx-1"><img src={pubu} alt="Bild som användes till loggan" width="500" /></p>
    <p class="my-4 md:my-6 mx-1">Tanken med hemsidan är att den ska bli en samlingspunkt för de som är intresserade av att träna  wushu med mig och/eller följa min träning. Har jag tillräckligt med tid så kommer jag att expandera hemsidan med användbara länkar/appar kring wushu som ska underlätta för en utövare.</p>

    <h1 class="text-3xl font-bold my-4 md:my-6 mx-1">Kommentarer</h1>
    <p class="my-4 md:my-6 mx-1"><em>Man måste skapa ett konto (gratis) på github.com för att kunna kommentera</em></p>
    <Utterances {reponame} {issueTerm} {theme} />
</div>