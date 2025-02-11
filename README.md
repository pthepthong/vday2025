# vday2025

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secret Love Letter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            padding: 50px;
        }
        .container {
            max-width: 500px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        #love-letter {
            display: none;
            margin-top: 20px;
            padding: 15px;
            background: #ffcccc;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        button {
            margin-top: 10px;
            padding: 10px;
            background: #ff4d4d;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background: #e60000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Do you love me? 💕</h2>
        <input type="text" id="answer" placeholder="Type your answer...">
        <button onclick="checkAnswer()">Submit</button>
        
        <div id="love-letter">
            <h3>My Dearest Love,</h3>
            <p>You make my world brighter every day. I am so grateful to have you in my life. Happy Valentine's Day! ❤️</p>
            <p>Forever yours,</p>
            <p>Panisara 💖</p>
        </div>
    </div>

    <script>
        function checkAnswer() {
            var answer = document.getElementById("answer").value.toLowerCase();
            if (answer === "yes") {
                document.getElementById("love-letter").style.display = "block";
            } else {
                alert("Oops! Try again, my love! 💕");
            }
        }
    </script>
</body>
</html>
