<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muskan, Will You Marry Me?</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/your-background-image.jpg'); /* Replace with your image URL */
            background-size: cover;
            font-family: 'Arial', sans-serif;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            position: relative;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        p {
            font-size: 1.5rem;
            margin-bottom: 30px;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
        }

        .button {
            padding: 15px 30px;
            font-size: 1.2rem;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            background-color: #e6005c;
            color: white;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #ff4e50;
        }

        .heart {
            font-size: 4rem;
            animation: pulse 1.5s infinite;
            margin: 20px 0;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <h1>Muskan, Will You Marry Me?</h1>
    <div class="heart">❤️</div>
    <p>From the moment I met you, my heart knew you were the one. Let's create a beautiful future together.</p>
    <button class="button" onclick="alert('YAY! Muskan said YES!')">Yes!</button>
    <button class="button" onclick="alert('No? I’ll keep trying, Muskan!')">No</button>
</body>
</html>
