<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Introduction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
        }
        .container {
            text-align: center;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #0056b3;
        }
        #intro {
            margin-top: 20px;
            font-size: 18px;
            color: #333;
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi there!</h1>
        <p>Want to know more about me?</p>
        <button onclick="revealIntro()">Click to Introduce Myself</button>
        <div id="intro">
            <p>Hello, I'm Shrijani Sai Gandham. I am a part of Prime Edge, actively involved in outreach activities, and working on exciting projects in technology, including AI and blockchain. I love learning new things and participating in various events. Nice to meet you!</p>
        </div>
    </div>

    <script>
        function revealIntro() {
            document.getElementById('intro').style.display = 'block';
        }
    </script>
</body>
</html>
