<script>
    import LeMat from "../images/a22.jpg"
</script>

<section class="hero">
    <div class="left-column">

        <img src={LeMat} alt="Le Mat">
    </div>
    <div class="right-column">

        <h2>Tarot is a Tool</h2>
        <p>Welcome Fellow Traveler</p>
    </div>
</section>

<style>
    section.hero {
        display: flex;
        border: 2px solid green;
        height: 100vh;
    }
    .left-column {
        display: flex;
        width: 50%;
        padding:  1rem;
        background-color: black;
        align-items: center;
        justify-content: center;
    }
    
    img {
        border: 2px solid magenta;
    }
     .right-column {
        width: 50%;
        padding:  1rem;
        border: 2px solid orange;
    }
</style>