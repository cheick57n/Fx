<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>7Seven-Travail | E-Visa</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: #0c1b2a;
    overflow-x: hidden;
}

/* Header bleu 3D glow */
header {
    text-align: center;
    padding: 60px 20px 150px;
    position: relative;
    overflow: hidden;
    background: linear-gradient(135deg,#1a2a6c,#155ab6);
}
header h1 {
    font-size: 3em;
    font-weight: 900;
    color: #fff;
    text-shadow:0 0 10px #fff,0 0 20px #4fc3f7,0 0 30px #1a73e8;
    animation:glowPulse 2s infinite alternate;
    margin:0;
}
header p {
    margin-top:15px;
    font-size:1.3em;
    text-shadow:1px 1px 3px rgba(0,0,0,0.5);
}

/* Glow animation */
@keyframes glowPulse{
    0%{text-shadow:0 0 10px #fff,0 0 20px #4fc3f7,0 0 30px #1a73e8;}
    100%{text-shadow:0 0 20px #fff,0 0 40px #4fc3f7,0 0 60px #1a2a6c;}
}

/* Avion et promo texte */
.airplane{position:absolute;top:45%;left:-60px;font-size:2.2em;color:#ffec00;animation:flyCurve 12s linear infinite alternate;z-index:10;}
@keyframes flyCurve{
    0%{left:-60px;transform:translateY(0) rotate(0deg);}
    25%{transform:translateY(-15px) rotate(10deg);}
    50%{left:80%;transform:translateY(0) rotate(0deg);}
    75%{transform:translateY(15px) rotate(-10deg);}
    100%{left:-60px;transform:translateY(0) rotate(0deg);}
}

/* Texte promo animé sous l’avion */
.promo-text{
    position:absolute;top:60%;width:100%;text-align:center;font-size:1.5em;font-weight:bold;color:#ffeb3b;
    text-shadow:2px 2px 6px rgba(0,0,0,0.7);
    animation:textSlide 12s linear infinite alternate;
    z-index:5;
}
@keyframes textSlide{
    0%{transform:translateX(-100%);}
    50%{transform:translateX(10%);}
    100%{transform:translateX(-100%);}
}

/* Textes supplémentaires animés */
.extra-text{
    position:absolute;
    top:68%;
    width:100%;
    text-align:center;
    font-size:1.2em;
    font-weight:bold;
    color:#00ffea;
    text-shadow:1px 1px 5px rgba(0,0,0,0.7);
    animation:fadeText 9s linear infinite;
    z-index:5;
}
@keyframes fadeText{
    0%,100%{opacity:0;}
    10%{opacity:1; content:"Traitement rapide en 24h !";}
    35%{opacity:0; content:"Visa touristique, affaires ou études";}
    60%{opacity:1; content:"Support WhatsApp instantané";}
}

/* Section formulaire avec background Canva */
.background-section{
    position:relative;
    background-image:url('https://www.canva.com/design/DAGxYbSZXJY/oTLvvfWlr8H_vx_wLnu5Qw/view?embed');
    background-size:cover;
    background-position:center;
    padding:120px 20px;
}

/* Formulaire bleu style “fou” */
.form-container{
    max-width:750px;
    margin:-50px auto 50px;
    padding:50px;
    border-radius:25px;
    position:relative;
    z-index:2;
    perspective:1000px;
    animation:float3D 6s ease-in-out infinite alternate;
    background:rgba(0,50,150,0.85);
    box-shadow:0 0 50px #1a73e8,0 0 80px #4fc3f7,0 0 120px #1a2a6c inset;
    backdrop-filter: blur(6px);
}

@keyframes float3D{
    0%{transform:rotateX(2deg) rotateY(-2deg) translateY(0px);}
    50%{transform:rotateX(-2deg) rotateY(2deg) translateY(-10px);}
    100%{transform:rotateX(2deg) rotateY(-2deg) translateY(0px);}
}

.form-container h2{
    text-align:center;
    color:#ffeb3b;
    margin-bottom:30px;
    text-shadow:0 0 5px #fff,0 0 10px #4fc3f7;
}

/* Champs 3D */
form{display:flex;flex-direction:column;gap:18px;}
.form-group{position:relative;}
.form-group i{position:absolute;left:15px;top:50%;transform:translateY(-50%);color:#ffeb3b;}
input,select{
    width:100%;
    padding:14px 14px 14px 45px;
    border-radius:15px;
    border:1px solid #4fc3f7;
    outline:none;
    font-size:1em;
    box-shadow:0 5px 25px rgba(0,0,0,0.25),0 0 15px #4fc3f7 inset;
    transition:all 0.4s ease;
    background-color:rgba(255,255,255,0.1);
    color:#fff;
}
input:focus,select:focus{transform:translateY(-2px) scale(1.02);box-shadow:0 15px 45px rgba(0,0,0,0.35),0 0 25px #4fc3f7 inset;border-color:#ffeb3b;}

button{
    padding:16px;
    background-color:#ffeb3b;
    color:#0c1b2a;
    font-size:1.2em;
    border:none;
    border-radius:20px;
    cursor:pointer;
    transition:all 0.4s ease;
    box-shadow:0 15px 45px rgba(0,0,0,0.35);
}
button:hover{background-color:#fff200;transform:translateY(-2px) scale(1.05);box-shadow:0 20px 50px rgba(0,0,0,0.45);}

/* Footer */
footer{text-align:center;padding:20px 0;background:rgba(255,255,255,0.85);font-size:0.95em;color:#555;margin-top:30px;}
</style>
</head>
<body>

<header>
<h1>7Seven-Travail</h1>
<p>Votre e-visa, simple et rapide</p>
<div class="airplane"><i class="fas fa-plane"></i></div>
<div class="promo-text">-50% de réduction sur chaque visa !</div>
<div class="extra-text">Traitement rapide en 24h !</div>
</header>

<section class="background-section">
<div class="form-container">
<h2>Demande de e-Visa</h2>
<form action="mailto:Africanewtradelogistic@antl.com" method="POST" enctype="text/plain">
<div class="form-group"><i class="fas fa-user"></i><input type="text" name="Nom" placeholder="Nom" required></div>
<div class="form-group"><i class="fas fa-user"></i><input type="text" name="Prénom" placeholder="Prénom" required></div>
<div class="form-group"><i class="fas fa-calendar"></i><input type="date" name="Date de naissance" required></div>
<div class="form-group"><i class="fas fa-flag"></i><input type="text" name="Nationalité" placeholder="Nationalité" required></div>
<div class="form-group"><i class="fas fa-globe"></i>
<select name="Pays de visa" required>
<option value="">Sélectionnez le pays du visa</option>
<option value="Dubai">Dubaï 🇦🇪</option>
<option value="Qatar">Qatar 🇶🇦</option>
<option value="Albanie">Albanie 🇦🇱</option>
<option value="Moldavie">Moldavie 🇲🇩</option>
<option value="Australie">Australie 🇦🇺</option>
</select>
</div>
<div class="form-group"><i class="fas fa-passport"></i>
<select name="Type de visa" required>
<option value="">Type de visa</option>
<option value="tourisme">Tourisme</option>
<option value="affaires">Affaires</option>
<option value="études">Études</option>
</select></div>
<div class="form-group"><i class="fas fa-plane"></i><input type="text" name="Dates de voyage" placeholder="Ex: du 01/10/2025 au 15/10/2025" required></div>
<div class="form-group"><i class="fab fa-whatsapp"></i><input type="text" name="WhatsApp" placeholder="Votre numéro WhatsApp" required></div>
<div class="form-group"><i class="fas fa-file-upload"></i><input type="file" name="Passeport" accept=".pdf,.jpg,.png" required></div>
<button type="submit">Soumettre ma demande</button>
</form>
</div>
</section>

<footer>
Contactez-nous : <strong>Africanewtradelogistic@antl.com</strong><br>
© 2025 7Seven-Travail | Tous droits réservés
</footer>

</body>
</html>
