<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Image with Internal CSS</title>
    <style>
        .image-link img {
            width: 200px;
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .image-link img:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <a href="https://www.wikipedia.org/" target="_blank" class="image-link">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Wikipedia-logo.png/800px-Wikipedia-logo.png" alt="Wikipedia Logo">
    </a>
</body>
</html>
