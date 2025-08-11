`html
<!DOCTYPE html>
<html>
<head>
  <title>Hackered Dackered</title>
  <style>
    body {
      background-color: black;
      color: lime;
      font-family: 'Courier New', monospace;
      text-align: center;
      padding-top: 20%;
    }
    .blink {
      animation: blink 0.5s step-start infinite;
      font-size: 2em;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="blink">YOU'VE BEEN HACKERED DACKERED</div>
  <audio autoplay>
    <source src="https://www.myinstants.com/media/sounds/windows-xp-error.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
`