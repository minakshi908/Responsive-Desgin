-------- index.html ---------

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Responsive Design</title>
</head>
<body>
    <header>
        <h1>My Responsive Page</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#section1">Section 1</a></li>
            <li><a href="#section2">Section 2</a></li>
            <li><a href="#section3">Section 3</a></li>
        </ul>
    </nav>
    <main>
        <section id="section1">
            <h2>Section 1</h2>
            <p>Content for section 1.</p>
        </section>
        <section id="section2">
            <h2>Section 2</h2>
            <p>Content for section 2.</p>
        </section>
        <section id="section3">
            <h2>Section 3</h2>
            <p>Content for section 3.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Responsive Page</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
---------  style.css -----------

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1rem;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: #333;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
    padding: 20px;
    border: 1px solid #ccc;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #4CAF50;
    color: white;
}

/* Responsive Styles */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }
}

@media (max-width: 480px) {
    header, footer {
        font-size: 0.8rem;
    }
}
 /* Basic Styling */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 1em 0;
    }

    section {
      padding: 20px;
    }

    /* Responsive Layout - Adjust breakpoints as needed */
    @media screen and (min-width: 600px) {
      section {
        /* For tablets and larger screens */
        float: left;
        width: 50%;
      }
    }

    @media screen and (min-width: 900px) {
      section {
        /* For larger desktops */
        width: 33.33%;
      }
    }
  
-------  script.js ---------
 
 document.addEventListener('DOMContentLoaded', () => {
    // Example: Add functionality here if needed
});
