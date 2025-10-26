elektro-dm-website/
│
├── index.html
├── style.css
│
└── images/
    ├── ![depositphotos_186166888-stock-photo-different-electrical-tools-on-wooden](https://github.com/user-attachments/assets/03546e21-11ce-41cf-9a90-caab2ff0acb5)

    ├── ![electrician-working-on-electrical-panel](https://github.com/user-attachments/assets/34cc6af8-9e87-44e8-b8cc-755442973f12)

    ├── ![man-working-on-electrical-panel](https://github.com/user-attachments/assets/3d23bdb3-9e61-4c10-bce8-285c534003cf)

    ├── ![slika-2517920-5e26192442cf2-velika](https://github.com/user-attachments/assets/d162bb0b-911f-4461-87a0-feded0f7e4ca)

    ├── ![69-3-m](https://github.com/user-attachments/assets/57f1cb76-74a0-4ce1-8850-a3028e27d796)

    └── ![installing-or-repairing-electrical-panel-2025-04-01-18-31-02-utc-1](https://github.com/user-attachments/assets/5a401b7e-4719-489a-9111-20a062fb45c1)

<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elektro DM - Ispitivanje i ispravljanje električnih instalacija</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <img src="images/logo.png" alt="Elektro DM Logo" class="logo">
    <h1>Elektro DM</h1>
    <p class="slogan">Sigurnost i preciznost u svakoj instalaciji</p>
</header>

<nav>
    <a href="#usluge">Usluge</a>
    <a href="#o-nama">O nama</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<section class="banner">
    <img src="images/banner.jpg" alt="Električne instalacije">
</section>

<main>
    <section id="usluge">
        <h2>Naše usluge</h2>
        <div class="services">
            <img src="images/alat.jpg" alt="Elektro alat">
            <ul>
                <li>Ispitivanje ispravnosti električnih instalacija</li>
                <li>Mjerenje uzemljenja i zaštitnih vodiča</li>
                <li>Termovizijsko snimanje električnih ormara</li>
                <li>Ispravljanje neispravnih instalacija</li>
                <li>Izdavanje izvješća i certifikata o ispravnosti</li>
            </ul>
        </div>
    </section>

    <section id="o-nama">
        <h2>O nama</h2>
        <div class="about">
            <img src="images/elektricar.jpg" alt="Električar na radu">
            <p>Elektro DM pruža profesionalne usluge ispitivanja i održavanja električnih instalacija.  
            Naš tim koristi suvremene instrumente i poštuje sve sigurnosne norme prema HRN i IEC standardima.</p>
        </div>
    </section>

    <section id="kontakt" class="kontakt">
        <h2>Kontaktirajte nas</h2>
        <div class="contact-info">
            <p><strong>Telefon:</strong> 098 467 885</p>
            <p><strong>E-mail:</strong> <a href="mailto:dalibormaravic79@gmail.com">dalibormaravic79@gmail.com</a></p>
        </div>

        <form>
            <label for="ime">Ime i prezime:</label>
            <input type="text" id="ime" name="ime" placeholder="Vaše ime" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" placeholder="dalibormaravic79@gmail.com" required>

            <label for="poruka">Poruka:</label>
            <textarea id="poruka" name="poruka" placeholder="Vaša poruka..." required></textarea>

            <button type="submit">Pošalji</button>
        </form>
    </section>
</main>

<footer>
    <p>&copy; 2025 Elektro DM | Sva prava pridržana</p>
</footer>

</body>
</html>
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f5f7fa;
    color: #333;
}

header {
    background-color: #004aad;
    color: white;
    text-align: center;
    padding: 30px 10px;
}

header .logo {
    width: 90px;
    margin-bottom: 10px;
}

.slogan {
    font-style: italic;
    color: #ff3b3b;
}

nav {
    background-color: #002f6c;
    display: flex;
    justify-content: center;
    padding: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 20px;
    font-weight: bold;
}

nav a:hover {
    color: #ff3b3b;
}

.banner img {
    width: 100%;
    max-height: 400px;
    object-fit: cover;
}

main {
    max-width: 1100px;
    margin: 40px auto;
    background: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

h2 {
    color: #004aad;
    border-left: 5px solid #ff3b3b;
    padding-left: 10px;
}

.services, .about {
    display: flex;
    align-items: center;
    gap: 20px;
}

.services img, .about img {
    width: 45%;
    border-radius: 5px;
}

.kontakt {
    background-color: #e8f0ff;
    padding: 20px;
    border-left: 5px solid #004aad;
}

form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 20px;
}

input, textarea {
    padding: 10px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    background-color: #004aad;
    color: white;
    padding: 12px;
    font-size: 1rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #ff3b3b;
}

footer {
    background-color: #004aad;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}
