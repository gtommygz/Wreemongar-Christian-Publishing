<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Wreemongar Christian Publishing, LLC - Nurturing Faith Through Literature">
    <meta name="keywords" content="Christian books, Christian literature, faith-based publishing, Wreemongar Christian Publishing">
    <meta name="author" content="Wreemongar Christian Publishing, LLC">
    <title>Wreemongar Christian Publishing, LLC</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4b2e2e;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        header img {
            height: 60px;
        }
        nav {
            display: flex;
            justify-content: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        #search-bar {
            padding: 5px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
        }
        .hero {
            background: url('/images/logo.png') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }
        .section {
            padding: 50px 20px;
            text-align: center;
        }
        .section.bg-light {
            background-color: #fff;
        }
        .section.bg-dark {
            background-color: #333;
            color: #fff;
        }
        footer {
            background-color: #4b2e2e;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            color: #fff;
            background-color: #d9534f;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #c9302c;
        }
        .social-media {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .social-media a {
            color: #fff;
            margin: 0 10px;
            font-size: 24px;
        }
        .video-audio {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .video-audio div {
            margin: 10px;
            max-width: 400px;
        }
        .video-audio iframe {
            width: 100%;
            height: 200px;
        }
        .book-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .book-item {
            margin: 20px;
            text-align: center;
        }
        .book-item img {
            width: 150px;
            height: 200px;
            object-fit: cover;
            margin-bottom: 10px;
        }
        .book-item .btn {
            margin: 5px;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());

        gtag('config', 'YOUR_TRACKING_ID');
    </script>
</head>
<body>

<header>
    <img src="/images/logo.png" alt="Wreemongar Christian Publishing Logo">
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#books">Books</a>
        <a href="#authors">Authors</a>
        <a href="#blog">Blog</a>
        <a href="#courses">Courses</a>
        <a href="#video-audio">Video/Audio</a>
        <a href="#contact">Contact</a>
    </nav>
    <input type="text" id="search-bar" placeholder="Search...">
</header>

<section class="hero" id="home">
    <h1>Welcome to Wreemongar Christian Publishing, LLC</h1>
    <p>Nurturing Faith Through Literature</p>
    <a href="#books" class="btn">Explore Our Books</a>
</section>

<section class="section bg-light" id="about">
    <h2>About Us</h2>
    <p>Our mission is to publish Christian literature that inspires and nurtures faith.</p>
</section>

<section class="section bg-dark" id="books">
    <h2>Our Books</h2>
    <div class="book-list">
        <div class="book-item">
            <img src="images/book-cover1.jpg" alt="Book Cover">
            <h3>Book Title 1</h3>
            <p>Author: Author Name</p>
            <a href="https://amazon.com" target="_blank" class="btn">Buy on Amazon</a>
            <a href="https://barnesandnoble.com" target="_blank" class="btn">Buy on B&N</a>
        </div>
        <!-- Add more book items similarly -->
    </div>
</section>

<section class="section bg-light" id="authors">
    <h2>Our Authors</h2>
    <p>Meet the talented authors behind our books.</p>
</section>

<section class="section bg-dark" id="blog">
    <h2>Blog</h2>
    <p>Read our latest articles and updates.</p>
</section>

<section class="section bg-light" id="courses">
    <h2>Ministry Courses</h2>
    <p>Explore our courses designed to enhance your ministry skills.</p>
</section>

<section class="section bg-dark" id="video-audio">
    <h2>Video/Audio</h2>
    <div class="video-audio">
        <div>
            <h3>Latest Sermon</h3>
            <iframe src="https://www.youtube.com/embed/examplevideo1" frameborder="0" allowfullscreen></iframe>
        </div>
        <div>
            <h3>Author Interview</h3>
            <iframe src="https://www.youtube.com/embed/examplevideo2" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>
</section>

<section class="section bg-light" id="search-engine">
    <h2>Search Christian Topics</h2>
    <input type="text" id="christian-search" placeholder="Search...">
    <button onclick="searchChristianTopics()">Search</button>
    <div id="search-results"></div>
</section>

<section class="section bg-dark" id="sermon-generator">
    <h2>Generate Sermons/Messages</h2>
    <textarea id="sermon-topic" rows="4" cols="50" placeholder="Enter sermon topic..."></textarea>
    <button onclick="generateSermon()">Generate Sermon</button>
    <div id="sermon-output"></div>
</section>

<section class="section bg-light" id="contact">
    <h2>Contact Us</h2>
    <p>Get in touch with us for any inquiries or support.</p>
    <div class="social-media">
        <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
        <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://youtube.com" target="_blank"><i class="fab fa-youtube"></i></a>
        <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
    </div>
</section>

<footer>
    <p>&copy; 2024 Wreemongar Christian Publishing, LLC. All rights reserved.</p>
</footer>

<script>
    document.getElementById('search-bar').addEventListener('keypress', function (e) {
        if (e.key === 'Enter') {
            let query = e.target.value.toLowerCase();
            let sections = document.querySelectorAll('section');
            sections.forEach(section => {
                if (section.innerText.toLowerCase().includes(query)) {
                    section.scrollIntoView({ behavior: 'smooth' });
                }
            });
        }
    });

    function searchChristianTopics() {
        let query = document.getElementById('christian-search').value;
        window.open(`https://www.google.com/search?q=${query}+Christianity`, '_blank');
    }

    async function generateSermon() {
        let topic = document.getElementById('sermon-topic').value;
        let response = await fetch('/generate-sermon', {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json'
            },
            body: JSON.stringify({ topic: topic })
        });
        let data = await response.json();
        document.getElementById('sermon-output').innerText = data.sermon;
    }
</script>

</body>
</html>
