<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escape Room</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Enter the Code to Proceed</h1>
        <form id="codeForm">
            <input type="password" id="password" placeholder="Enter Code" />
            <button type="submit">Submit</button>
        </form>
        <p id="feedback"></p> <!-- To show feedback on incorrect tries -->
        <!-- Hidden jumpscare -->
        <div id="jumpscare" class="hidden">
            <img src="scary-image.jpeg" alt="Scary" />
            <audio id="screamSound" src="five-nights-at-freddys-full-scream-sound_2.mp3"></audio>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
