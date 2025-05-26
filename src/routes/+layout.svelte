<script>
    import "../app.css"
    import { Header } from "$lib/components/index";
    let { children } = $props()
</script>

<Header />

<main>
    {@render children()}
</main>

<style>
    main {
        width: 70%;
        margin: 2rem auto;
    }
</style>