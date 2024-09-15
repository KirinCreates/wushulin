<script>
    import playStore from '$lib/assets/play store 48px.png';
    import appStore from '$lib/assets/app store 48px.png';

    //variable Init
	let sign = "+";
	//function to be called on click
	function expand() {
		var content = this.nextElementSibling;
        if (content.style.display === "block") {
            content.style.display = "none";
            sign = "+";
        } else {
            content.style.display = "block";
            sign = "-";
        }
	}
</script>

<div class="md:w-[48rem] md:mx-auto md:text-lg lg:text-xl">
    <button on:click={expand} class="pl-1 text-left mt-4 w-full bg-slate-300 hover:bg-slate-400 text-black font-bold py-2">Missa inga inlägg!<span class="float-right mr-2">{sign}</span></button>
    <div class="overflow-hidden hidden bg-slate-100">
        <h1 class="text-xl font-bold my-4 md:my-6 mx-1">Metod 1: Gå med i facebookgruppen</h1>
        <p class="my-4 md:my-6 mx-1">
            Joina wushulins <a class="text-blue-700 underline" href="https://www.facebook.com/groups/1551666515730401/">facebook-grupp</a> så uppdaterar jag gruppen när ett nytt inlägg kommer upp på bloggen!
            Ni kan också nå mig via gruppen.
        </p>  

        <h1 class="text-xl font-bold my-4 md:my-6 mx-1">Metod 2: Som en del i ditt nyhetsflöde (social media-fri metod)</h1>
        <p class="my-4 md:my-6 mx-1">
            Vill man prenumerera på mina bloggposter så man inte missar inlägg från mig så kan man göra detta genom
            att installera en mobilapp (feedly) som hanterar nyheter för dig:
        </p>    

        <div class="flex justify-center mb-4">
            <a target="_blank" rel="noopener noreferrer" href="https://play.google.com/store/apps/details?id=com.devhd.feedly">
                <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Ladda ned Android-app" src={playStore} />
            </a>
            <a target="_blank" rel="noopener noreferrer" href="https://apps.apple.com/us/app/feedly-smart-news-reader/id396069556">
                <img class="min-[0px]:w-8 sm:w-8 md:w-10 mx-2" alt="Ladda ned Iphone-app" src={appStore} />
            </a>
        </div>
        <p class="my-4 md:my-6 mx-1">
            Efter installation av appen så är det bara att logga in med google eller apple alternativt skapa ett konto.
            Sök sedan på wushulin.se och lägg till bloggen med +. Man Kan ställa in notifikationer för appen så får man en notifikation när en ny bloggpost är publicerad.
        </p>
        <p class="my-4 md:my-6 mx-1">
            Använder man inte en mobil så kan man skapa ett konto på <a target="_blank" rel="noopener noreferrer" href="https://feedly.com/news-reader" class="text-sky-500 no-underline hover:underline ...">feedly.com</a>
        </p>
    </div>
      
    <h1 class="text-3xl font-bold my-4 md:my-6 mx-1">Bloggposter!</h1>
    <div class="border-2 border-slate-200 rounded my-1">
        <p class="my-4 md:my-6 mx-1 float-right"><em>Skrevs 2024-09-15</em></p>
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/training-20240913">Kungfu-träning 2024-09-13</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Felxibilitetsstyrka</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <p class="my-4 md:my-6 mx-1 float-right"><em>Skrevs 2024-09-12</em></p>
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/training-20240909">Träning 2024-09-09</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Maximum hardcore 🤘!</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <p class="my-4 md:my-6 mx-1 float-right"><em>Skrevs 2024-09-08</em></p>
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/reaching-out">Att nå ut</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Veckan som gått samt stavträning</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/training-20240830">Kombinationsträning 2024-08-30</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Lite changquan (long fist)</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/training-20240826">Utomhusträning 2024-08-26</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Alla är välkomna + status update!</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/why-practicing-martial-arts">Varför träna kampsport?</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Hur vill du att din kampsportsresa ska se ut?</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/reklampelare">Levande reklampelare</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Alla i familjen ingår!</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/trailer">Min trailer</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Ett gott försök till en i alla fall!</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/recovery">High impact recovery!</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Återhämtning på hög nivå här!</p>
    </div>
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/art-of-winning">Konsten att vinna</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Varför tävlar du?</p>
    </div>
    
    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/backsweep 540">540 någonting?!</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Mina tankar kring bakåtsvep inom wushu</p>
    </div>

    <div class="border-2 border-slate-200 rounded my-1">
        <h2 class="text-2xl font-bold my-4 md:my-6 mx-1">
            <a class="text-blue-700 underline" href="/blog/first-post">Första bloggposten!</a>
        </h2>
        <p class="my-4 md:my-6 mx-1">Mina tankar kring hemsidan</p>
    </div>
</div>
