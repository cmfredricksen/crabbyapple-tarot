<script>
    import "../app.css"
    import { Header } from "$lib/components/index";
    let { children } = $props()
</script>


<main>
    {@render children()}
</main>
<Header />

<style>
    main {
        min-height: 100vh;
    }
</style>