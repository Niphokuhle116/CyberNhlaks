# CyberNhlaks
Cybersecurity Portfolio
/* Directory structure for the assets folder */

cybersecurity-portfolio/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── images/
│   │   ├── hero-bg.jpg
│   │   ├── vulnerability.png
│   │   ├── siem.png
│   │   ├── pentest.png
│   │   └── ctf.png
│   └── icons/
│       ├── github.svg
│       ├── linkedin.svg
│       └── email.svg

/* Example styles.css */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0d1117;
    color: #c9d1d9;
    transition: background 0.3s, color 0.3s;
}
header {
    background: #161b22;
    padding: 1.5rem 2rem;
    text-align: center;
    border-bottom: 1px solid #30363d;
    position: sticky;
    top: 0;
    z-index: 100;
}
header h1 {
    margin: 0;
    font-size: 2rem;
    color: #58a6ff;
}
nav a {
    margin: 0 1rem;
    color: #58a6ff;
    text-decoration: none;
    transition: color 0.3s;
}
nav a:hover {
    color: #2ea043;
}
.hero {
    text-align: center;
    padding: 3rem 1rem;
    position: relative;
    background: url('../images/hero-bg.jpg') no-repeat center center/cover;
}
.hero h2, .hero p {
    animation: fadeIn 1s ease;
}
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
}
.card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 12px;
    padding: 1.5rem;
    transition: 0.3s ease, transform 0.3s ease;
}
.card:hover {
    border-color: #58a6ff;
    transform: translateY(-5px);
}
.button {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.75rem 1.5rem;
    background: #238636;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    transition: 0.3s;
}
.button:hover {
    background: #2ea043;
}
.skills-list li::before {
    content: '▹ ';
    color: #58a6ff;
    font-weight: bold;
}
@keyframes fadeIn {
    0% {opacity: 0; transform: translateY(20px);}
    100% {opacity: 1; transform: translateY(0);}
}
