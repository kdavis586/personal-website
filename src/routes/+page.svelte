<div class="container">
    <img id="pfp-image" src="/pfp.jpg" alt="Kaelan's Face"/>
    <div class="description-container">
        <h1>Kaelan Davis</h1>
        <p>Hello! 👋</p>
        <p>
            My name is Kaelan. I'm a software engineer who likes to make cool stuff!<br/><br/>
            I currently work as a junior software engineer at PIMCO. Before that, I got my bachelors in CS from UIUC.<br/><br/>
            Born in central Illinois 🌽, currently living in Irvine, CA 🍊
        </p>
    </div>
    <div class="links-container">
        <a href="https://github.com/kdavis586" target="_blank" rel="noopener noreferrer">
           <img src="/github-mark/github-mark.svg" alt="Github" />
        </a>
    </div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');

    /* Needed to reset the default margin of <body> in app.html */
    :global(body) {
        margin: 0;
    }

    * {
        font-family: 'Open Sans', sans-serif;
        box-sizing: border-box;
    }
    
    .container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 100vw;
        height: 100vh;
        background: linear-gradient(20deg, #46a6cc 0%, #e5e5e5 125%);
    }

    #pfp-image {
        width: 200px;
        height: auto;
        border-radius: 10%;
        object-fit: cover;
    }

    .description-container {
        text-align: center;
        width: 20%;
        margin-top: 20px;
        background-color: rgba(0, 0, 0, .7);
        color: white; /* added this line to make the font white */
        padding: 15px;
        border-radius: 5%;
    }

    .description-container p {
        text-align: left;
    }

    .links-container {
        display: flex;
        justify-content: center;
        margin-top: 20px;
    }

    .links-container img {
        height: 50px;
    }
</style>
