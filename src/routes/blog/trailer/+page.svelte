<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

    <h1 class="text-3xl font-bold my-3 mx-1" id="trailer">Trailer för hemsidan finns nu uppe</h1>
    <p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2024-08-20</em></p>
    <p class="my-4 md:my-6 mx-1">Skapade trailern med den samling av träningsvideos som man har filmat, så mycket är ju misslyckade nanduförsök 😹. Denna trailer består ju av de försök som inte är helt katastrofala. Borde lägga upp fler videos på när man kör hela former. Tradtionella former borde gå. Moderna är ju så krävande för min kropp 👨‍🦯.</p>
    <div class="mx-1 mb-6">
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/2Ofp96HFh88?si=a5tebiUfa_HAZBmp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <p class="my-4 md:my-6 mx-1">Följ mig gärna på instagram eller prenumerera på min youtube-kanal. Se menyn ovan.</p>

<Utterances {reponame} {issueTerm} {theme} />
</div>