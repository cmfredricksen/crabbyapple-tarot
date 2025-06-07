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
        <p>Tarot is the perfect tool to help you find answers and solutions to the obstacles in your life. Use the cards to gain insight and an "objective" point of view.</p>
        <p>Tarot is practical and down to Earth, it triggers your creative mind, bringing forth ideas and inspiration. Tarot also allows you to make new connections within your own life, relationships and habits.</p>
    </div>
</section>

<style>
    section.hero {
        display: flex;
        height: 100vh;
        background-color: var(--clr-blue);
        
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
        border: 1rem solid var(--clr-green);
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