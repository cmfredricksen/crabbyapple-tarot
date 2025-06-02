<script>
    const links = [
        {
            path: "/",
            title: "Home"
        },
        {
            path: "/",
            title: "About"
        }
    ]
</script>

<header>
    <a href="/">
        <h1>Agnostic Tarot</h1>
    </a>
    <nav>
        {#each links as {path, title}}
            <a href={path}>{title}</a>
        {/each}
    </nav>
</header>

<style>
    header {
        padding: 2rem 1rem;
        display: flex;
        justify-content: space-between;
        align-items: baseline;
    }
    nav a{
        font-size: 1.25rem;
        margin: 0 1rem;
    }
</style>