# Ex02 Commercial Website

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HealthCare</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Healthcare</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact Details</a>
            <a href="#account">User Account</a>
        </nav>
    </header>

    <!-- Home / Hero Section -->
    <section id="home" class="hero">
        <div class="hero-text">
            <h2>Healthy Life Happy Life</h2>
            <p>Healthcare brings you premium, doctor-tested natural foods, products that nourish, protect your health naturally.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2>Our Products & Services</h2>
        <div class="product-card">
            <img src="images/nuts.webp" alt="Nuts">
            <h3>Nuts</h3>
            <p>A healthy food.</p>
            <span class="price">₹320.00</span>
        </div>

        <div class="product-card">
            <img src="images/whole grain.jpeg" alt="Whole grain">
            <h3>Whole grain</h3>
            <p>Opt for whole grains like brown rice, oats, quinoa, and whole-wheat bread instead of refined grains.</p>
            <span class="price">₹250.00</span>
        </div>

        <div class="product-card">
            <img src="images/fats.jpeg" alt="Healthy Fats">
            <h3>Healthy Fats</h3>
            <p>Choose healthy fats from sources like avocados, nuts, seeds, and olive oil. These fats are important for brain health, hormone production, and nutrient absorption. </p>
            <span class="price">₹500.00</span>
        </div>
    </section>


    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Details</h2>
        <p>Email: jespiah@healthcare.com</p>
        <p>Phone: +91 6383389837</p>
        <p>Address: Gandhi Street, Delhi, India</p>
    </section>

    <!-- User Account Section -->
    <section id="account" class="account">
        <h2>User Account</h2>
        <form>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" required><br><br>
            
            <button type="submit" class="btn">Login</button>
            <p>New user? <a href="#">Create an account</a></p>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="social-links">
            <a href="https://facebook.com/glowcare" target="_blank">Facebook</a> |
            <a href="https://instagram.com/glowcare" target="_blank">Instagram</a> |
            <a href="https://twitter.com/glowcare" target="_blank">Twitter</a>
        </div>
        <p>&copy; 2025 Healthcare. All rights reserved.</p>
    </footer>

</body>
</html>
```
### CSS
```
body {
    font-family: Arial, sans-serif;
    font-size: larger;
    margin: 0;
    padding: 0;
    background: #fdfdfd;
    color: #333;
}

/* Header */
header {
    background: #0a801c;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color: white;
    padding: 15px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    margin: 0;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}

nav a:hover {
    color: #6ecd7c;
}

/* Hero Section */
.hero {
    background-color: #fff5f7;
    text-align: center;
    padding: 120px 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-text {
    max-width: 600px;
    background: #f4f8f5;
    padding: 20px;
    border-radius: 10px;
}

.hero-text h2 {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 2.5rem;
    font-size: larger;
    margin-bottom: 15px;
}

.hero-text p {
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1.1rem;
}

.hero h2 {
    font-size: 40px;
}

/* Buttons */
.btn {
    display: inline-block;
    margin-top: 100px;
    padding: 10px 20px;
    background: white;
    color:  #0a801c;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background 0.3s;
}

.btn:hover {
    background: #55cf67;
}

/* Products Section */
.products {
    padding: 40px 20px;
    text-align: center;
}

.product-card {
    background: white;
    display: inline-block;
    width: 250px;
    margin: 15px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
}

.product-card img {
    width: 100%;
    border-radius: 10px;
}

.price {
    display: block;
    margin-top: 10px;
    color: #6ecd7c;
    font-weight: bold;
}


/* Contact Section */
.contact {
    padding: 40px 20px;
    background: #85f195;
    text-align: center;
}

/* User Account Section */
.account {
    padding: 40px 20px;
    background: #ffffff;
    text-align: center;
}

.account form {
    background: #b4f4bd;
    padding: 20px;
    border-radius: 10px;
    max-width: 350px;
    margin: 0 auto;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
}

.account input {
    width: 90%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #85f195;
    border-radius: 5px;
    outline: none;
}

.account button {
    margin-top: 15px;
    padding: 10px 20px;
    background: #85f195;
    color: white;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
}

.account button:hover {
    background: #499755;
}

/* Footer */
footer {
    background: #0a801c;
    color: white;
    text-align: center;
    padding: 15px;
}

.social-links {
    margin-bottom: 10px;
}

.social-links a {
    color: white;
    margin: 0 8px;
    text-decoration: none;
    font-weight: bold;
}

.social-links a:hover {
    text-decoration: underline;
}
```

## OUTPUT
<img width="1895" height="863" alt="image" src="https://github.com/user-attachments/assets/1383aef5-f5a4-4845-a081-28331b48f06a" />
<img width="1876" height="841" alt="image" src="https://github.com/user-attachments/assets/3941b835-82a2-42d2-b130-d24237faa460" />
<img width="1897" height="470" alt="image" src="https://github.com/user-attachments/assets/f3db3e37-3264-45fa-ad7c-145adfeb9694" />
<img width="1908" height="827" alt="image" src="https://github.com/user-attachments/assets/6dba8c30-58d2-42eb-8148-86198457b64d" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
