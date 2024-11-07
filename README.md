# Ex.07 Restaurant Website
## Date:07-11-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="Asset 16@4x.png" alt="Logo">
        </div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Menu</a>
            <a href="#">Book</a>
            <a href="#">About</a>
        </nav>
    </header>

    <!-- Promo Section -->
    <section class="promo">
        <h2>30% Off This Weekend</h2>
        <p class="promo-line">Weekly Taste & Happy Bites</p>
    </section>

    <!-- Main Content Section -->
    <main>
        <div class="content-box">
            <div class="card">
                <h3>Our New Menu</h3>
                <img src="images.jpg" alt="New Menu">
                <p>Honey Sriracha Chicken Skewers</p>
                <a href="#">See our new menu</a>
            </div>
            <div class="card">
                <h3>Book a table</h3>
                <img src="salmon-nicoise-salad-FT-RECIPE0221-984254ccb3734468836570330b4ff897.jpg" alt="Book a Table">
                <p>Kids Eat Free</p>
                <a href="#">Book your table now</a>
            </div>
            <div class="card">
                <h3>Opening Hours</h3>
                <img src="images (2).jpg" alt="Opening Hours">
                <p>Book your spacial time</p>
                <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
            </div>
        </div>
    </main>

    <!-- Footer Section -->
    <footer>
        <div class="footer-logo">
            <img src="Asset 20@4x.png" alt="Little Lemon Logo">
        </div>
        <div class="footer-text">
        <p>Copyright Little Lemon</p>
    </footer>
</body>
</html>
```
styles.css
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f9f9f9;
}
header {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    background-color: #333; 
    color: #fff;
}

header .logo {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 10px;
}

header nav {
    display: flex;
    gap: 15px;
    background-color: #000; 
    padding: 10px 20px; 
    border-radius: 5px; 
}

header nav a {
    color: #fff;
    text-decoration: none;
    font-size: 20px; 
}

header nav a:hover {
    color: #d3d3d3; 
}

.promo {
    background: url('pizza-5179939_960_720.jpg') center/cover no-repeat;
    padding: 50px;
    color: #0c0b0b;
    text-align: center;
}
.promo-line {
    font-size: 2em; 
    color: #fbf7f7;
    font-weight: bold;
}

.promo h2 {
    font-size: 4em;
    margin-bottom: 40px;
}

main {
    display: flex;
    justify-content: center;
    padding: 20px;
}

.content-box {
    display: flex;
    gap: 20px;
}

.card {
    background-color: #f8b052;
    padding: 20px;
    text-align: center;
    width: 600px;
    border-radius: 20px;
}

.card img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 10px;
}

.card h3 {
    color: #333;
}

.card a {
    color: #287929;
    text-decoration: none;
}


footer {
    background-color: #f2ebeb;
    color: #191414;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

.footer-logo img {
    width: 50px;
    display: flex;
    align-items: center;
    color: #777;
}
```

## OUTPUT:
![alt text](<Screenshot (31)-1.png>)
![alt text](<Screenshot (32)-1.png>) 

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
