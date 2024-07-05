/* Reset de estilos básicos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: #111;
    color: #fff;
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.navbar {
    background-color: #111;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.navbar .logo img {
    width: 120px;
    height: auto;
}

.navbar nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    align-items: center;
}

.navbar nav ul li {
    margin-right: 20px;
}

.navbar nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    transition: color 0.3s ease;
}

.navbar nav ul li a:hover {
    color: #e50914; /* Color rojo de Netflix */
}

.navbar .user {
    margin-left: auto;
}

.btn {
    cursor: pointer;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn-signin {
    background-color: #e50914;
    color: #fff;
}

.hero {
    height: 100vh;
    background-image: url('hero_bg.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.5rem;
    margin-bottom: 30px;
}

.btn-primary {
    background-color: #e50914;
    color: #fff;
    font-size: 1.2rem;
}

.content {
    padding: 50px 0;
}

.content h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.movies {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.movie {
    width: 200px;
    margin-bottom: 30px;
}

.movie img {
    width: 100%;
    border-radius: 5px;
}

.footer {
    background-color: #111;
    padding: 20px 0;
    text-align: center;
    position: relative;
    bottom: 0;
    width: 100%;
}
