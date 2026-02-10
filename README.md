# MalcolmNZ
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXPLOSION d'Anniversaire pour MALCOLM !</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap');

        body {
            background-color: #000;
            color: white;
            font-family: 'Luckiest Guy', cursive;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            text-align: center;
            overflow: hidden; /* Cache les débordements des images */
            position: relative;
        }

        /* Fond énergétique qui pulse */
        .background-energy {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at center, rgba(255,140,0,0.3) 0%, rgba(0,0,0,1) 70%);
            animation: energyPulse 3s infinite alternate;
            z-index: 0;
        }

        @keyframes energyPulse {
            0% { transform: scale(1); opacity: 0.8; }
            100% { transform: scale(1.5); opacity: 0.5; }
        }

        /* Conteneur principal du message */
        .main-content {
            position: relative;
            z-index: 10;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7); /* Fond légèrement transparent pour le texte */
            border-radius: 15px;
            box-shadow: 0 0 30px rgba(255,165,0,0.8);
            max-width: 90%;
            border: 3px solid #ffcc00;
        }

        h1 {
            color: #ffcc00; /* Jaune Super Saiyan */
            font-size: clamp(2rem, 8vw, 4rem); /* Taille adaptative */
            text-shadow: 4px 4px 0 #ff8c00, 7px 7px 0 #0047ab;
            margin-bottom: 20px;
            letter-spacing: 3px;
            animation: textGlow 1.5s infinite alternate;
        }

        @keyframes textGlow {
            from { text-shadow: 4px 4px 0 #ff8c00, 7px 7px 0 #0047ab; }
            to { text-shadow: 4px 4px 15px #ffcc00, 7px 7px 25px #ff8c00; }
        }

        .message {
            font-size: clamp(1rem, 4vw, 1.8rem); /* Taille adaptative */
            line-height: 1.4;
            color: #f1f1f1;
            margin: 20px auto;
        }

        .heart-icon {
            font-size: clamp(1.5rem, 5vw, 3rem);
            color: #ff004f;
            display: block;
            margin-top: 20px;
            animation: beat 0.8s infinite;
        }

        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }

        /* Gokus qui apparaissent partout */
        .goku-blast {
            position: absolute;
            width: 100px; /* Taille des petits Goku */
            height: auto;
            opacity: 0;
            animation: flyInGoku 8s infinite ease-out;
            filter: drop-shadow(0 0 10px #ffcc00);
            z-index: 5;
        }

        /* Positions et délais des Goku */
        .goku-blast:nth-child(1) { top: 10%; left: 5%; animation-delay: 0s; }
        .goku-blast:nth-child(2) { bottom: 15%; right: 10%; animation-delay: 1s; }
        .goku-blast:nth-child(3) { top: 5%; right: 20%; animation-delay: 2s; transform: scaleX(-1); } /* Reflet */
        .goku-blast:nth-child(4) { bottom: 5%; left: 25%; animation-delay: 3s; }
        .goku-blast:nth-child(5) { top: 25%; left: 30%; animation-delay: 4s; transform: scale(0.8); }
        .goku-blast:nth-child(6) { bottom: 20%; right: 30%; animation-delay: 5s; transform: scaleX(-1) scale(0.9); }

        @keyframes flyInGoku {
            0% { opacity: 0; transform: scale(0.5) rotate(0deg); }
            10% { opacity: 1; transform: scale(1) rotate(10deg); }
            20% { opacity: 0; transform: scale(1.2) rotate(20deg); }
            100% { opacity: 0; }
        }
    </style>
</head>
<body>

    <div class="background-energy"></div>

    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ2OG82d3U3OWdxeWV1dXJ5Z2J2OG82d3U3OWdxeWV1dXJ5Z2FwaXJhYnQ1biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bLy8c3EThKm4WCDCcx/giphy.gif" alt="Goku Blast" class="goku-blast">

    <div class="main-content">
        <h1>Joyeux Anniversaire MALCOLM !</h1>
        <p class="message">
            Merci d'être toi, <br>
            je t'aime de tout mon cœur ! <br>
            Profite à fond de ta journée !
        </p>
        <span class="heart-icon">❤️</span>
    </div>

</body>
</html>
