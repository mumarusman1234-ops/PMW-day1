<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Space</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 16px;
            padding: 40px;
            max-width: 500px;
            width: 100%;
            text-align: center;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: linear-gradient(45deg, #00c6ff, #0072ff);
            margin: 0 auto 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2.5rem;
            font-weight: bold;
        }

        h1 {
            font-size: 2rem;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        p {
            color: #b0bec5;
            font-size: 1rem;
            margin-bottom: 30px;
            line-height: 1.5;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            background: rgba(255, 255, 255, 0.1);
            color: #ffffff;
            text-decoration: none;
            padding: 12px 20px;
            border-radius: 8px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .btn:hover {
            background: #ffffff;
            color: #0f2027;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,198,255,0.4);
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="profile-img">👤</div>
        <h1>Welcome to My Space</h1>
        <p>Student, tech enthusiast, and creator. Exploring web development, building cool interfaces, and documenting the journey one day at a time.</p>
        
        <div class="links">
            <a href="https://github.com" target="_blank" class="btn">GitHub Profile</a>
            <a href="mailto:your-email@example.com" class="btn">Get In Touch</a>
        </div>
    </div>

</body>
</html>
