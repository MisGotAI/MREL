# MREL
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Présentation du MREL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #87CEEB; /* Bleu ciel */
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #FFD700; /* Jaune */
            padding: 20px;
            text-align: center;
            width: 100%;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            padding: 20px;
            text-align: center;
            max-width: 800px;
            width: 100%;
        }
        .intro, .team, .video, .feedback {
            margin-bottom: 40px;
        }
        .team img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
            object-fit: cover;
            margin: 10px;
        }
        .team p {
            margin: 5px 0;
            font-size: 1.2em;
        }
        .video iframe {
            width: 100%;
            height: 315px;
            border: none;
        }
        .feedback label {
            display: block;
            margin-bottom: 10px;
            font-size: 1.1em;
        }
        .feedback button {
            padding: 10px 20px;
            background-color: #FFD700;
            color: #333;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            margin-top: 10px;
        }
        .feedback button:hover {
            background-color: #FFA500;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue au MREL</h1>
    </header>
    <div class="container">
        <div class="intro">
            <h2>Introduction</h2>
            <p>Le MREL est une initiative visant à promouvoir l'innovation et la collaboration dans le domaine de la recherche. Nous nous efforçons de créer un environnement où les idées peuvent fleurir et les projets peuvent prospérer.</p>
        </div>
        <div class="team">
            <h2>Notre Équipe</h2>
            <div>
                <img src="https://via.placeholder.com/100" alt="Wendy">
                <p>Wendy</p>
            </div>
            <div>
                <img src="data:image/jpeg;base64,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" alt="Pierre">
                <p>Pierre</p>
            </div>
            <div>
                <img src="https://via.placeholder.com/100" alt="Marco">
                <p>Marco</p>
            </div>
        </div>
        <div class="video">
            <h2>Regardez notre vidéo</h2>
            <iframe src="https://www.youtube.com/embed/2C53gDGkmB4" allowfullscreen></iframe>
        </div>
        <div class="feedback">
            <h2>Avez-vous compris ?</h2>
            <label>
                <input type="radio" name="comprehension" value="oui"> Oui
            </label>
            <label>
                <input type="radio" name="comprehension" value="non"> Non
            </label>
            <button onclick="submitFeedback()">Soumettre</button>
        </div>
    </div>

    <script>
        function submitFeedback() {
            const feedback = document.querySelector('input[name="comprehension"]:checked');
            if (feedback) {
                if (feedback.value === 'oui') {
                    alert("Espèce de gros mytho mdrrr t'as rien compris à ce que t'as fais et Claire le sait très bien");
                } else {
                    alert("C'est bien ce que je me disais, t'es complètement con");
                }
            } else {
                alert('Veuillez sélectionner une option.');
            }
        }
    </script>
</body>
</html>
