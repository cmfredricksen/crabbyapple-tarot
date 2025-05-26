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
    <h1>Agnostic Tarot</h1>
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
        margin: 0 1rem;
        text-decoration: none;
    }
    a:hover {
        color: grey;
    }
</style>