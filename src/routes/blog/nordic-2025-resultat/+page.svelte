<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin";
    let issueTerm = 'url';
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">

<h1 class="text-3xl font-bold my-4 md:my-6 mx-1" id="varför-träna-kampsport">Reflektioner efter Nordic Wushu Open 2025</h1>
<p class="my-4 md:my-6 mx-1"><em>Datum skrivet: 2025-12-21</em></p>
<p class="my-4 md:my-6 mx-1">
    Då har man tävlat igenom efter ett litet break. Jag och min elev, Aryan har deltagit på 7th Nordic Open Wushu Championships 2025, 
    en internationell kungfu-tävling med deltagare från olika delar av världen. Tävling höll hus den 13/12 2025 i Solnahallen som en del av kampsportsfestivalen.
    Jag och min elev deltog med klassen tradtionellt långt vapen respektive öppen traditionell vapen och vi körde stav för åldrarna 18-39 respektive 6-11 år. 
    För mig blev det silver 🥈och för Aryan blev det guld 🥇. Hurra och grattis 🎉🎊🥳!
</p>

<p class="my-4 md:my-6 mx-1">
    I nedanstående vidoeklipp kan man se min och Aryans performance!
</p>

<div class="mx-1 mb-6">
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/trrEXNCb7Bs?si=Ih6_tPPOIra0gQXz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div class="mx-1 mb-6">
    <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/SPyWo5UFF9Q?si=vtTpSodgaPM2SJdB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<Utterances {reponame} {issueTerm} {theme} />
</div>