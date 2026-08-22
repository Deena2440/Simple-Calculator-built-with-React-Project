# Ex04 Simple Calculator - React Project
## Date:22-8-2026
## Name : DEENATHAYALAN K
## Reg No :21224040058

## AIM
To  develop a Simple Calculator using React.js with clean and responsive design, ensuring a smooth user experience across different screen sizes.

## ALGORITHM
### STEP 1
Create a React App.

### STEP 2
Open a terminal and run:
  <ul><li>npx create-react-app simple-calculator</li>
  <li>cd simple-calculator</li>
  <li>npm start</li></ul>

### STEP 3
Inside the src/ folder, create a new file Calculator.js and define the basic structure.

### STEP 4
Plan the UI: Display screen, number buttons (0-9), operators (+, -, *, /), clear (C), and equal (=).

### STEP 5
Create a new file Calculator.css in src/ and add the styling.

### STEP 6
Open src/App.js and modify it.

### STEP 7
Start the development server.
  npm start

### STEP 8
Open http://localhost:3000/ in the browser.

### STEP 9
Test the calculator by entering numbers and operations.

### STEP 10
Fix styling issues and refine content placement.

### STEP 11
Deploy the website.

### STEP 12
Upload to GitHub Pages for free hosting.

## PROGRAM
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShopEasy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>ShopEasy</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home" class="hero">
    <h2>Welcome to ShopEasy</h2>
    <p>Quality Products at Affordable Prices</p>
    <a href="#products" class="btn">Shop Now</a>
</section>

<section id="products">
    <h2>Our Products</h2>

    <div class="products">

        <div class="card">
            <div class="icon">💻</div>
            <h3>Laptop</h3>
            <p>Powerful laptop for work and entertainment.</p>
            <h4>₹55,000</h4>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <div class="icon">📱</div>
            <h3>Smartphone</h3>
            <p>Latest smartphone with advanced features.</p>
            <h4>₹25,000</h4>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <div class="icon">🎧</div>
            <h3>Headphones</h3>
            <p>Wireless headphones with excellent sound.</p>
            <h4>₹3,500</h4>
            <button>Buy Now</button>
        </div>

    </div>
</section>

<section id="about" class="about">
    <h2>About Us</h2>
    <p>
        ShopEasy provides quality electronic products
        at affordable prices with excellent customer service.
    </p>
</section>

<section id="contact">
    <h2>Contact Us</h2>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>© 2026 ShopEasy. All Rights Reserved.</p>
</footer>

</body>
</html>
```
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f4f4;
    color: #333;
}

header {
    background: #1e293b;
    color: white;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 28px;
}

nav {
    display: flex;
    gap: 25px;
}

nav a {
    color: white;
    text-decoration: none;
}

nav a:hover {
    color: #38bdf8;
}

.hero {
    height: 450px;
    background: linear-gradient(135deg, #2563eb, #0f172a);
    color: white;
    text-align: center;
    padding-top: 150px;
}

.hero h2 {
    font-size: 45px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 20px;
    margin-bottom: 30px;
}

.btn {
    background: white;
    color: #2563eb;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 60px 8%;
    text-align: center;
}

section h2 {
    font-size: 32px;
    margin-bottom: 30px;
}

.products {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.card {
    background: white;
    width: 280px;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 5px 15px #ccc;
}

.card:hover {
    transform: translateY(-5px);
}

.icon {
    font-size: 70px;
}

.card h3 {
    margin: 15px 0 10px;
}

.card p {
    color: #666;
    margin-bottom: 15px;
}

.card h4 {
    font-size: 20px;
    margin-bottom: 15px;
}

button {
    background: #2563eb;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #1d4ed8;
}

.about {
    background: white;
}

.about p {
    max-width: 700px;
    margin: auto;
    line-height: 1.7;
    font-size: 18px;
}

form {
    max-width: 600px;
    margin: auto;
}

input,
textarea {
    width: 100%;
    padding: 14px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

textarea {
    height: 120px;
}

footer {
    background: #1e293b;
    color: white;
    text-align: center;
    padding: 20px;
}

@media (max-width: 768px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav {
        flex-wrap: wrap;
        justify-content: center;
    }

    .hero h2 {
        font-size: 32px;
    }
}
```

## OUTPUT
<img width="1901" height="1073" alt="image" src="https://github.com/user-attachments/assets/05c150b6-52a2-405f-b791-05acc333a089" />
<img width="1907" height="728" alt="image" src="https://github.com/user-attachments/assets/93f3355b-9f92-4c53-b378-03ff299171bb" />


## RESULT
The program for developing a simple calculator in React.js is executed successfully.
