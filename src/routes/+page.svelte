
<div class="container">
    <img src="/cheems.png" alt="Cheems" class="circle-image" />
    <div class="description-container">
        <h1>Kaelan Davis</h1>
        <p>A software engineer currently working for PIMCO</p>
    </div>
    <div class="links-container">
        <a href="https://github.com/kdavis586" target="_blank" rel="noopener noreferrer">GitHub</a>
    </div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');

    * {
        font-family: 'Open Sans', sans-serif;
    }
    
    .container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .circle-image {
        width: 200px;
        height: 200px;
        border-radius: 50%;
        object-fit: cover;
    }

    .description-container {
        text-align: center;
        margin-top: 20px;
    }

    .links-container {
        margin-top: 40px;
    }
</style>
