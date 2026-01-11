# Love-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Raidha Sherin ❤️</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    height: 100vh;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #ff5f9e, #ffc371);
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    text-align: center;
}

.container {
    background: rgba(0,0,0,0.35);
    padding: 30px 20px;
    border-radius: 20px;
    width: 90%;
    max-width: 420px;
    box-shadow: 0 15px 40px rgba(0,0,0,0.4);
}

h1 {
    font-family: 'Great Vibes', cursive;
    font-size: 42px;
    margin-bottom: 10px;
}

p {
    font-size: 18px;
    line-height: 1.6;
}

.heart {
    font-size: 48px;
    animation: beat 1s infinite;
    margin: 15px 0;
}

@keyframes beat {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
}

.buttons {
    margin-top: 25px;
}

button {
    border: none;
    padding: 12px 25px;
    font-size: 18px;
    border-radius: 30px;
    cursor: pointer;
    margin: 8px;
}

.yes {
    background: #ff2e63;
    color: white;
}

.no {
    background: #555;
    color: white;
}

.yes:hover {
    background: #ff0844;
}

.no:hover {
    background: #333;
}

.footer {
    margin-top: 15px;
    font-size: 14px;
    opacity: 0.8;
}
</style>
</head>

<body>

<!-- Background Music -->
<audio autoplay loop>
    <source src="music.mp3" type="audio/mpeg">
</audio>

<div class="container">
    <h1>Raidha Sherin</h1>
    <div class="heart">❤️</div>

    <p>
        Every moment with you feels special.<br>
        Your smile lights up my world,<br>
        and your presence makes my heart feel at home.
    </p>

    <p>
        Raidha Sherin,<br>
        will you be my forever?
    </p>

    <div class="buttons">
        <button class="yes" onclick="yesAnswer()">Yes 💖</button>
        <button class="no" onclick="noAnswer()">No 😢</button>
    </div>

    <div class="footer">
        Made with love 💕
    </div>
</div>

<script>
function yesAnswer() {
    document.body.innerHTML = `
        <div style="
            height:100vh;
            display:flex;
            justify-content:center;
            align-items:center;
            flex-direction:column;
            background:linear-gradient(135deg,#ff0844,#ffb199);
            color:white;
            font-family:'Poppins',sans-serif;
            text-align:center;">
            <h1 style="font-family:'Great Vibes',cursive;font-size:50px;">
                She said YES ❤️
            </h1>
            <p style="font-size:20px;">
                This is the happiest moment of my life 💍
            </p>
        </div>
    `;
}

function noAnswer() {
    alert("Please think again 🥺💔");
}
</script>

</body>
</html>
