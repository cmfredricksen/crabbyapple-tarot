<script>
    import LeMat from "../images/a22.jpg"
</script>

<section class="hero">
    <div class="left-column">
        <h1 class="hero-title">Agnostic Tarot</h1>
        <img src={LeMat} alt="Le Mat">
    </div>
    <div class="right-column">

        <h1>Welcome Fellow Traveler</h1>
    </div>
</section>

<style>
    section.hero {
        display: flex;
        height: 100vh;
        background: linear-gradient(lavender, lavenderBlush);
        border: 1rem solid deepskyblue;
        
    }
    .left-column {
        display: flex;
        flex-direction: column;
        width: 50%;
        padding:  1rem;
        align-items: center;
        justify-content: center;
    }
    
    img {
        border: 1rem solid lightskyblue;
        outline: 1.5rem deepskyblue;
        margin: 1rem 0;
    }
     .right-column {
        display: flex;
        flex-direction: column;
        width: 50%;
        padding:  1rem;
        align-items: center;
        justify-content: center;
    }
</style>