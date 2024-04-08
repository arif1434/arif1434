<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Sharing Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Video Sharing Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Upload</a></li>
                <li><a href="#">Channels</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="video">
            <h2>Featured Video</h2>
            <video id="featuredVideo" controls>
                <source src="video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>
        <section class="videos">
            <h2>Recent Videos</h2>
            <div id="videoList" class="video-list">
                <!-- Video list items go here -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Video Sharing Website. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
