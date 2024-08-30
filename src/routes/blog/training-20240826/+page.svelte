<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="training-20240826">Uteträning 2024-08-26</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-08-30</em></p>
    <p class="my-4 md:my-6 mx-1">Video på utomhusträningen jag hade. Lite tomt just nu men det ska bli ändring på detta! Alla är välkomna!</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/DlQGIMfDr18?si=LWENY4QMvZJHwZdv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">
        Ingen akrobatik just nu då min vänstra hälsena strular. Har besökt naprapaten och blivit knäckt på lite här och där. Smärtan beror förmodligen på en gammal Smärta
        från en tidigare skada i hälen dec 2023 då jag slog i den efter en misslyckad aerial twist. Sen har hela vadmuskeln kompenserat genom Att
        krampa ihop sig lite. Blivit ordinerade massage av typ "trycka inne" i vadmuskeln genom att gräva med tummen bredvid skenbenet. Gör ju härligt ont 😂. Känns ju nu redan mycket bättre.
    </p>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>