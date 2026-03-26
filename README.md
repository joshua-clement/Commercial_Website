# Ex02 Commercial Website
## Date:

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

```
style.css
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background: #f5f7fa;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #1e1e2f;
  color: white;
  padding: 15px 30px;
}

.nav-links {
  display: flex;
  gap: 25px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

.nav-links a:hover {
  color: #00adb5;
}

/* Hero Section */
.hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 300px;
  background: linear-gradient(to right, #00adb5, #007b80);
  color: white;
  text-align: center;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 10px;
}

.hero button {
  margin-top: 10px;
}

/* Title */
.title {
  text-align: center;
  margin-top: 30px;
}

/* Products */
.products {
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
  padding: 40px;
}

/* Cards */
.card {
  background: white;
  padding: 20px;
  width: 220px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  text-align: center;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-10px);
}

/* Image */
.card img {
  width: 100%;
  border-radius: 10px;
}

/* Button */
button {
  background: #00adb5;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 6px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #007b80;
}

/* Footer */
footer {
  background: #1e1e2f;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}
```
```
index.html
<!DOCTYPE html>
<html>
<head>
  <title>My Store</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <div class="navbar">
    <h1>My Store</h1>
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Contact</a>
    </div>
  </div>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Welcome to My Store</h2>
    <p>Best products at affordable prices</p>
    <button>Shop Now</button>
  </section>

  <!-- Products -->
  <h2 class="title">Our Products</h2>

  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>Product 1</h3>
      <p>₹500</p>
      <button>Buy Now</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>Product 2</h3>
      <p>₹800</p>
      <button>Buy Now</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/200" alt="Product">
      <h3>Product 3</h3>
      <p>₹1200</p>
      <button>Buy Now</button>
    </div>

  </div>

  <!-- Footer -->
  <footer>
    <p>© 2026 My Store | All Rights Reserved</p>
  </footer>

</body>
</html>
```


## OUTPUT
<img width="1838" height="1004" alt="image" src="https://github.com/user-attachments/assets/1cd1b3aa-83fd-45c9-8fc8-27092d53c336" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
