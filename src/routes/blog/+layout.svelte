<slot />

<p>Kommentarer</p>
<script>
    import { Utterances, utterancesTheme } from "@codewithshin/svelte-utterances";
    const theme = 'github-light';
    let reponame = "KirinCreates/wushulin"
    let issueTerm = "title"
</script>

<div>
    <Utterances {reponame} {issueTerm} {theme} />
</div>