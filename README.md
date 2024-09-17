<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stephen Curry Showcase</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: #fff;
        }
        .header {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
        }
        .content {
            padding: 20px;
        }
        .video, .photo {
            margin-bottom: 20px;
        }
        .video iframe, .photo img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: calc(33.333% - 10px);
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Stephen Curry Showcase</h1>
    </div>
    <div class="content">
        <div class="video">
            <h2>Featured Videos</h2>
            <iframe src="https://www.youtube.com/embed/VIDEO_ID1" frameborder="0" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/VIDEO_ID2" frameborder="0" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/VIDEO_ID3" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="photo">
            <h2>Gallery</h2>
            <div class="gallery">
                <img src="https://example.com/stephen-curry-photo1.jpg" alt="Stephen Curry 1">
                <img src="https://example.com/stephen-curry-photo2.jpg" alt="Stephen Curry 2">
                <img src="https://example.com/stephen-curry-photo3.jpg" alt="Stephen Curry 3">
                <!-- Add more photos if needed -->
            </div>
        </div>
    </div>
</body>
</html>
