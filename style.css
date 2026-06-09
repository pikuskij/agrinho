/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

/* Cores e variáveis */
:root {
    --primary-color: #1e4620;
    --secondary-color: #4caf50;
    --text-color: #f0f0f0;
    --bg-color: #ffffff;
}

/* Dark Mode */
body.dark-mode {
    background-color: #121212;
    color: #e0e0e0;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
    background-color: var(--primary-color);
    color: var(--text-color);
    position: sticky;
    top: 0;
    z-index: 1000;
}

header .logo {
    font-size: 1.8rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a, nav ul li button {
    color: var(--text-color);
    text-decoration: none;
    font-weight: bold;
    cursor: pointer;
    transition: color 0.3s;
}

nav ul li a:hover, nav ul li button:hover {
    color: var(--secondary-color);
}

/* Menu mobile */
.menu-toggle {
    display: none;
    font-size: 2rem;
    cursor: pointer;
}

/* Hero Section */
.hero {
    height: 90vh;
    background: linear-gradient(rgba(30,70,32,0.8), rgba(30,70,32,0.8)), url('assets/images/fazenda1.jpg') center/cover no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: var(--text-color);
    animation: fadeIn 2s ease-in;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.5rem;
    margin-bottom: 30px;
}

.cta-btn {
    padding: 10px 25px;
    border: none;
    background-color: var(--secondary-color);
    color: var(--text-color);
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: transform 0.3s;
}

.cta-btn:hover {
    transform: scale(1.1);
}

/* Seções de informação */
.info-section, .gallery-section {
    padding: 60px 20px;
    text-align: center;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.gallery img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0px 8px 20px rgba(0,0,0,0.3);
}

/* Footer */
footer {
    background-color: var(--primary-color);
    color: var(--text-color);
    text-align: center;
    padding: 20px;
}

/* Animações */
@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
}

/* Responsividade */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        position: absolute;
        top: 70px;
        right: -100%;
        background-color: var(--primary-color);
        width: 200px;
        transition: right 0.3s;
    }

    nav ul.active {
        right: 0;
    }

    .menu-toggle {
        display: block;
    }
}
