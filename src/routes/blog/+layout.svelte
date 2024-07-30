<slot />

<p>Kommentarer</p>
<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin"
</script>

<div>
    <Utterances {reponame} {theme} />
</div>