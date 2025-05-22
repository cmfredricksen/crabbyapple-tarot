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