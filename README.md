# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
            flex-direction: column; /* Stack elements vertically */
            margin: 0; /* Remove default margin */
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #ff69b4; /* Hot pink */
            color: white;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #ff1493; /* Deep pink */
        }
        #message {
            margin-top: 20px;
            font-size: 48px; /* Increased font size */
            color: #333;
            display: none; /* Initially hidden */
            text-align: center; /* Center the text */
        }
    </style>
</head>
<body>

    <button id="loveButton">Click Me!</button>
    <div id="message">I love you!</div>

    <script>
        document.getElementById('loveButton').addEventListener('click', function() {
            document.getElementById('message').style.display = 'block';
        });
    </script>

</body>
</html>
