<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p><em>I'm a BCA Student</em></p>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <hr>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is <strong>Venkateswar Aggarwal</strong>. I am a BCA student at <strong>Geeta University</strong>.</p>
        <p>I enjoy working with <abbr title="HyperText Markup Language">HTML</abbr>, CSS, and JavaScript to create user-friendly websites.</p>
        <hr>
    </section>
    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Gallery</h2>
        <figure>
            <img src="705f93fe08fc12e0da5f79e28073490f.jpg" height="100" width="100" alt="Profile Picture">
            <figcaption>My Profile Picture</figcaption>
        </figure>

        <video controls width="300">
            <source src="sample.mp4" type="video/mp4">
            Your browser does not support video.
        </video>

        <audio controls>
            <source src="sample.mp3" type="audio/mpeg">
            Your browser does not support audio.
        </audio>
        <hr>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" placeholder="Enter your email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" rows="5" cols="40"></textarea><br><br>

            <label>Gender:</label>
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female <br><br>

            <label>Interests:</label>
            <input type="checkbox"> Coding
            <input type="checkbox"> Sports
            <input type="checkbox"> Reading <br><br>

            <label for="country">Choose Country:</label>
            <select id="country">
                <option>India</option>
                <option>USA</option>
                <option>UK</option>
            </select><br><br>

            <input type="submit" value="Submit">
        </form>
        <hr>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 My Portfolio | Made with ❤️ using HTML</p>
        <address>
            Written by: <a href="mailto:myemail@example.com">myemail@example.com</a>
        </address>
    </footer>

</body>
</html>
