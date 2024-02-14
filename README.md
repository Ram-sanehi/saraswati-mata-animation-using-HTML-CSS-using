# saraswati-mata-animation-using-HTML-CSS-using

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Saraswati Mata Animation</title>
        <style>
            body {
                background-color: #f7e4d4;
            }

            .container {
                width: 300px;
                height: 400px;
                margin: 50px auto;
                position: relative;
            }

            .saraswati {
                width: 200px;
                position: absolute;
                left: 50%;
                bottom: 0;
                transform: translateX(-50%);
                animation: play-veena 2s infinite linear;
            }

            @keyframes play-veena {
                0% {
                    transform: translateX(-50%) rotate(-10deg);
                }
                50% {
                    transform: translateX(-50%) rotate(0deg);
                }
                100% {
                    transform: translateX(-50%) rotate(-10deg);
                }
            }
        </style>
    </head>
    <body>
        <div class="container">
            <img src="saraswati.png" alt="Saraswati Mata" class="saraswati">
        </div>
    </body>
    </html>
  
