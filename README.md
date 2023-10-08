# Netflix-homepage


<!DOCTYPE html>
<html>
<head>
    <title>Netflix Clone</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="netflix-logo.png" alt="Netflix Logo">
            </div>
            <div class="nav-links">
                <a href="#">Home</a>
                <a href="#">TV Shows</a>
                <a href="#">Movies</a>
                <a href="#">My List</a>
            </div>
        </nav>
    </header>
    <main>
        <section class="hero">
            <div class="hero-content">
                <h1>Welcome to Netflix</h1>
                <p>Unlimited movies, TV shows, and more.</p>
                <button>Sign Up</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>




body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #111;
    color: white;
}

header {
    background-color: #111;
    padding: 20px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

.nav-links a {
    text-decoration: none;
    margin: 0 20px;
    color: white;
}

.logo img {
    width: 100px;
}

.hero {
    background-image: url('netflix-hero.jpg');
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    text-align: center;
    color: white;
}

.hero-content {
    margin: 0 auto;
    background-color: rgba(0, 0, 0, 0.7);
    padding: 20px;
    border-radius: 5px;
}

button {
    background-color: #e50914;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-weight: bold;
    font-size: 18px;
    border-radius: 3px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #222;
}




