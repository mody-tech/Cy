<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Quotes Hub</title>
    <style>
        /* Dark mode aesthetic theme */
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }

        .header {
            background: linear-gradient(135deg, #8b0000, #4a0000);
            color: #ffffff;
            padding: 30px;
            font-size: 28px;
            font-weight: bold;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
            letter-spacing: 1px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        /* Quote Layout Display Card */
        .quote-card {
            background-color: #161b22;
            border-left: 5px solid #ff4500;
            padding: 20px;
            margin: 15px 0;
            border-radius: 4px;
            text-align: left;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }

        .quote-text {
            font-size: 18px;
            font-style: italic;
            line-height: 1.5;
            color: #f0f6fc;
        }

        .quote-author {
            margin-top: 10px;
            font-size: 14px;
            color: #ff4500;
            font-weight: bold;
            text-transform: uppercase;
        }

        /* Media Assets Handling */
        .media-section {
            background-color: #161b22;
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
            border: 1px solid #21262d;
        }

        h2 {
            color: #f0f6fc;
            border-bottom: 2px solid #21262d;
            padding-bottom: 10px;
        }

        /* Permanent Cloud-Linked Image Styling */
        .anime-img {
            max-width: 100%;
            height: auto;
            border-radius: 6px;
            border: 2px solid #30363d;
            margin: 15px 0 25px 0;
        }

        /* Live video wrapper */
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            border-radius: 6px;
            border: 2px solid #30363d;
        }

        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>

    <div class="header">
        🔥 ANIME QUOTE REALM 🔥<br>
        <span style="font-size: 14px; font-weight: normal; color: #f0f6fc80;">Beyond the Limits</span>
    </div>

    <div class="container">
        
        <!-- Quotes Section -->
        <div class="quote-card">
            <div class="quote-text">"Set your heart ablaze. Go beyond your limits!"</div>
            <div class="quote-author">— Kyojuro Rengoku (Demon Slayer)</div>
        </div>

        <div class="quote-card">
            <div class="quote-text">"Push through the pain. Giving up hurts more."</div>
            <div class="quote-author">— Vegeta (Dragon Ball Z)</div>
        </div>

        <!-- Live Media section -->
        <div class="media-section">
            <h2>Featured Gallery</h2>
            
            <!-- PERMANENT CLOUD-HOSTED IMAGE LINK -->
            <img class="anime-img" src="https://wallpaperaccess.com/full/3040357.png" alt="Aesthetic Anime Art Scene">

            <h2>Featured AMV / Video Clip</h2>
            <!-- Live Streaming Video Embed Frame Layout -->
            <div class="video-wrapper">
                <iframe 
                    src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                    allowfullscreen>
                </iframe>
            </div>
        </div>

    </div>

</body>
</html>
