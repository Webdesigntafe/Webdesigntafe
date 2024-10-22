- !DOCTYPE html>
<html lang="en">
<head>
    <title>Home Page</title>
    <link rel="icon" href="icons/home-solid.png">
    <link rel="stylesheet" href="styles/main.css">
    <link rel="stylesheet" href="styles/responsive.css">
    <meta charset="utf-8">
    <meta name="description" content="a web page for learning HTML and CSS">
    <meta name="keyword" content="HTML,CSS,learning">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <!-- <h1>Hello world</h1> -->
    <header class="main-header">
        <a href="/" class="logo">
            <img src="images/icon-black.png" alt="website logo">
        </a>
        <button type="button" class="nav-button">
            <i class="fa-solid fa-bars"></i>
        </button>
        <form class="search" method="get" action="https://example.com/search">
            <input type="search" name="query" placeholder="Search">
            <button type="submit">Search</button>
        </form>
        <nav class="navigation">
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <div class="banner">
        <h1>Welcome</h1>
    </div>
    <main class="home-content">
        <div class="card">
            <img class="card-image" src="images/510c929f-e33f-41c5-96a2-6a092e41fb83.jpg" alt="casual shoes">
            <div class="card-content">
                <h4>Casual Shoes</h4>
                <p>These casual shoes feature a sleek, low-top design with a breathable canvas upper, complemented by a cushioned insole for comfort.</p>
                <a href="#" class="card-button">Buy it now</a>
            </div>
        </div>
        <div class="card">
            <img class="card-image" src="images/700b0f05-183a-401a-9ae8-91d44a44382d.jpg" alt="basketball shoes">
            <div class="card-content">
                <h4>Basketball Shoes</h4>
                <p>These casual shoes feature a sleek, low-top design with a breathable canvas upper, complemented by a cushioned insole for comfort.</p>
                <a href="#" class="card-button">Buy it now</a>
            </div>
        </div>
        <div class="card">
            <img class="card-image" src="images/8721825c-4c3d-4bf1-96e5-4cb9c8d0ddc6.jpg" alt="formal shoes">
            <div class="card-content">
                <h4>Formal Shoes</h4>
                <p>These formal shoes feature a sleek, low-top design with a breathable canvas upper, complemented by a cushioned insole for comfort.</p>
                <a href="#" class="card-button">Buy it now</a>
            </div>
        </div>
    </main>
    <footer class="main-footer">
        <nav class="footer-nav">
            <a href="returns.html">Return Policies</a>
            <a href="exchange.html">Exchange Policies</a>
            <a href="delivery.html">Delivery Policies</a>
        </nav>
        <nav class="social-nav">
            <a href="https://facebook.com/tiptoeshoes">
                <i class="fa-brands fa-square-facebook" role="img" aria-label="Facebook"></i>
            </a>
            <a href="https://instagram.com/tiptoeshoes">
                <i class="fa-brands fa-square-instagram" role="img" aria-label="Instagram"></i>
            </a>
            <a href="https://twitter.com/tiptoeshoes">
                <i class="fa-brands fa-square-x-twitter" role="img" aria-label="X"></i>
            </a>
            <a href="https://youtube.com/tiptoeshoes">
                <i class="fa-brands fa-square-youtube" role="img" aria-label="YouTube"></i>
            </a>
        </nav>
    </footer>
</body>
</html>
