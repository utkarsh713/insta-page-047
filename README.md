<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Utkarsh Barnwal - Influencer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="profile.jpg" alt="Utkarsh Barnwal">
            <h6>Utkarsh Barnwal</h6>
            <p class="tagline">Tech Influencer | Web Developer | Content Creator</p>
            <a href="https://instagram.com/utkarsh0.24" target="_blank" class="insta-btn">
                <i class="fab fa-instagram"></i> Follow @utkarsh0.24
            </a>
        </div>
    </div>
</body>
</html>

<!-- styles.css -->
<style>
    body {
        background-color: #121212;
        color: white;
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
    }

    .container {
        text-align: center;
        background: #1e1e1e;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
    }

    .profile img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        border: 3px solid #ff007f;
        margin-bottom: 10px;
    }

    h6 {
        font-size: 18px;
        color: #ff007f;
        margin: 0;
    }

    .tagline {
        font-size: 14px;
        color: #bbb;
        margin: 5px 0;
    }

    .insta-btn {
        text-decoration: none;
        color: white;
        background: #ff007f;
        padding: 8px 16px;
        border-radius: 5px;
        display: inline-block;
        margin-top: 10px;
        transition: 0.3s;
    }

    .insta-btn:hover {
        background: #e60073;
    }
</style>

<!-- script.js -->
<script>
    document.addEventListener("DOMContentLoaded", function () {
        const instaBtn = document.querySelector(".insta-btn");

        instaBtn.addEventListener("mouseover", function () {
            instaBtn.style.transform = "scale(1.1)";
        });

        instaBtn.addEventListener("mouseout", function () {
            instaBtn.style.transform = "scale(1)";
        });
    });
</script>
