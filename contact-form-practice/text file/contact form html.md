<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grow 1.0 | Contact Form</title>
    <!-- <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"> -->
    <link rel="stylesheet" href="contact_style.css">
    <script src="https://kit.fontawesome.com/3357889f5c.js" crossorigin="anonymous"></script>
</head>
<body>
    <main>
        <div class="wrapper">   
            <div class="left-container">
                <h2>Get a quote</h2>
                <p class="enonce">
                    Remplissez le formulaire et un membre de notre équipe <br> vous répondra dans les 24 heures.
                </p>

                <ul class="contact-info">
                    <li>
                        <i class="fa-solid fa-phone"></i>
                        <p>+0123 4567 8910</p>
                    </li>
                    <li>
                        <i class="fa-solid fa-envelope"></i>
                        <p><a href="mailto:hello@ecolegrow.tech">hello@ecolegrow.tech</a></p>
                    </li>
                    <li>
                        <i class="fa-solid fa-location-dot"></i>
                        <p>102 Street  2714 Don</p>
                    </li>
                </ul>

                <div class="social-icons-container">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-instagram"></i>
                </div>
            </div>
            <div class="right-container">
                <form action="" method="post">
                    <label for="name">votre nom:</label>
                    <div class="input-area">
                        <input type="text" id="name" name="nom_utilisateur"/>
                        <i class="fa-solid fa-user"></i>
                    </div>

                    <label for="mail">mail:</label>
                    <div class="input-area">
                        <input type="email" id="mail" name="email_utilisateur" />
                        <i class="fa-solid fa-envelope"></i>
                    </div>
    
                    <label for="msg">message:</label>
                    <textarea id="msg" name="message_utilisateur">Message</textarea>

                    <button type="submit">Envoyer</button>
                </form>
            </div>
        </div>
    </main>
</body>
</html>