<!doctype html>
<html lang="fr"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Accueil - Cryptage Creatif</title> 
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"> 
  <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }

        header {
            background-color: #4A90E2;
            color: white;
            padding: 10px 0;
            font-size: 2em;
            position: relative;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .hero {
            height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }

        h1 {
            font-size: 4em;
            color: #4A90E2;
            animation: slide-in 2s ease-out forwards;
        }

        @keyframes slide-in {
            from {
                transform: translateY(-100px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .intro-text {
            margin-top: 20px;
            font-size: 1.5em;
            animation: fade-in 3s ease-out forwards;
        }

        @keyframes fade-in {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .cta {
            margin-top: 40px;
            font-size: 1.2em;
            padding: 15px 30px;
            background-color: #4A90E2;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            animation: bounce-in 3.5s ease-out forwards;
        }

        .cta:hover {
            background-color: #357ABD;
        }

        @keyframes bounce-in {
            from {
                transform: scale(0.5);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
    </style> 
 </head> 
 <body> 
  <header> 
   <div>
    Cryptage Créatif
   </div> 
  </header> 
  <section class="hero"> 
   <h1>Bienvenue dans l'univers du cryptage</h1> 
   <p class="intro-text">Chiffrez, partagez et protégez vos messages avec style.</p> <a href="chiffrer.html"> <button class="cta"><i class="fas fa-lock"></i> Chiffrez un message</button> </a> 
  </section> 
  <footer> 
   <p>© 2024 Cryptage Créatif. Tous droits réservés.</p> 
  </footer> &gt;
 </body>
</html># Criptage