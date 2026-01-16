# Denim
Cloth brand
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    color: #ffffff;
    background-color: #000;
}

/* HERO SECTION */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)),
                url('../images/background.jpg') center/cover no-repeat;
    display: flex;
    flex-direction: column;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 25px 40px;
}

.logo {
    font-family: 'Anton', sans-serif;
    font-size: 2rem;
    letter-spacing: 2px;
}

.logo span {
    color: #e10600;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 25px;
}

.nav-links a {
    text-decoration: none;
    color: #ffffff;
    font-weight: 600;
}

.nav-links a:hover {
    color: #e10600;
}

/* HERO CONTENT */
.hero-content {
    margin: auto;
    text-align: center;
}

.hero-content h1 {
    font-family: 'Anton', sans-serif;
    font-size: 3.5rem;
    letter-spacing: 3px;
}

.hero-content p {
    margin: 15px 0 30px;
    color: #cccccc;
    font-size: 1.2rem;
}

.btn {
    padding: 12px 30px;
    background: #e10600;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

/* SECTIONS */
.section {
    padding: 80px 20px;
    text-align: center;
    max-width: 900px;
    margin: auto;
}

.section h2 {
    font-family: 'Anton', sans-serif;
    color: #e10600;
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.section p {
    font-size: 1.1rem;
    line-height: 1.8;
    color: #e0e0e0;
}

.dark {
    background: #0d0d0d;
}

.highlight {
    color: #e10600;
    font-weight: bold;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 25px;
    background: #000;
    color: #999;
    font-size: 0.9rem;
}

/* RESPONSIVE */
@media (max-width: 768px) {
    .nav-links {
        display: none;
    }

    .hero-content h1 {
        font-size: 2.5rem;
    }
}
