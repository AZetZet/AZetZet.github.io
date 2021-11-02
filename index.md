<!DOCTYPE html>
<html>
    <head>
        <title>Biodata Diri</title>
        <style type="text/css">
            @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap');

body {
    font-family: 'Quicksand', sans-serif;
    margin: 0;
    padding: 0;
}

h2, h3, h4 {
    color: #00a2c6;
}

header {
    display: inline;
}

.jumbotron {
    font-size: 20px;
    padding : 60px;
    background-color: #00cBeb;
    text-align: center;
    color: white;
}

nav {
    background-color: #00a2c6;
    padding: 5px;
    position: sticky;
    top: 0;
}

nav a {
    font-size: 18px;
    font-weight: 400;
    text-decoration: sticky;
    color: white;
}

nav a:hover {
    font-weight: bold;
}

nav li {
    display: inline;
    margin-right: 20px;
    list-style-type: none;
}

footer {
    padding: 20px;
    color: white;
    background-color: #00a2c6;
    text-align: center;
    font-weight: bold;
}

main {
    padding: 20px;
    overflow: auto;
}

#content {
    float: left;
    width: 75%;
}

.card {
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    border-radius: 5px;
    padding: 20px;
    margin-top: 20px;
}

aside {
    float: right;
    width: 25%;
    padding-left: 20px;
}

* {
    box-sizing: border-box;
}

@media screen and (max-width: 1000px) {
    #concent, aside{
        width: 100%;
        padding: 0;
    }
}

.featured-image {
    width: 100%;
    max-height: 300px;
    object-fit: cover;
    object-position: center;
}
        </style>
        <meta name="viewport" content="width=device-width, initial-scale=1">
    </head>
    <body>
        <header>
            <div class="jumbotron">
                <h1>James Alejandro Sumardin</h1>
                <p>XII RPL</p>
            </div>

            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#skill">Skill</a></li>
                    <li><a href="#language">Language</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <div id="content">
                <article id="about" class="card">
                    <h2>About</h2>
                    
                    <img src="cktc.jpg" class="featured-image" alt="about">
                    <p>GG</p>
                </article>
                
                <article id="education" class="card">
                    <img src="cktc.jpg" class="featured-image" alt="about">
                    <h2>Education</h2>
                    <p>Geming</p>
                </article>
                
                <article id="skill" class="card">
                    
                    <img src="cktc.jpg" class="featured-image" alt="about">
                    <h2>Skill</h2>
                    <p>Gk</p>
                </article>
            </div>

            <aside>
                <article id="language" class="card">
                    
                    <img src="cktc.jpg" class="featured-image" alt="about">
                    <h2>Language</h2>
                    <p>Gais</p>
                </article>
            </aside>
        </main>
        <footer>
            <p>Produk kreatif dan kewirausahaan &#169; 2020, SMK CKTC</p>
        </footer>
    </body>
</html>
