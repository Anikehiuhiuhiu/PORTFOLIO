//HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Write a brief introduction about yourself.</p>
    </section>
    
    <section id="projects">
        <h2>My Projects</h2>
        <!-- Add project details here -->
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Provide your contact information or a contact form.</p>
    </section>
    
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>


//CSS


 /* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}
// CSS 
@media (max-width: 600px) {
    nav ul {
        text-align: center;
    }

    nav ul li {
        display: block;
        margin: 10px 0;
    }
}



