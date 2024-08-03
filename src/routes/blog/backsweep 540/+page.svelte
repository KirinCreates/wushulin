<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<h1 class="text-3xl font-bold my-3 mx-1" id="någonting">540 någonting?</h1>
<p class="my-3 mx-1"><em>Datum skrivet: 2024-07-31</em></p>
<p class="my-3 mx-1">Nja inte riktigt enligt videoklippet, men nära. Behöver ju finslipa på bakåtsvepet så man sätter 540 grader konsekvent. Har satt den off camera. Ni får lita på mig!</p>
<p class="my-3 mx-1"><a href="https://youtu.be/RjUPFzpgLug" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/RjUPFzpgLug/0.jpg" alt="Watch the video"></a></p>
<p class="my-3 mx-1">Key takeaways teknikmässigt: Bäst att först öva på att sätta 180 och 360 grader först konsekvent. För att få till 540 grader så behöver man justera tekniken. Enklaste sättet att förklara det är att man behöver starta svepet tidigt och “wind:a” nedåt samtidit som man sveper. Detta ger momentum för hela kroppen. Såsom tekniken brukar läras ut funkar bara för upp till 360-400ish grader.</p>
<p class="my-3 mx-1">Bonusvideo:<br>
<a href="https://youtube.com/shorts/Bcrt-_azPTU?si=YWnU26adiR75kACJ" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/Bcrt-_azPTU/0.jpg" alt="Watch the video"></a></p>
<p class="my-3 mx-1">Känner verkligen att tekniken inte är optimerad ännu då jag inte får till hopphöjden och rotationen. Ska nog testa att öva på att ta ett snedsteg istället som takeoff. Tror att det blir lättare med rotationen i alla fall.</p>

<h1 class="text-3xl font-bold my-3 mx-1">Kommentarer</h1>
<p class="my-3 mx-1"><em>Man måste skapa ett konto (gratis) på github.com för att kunna kommentera</em></p>
<Utterances {reponame} {issueTerm} {theme} />