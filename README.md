# Hotelcatz.github.io
mkdir css js images
touch index.html about.html gallery.html booking.html blog.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotelcatz - Home</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Hotelcatz</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About/Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="booking.html">Booking and Pay</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Featured</h2>
            <p>Welcome to the Hotelcatz website. Explore our services and make your booking today!</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Hotelcatz. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotelcatz - About/Contact</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>About Hotelcatz</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About/Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="booking.html">Booking and Pay</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Our Story</h2>
            <p>Learn more about Hotelcatz and our mission to provide the best service.</p>
            <h2>Contact Us</h2>
            <p>Feel free to reach out through our contact form or visit us at our location.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Hotelcatz. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotelcatz - Gallery</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Our Gallery</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About/Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="booking.html">Booking and Pay</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Image Gallery</h2>
            <div class="gallery">
                <!-- Add your images here -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Hotelcatz. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotelcatz - Booking and Pay</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Book Your Stay</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About/Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="booking.html">Booking and Pay</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Booking Form</h2>
            <form action="#">
                <label for="date">Date:</label>
                <input type="date" id="date" name="date">
                <label for="guests">Number of Guests:</label>
                <input type="number" id="guests" name="guests">
                <button type="submit">Book Now</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Hotelcatz. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotelcatz - Blog</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Our Blog</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About/Contact</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="booking.html">Booking and Pay</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Latest Posts</h2>
            <div class="blog-posts">
                <!-- Add your blog posts here -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Hotelcatz. All rights reserved.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}
nav ul {
    list-style-type: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 10px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}
main {
    padding: 2em;
}
footer {
