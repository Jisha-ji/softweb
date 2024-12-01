# Ex.07 Restaurant Website
# Date:01.12.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
shifa.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Citrus Grove</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header> 
        <div class ="header-container">
     <img src ="lemon.png" alt="Citrus grove logo" class="logo">
        <h1>CITRUS GROVE</h1>
        </div>
        <nav>
            <ul>
                <li><a href="shifa.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h1>Welcome to Citrus Grove</h1>
        <p>Get 30% off this weekend!</p>
    </section>

    <section class="menu-section">
        <div class="info-box">
            <h2>Our New Menu</h2>
            <img src ="menu.png"alt="menu-image" style="width:200px; height:200px;">
            <p>Discover our latest offerings</p>
            <a href="menu.html">See our menu</a>
            
        </div>
        <div class="info-box">
            <h2>Administration</h2>
            <img src ="admin.png"alt="admin-image"style="width:300px; height:200px">
            <p>Meet our perfect team</p>
            <a href="administration.html">our perfect team</a>

        </div>
        <div class="info-box">
            <h2>Opening Hours</h2>
            <img src ="working.png" alt="working-image"style="width:200px; height:200px;">
            <p>Mon-Fri: 12pm - 10pm<br>Sat-Sun: 1pm - 9pm</p>
            <a href="contact.html">Contact us</a>

        </div>
    </section>

    <footer>
        <p>Designed by Jisha Bossne SJ</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Citrus Grove</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href=shifa.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
     <div class="menu-section">
        <h1>Our Menu:</h1>
        <div class="menu-items">
            <h2>Grilled Chicken Skewers</h2>
                <img src="c.png" alt ="grilled chicken">
             <h2>Caesar Salad</h2>   
             <img src="sal.png" alt ="caesar salad"> 
             <h2>Margherita Pizza</h2>   
                <img src="m.png" alt ="margherita pizza">
              <h2>Spaghetti Carbonara</h2>
                <img src="car.png" alt ="Spaghetti Carbonara"> 
               <h2>Beef Burger </h2>
                <img src="burger.png" alt ="Beef Burger">
                <h2>Vegetarian Burger</h2>               
                 <img src="veg.png" alt ="Vegetarian Burger">
                 <h2>Shrimp Tacos</h2>
                <img src="shrimp.png" alt ="Shrimp Tacos"> 
                 <h2>Quinoa Salad</h2>
                <img src="q.png" alt ="Quinoa Salad"> 
               <h2>Lemon Cheesecake</h2>
            <img src="l.png" alt ="Lemon Cheesecake">
            <h2>Chocolate Lava Cake</h2>
                <img src="lava.png" alt ="Chocolate Lava Cake"> 
              
        </div>
    </div>

    <footer>
        <p>Designed by Jisha Bossne SJ</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Citrus Grove </title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>

        <nav>
            <ul>
                <li><a href="shifa.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="admin-section">
        <h1>Meet the Team</h1>
        <div class="admin-box">
            <img src="image1.png" alt="Admin 1">
            <p>John Doe - Head Chef</p>
        </div>
        <div class="admin-box">
            <img src="image2.png" alt="Admin 2">
            <p>Jane Smith - Manager</p>
        </div>
        <div class="admin-box">
            <img src="image3.png" alt="Admin 3">
            <p>Michael Brown - Sous Chef</p>
        </div>
        <div class="admin-box">
            <img src="image4.png" alt="Admin 4">
            <p>Emily Clark - Wait Staff Supervisor</p>
        </div>
        <div class="admin-box">
            <img src="image5.png" alt="Admin 5">
            <p>David Johnson - Bartender</p>
        </div>
        <div class="admin-box">
            <img src="image6.png" alt="Admin 6">
            <p>Sarah Davis - Pastry Chef</p>
        </div>
    </section>

    <footer>
        <p>Designed by Jisha Bossne SJ</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Citrus Grove</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        
        <nav>
            <ul>
                <li><a href="shifa.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact-section">
        <h1>Contact Us</h1>
        <p>Address: 123 Lemon Street, Food City</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@citrusgrove.com</p>
    </section>

    <footer>
        <p>Designed by Jisha Bossne SJ</p>
    </footer>
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
}

header {
    background-color: #0e0f0f;
    padding: 5px;
    text-align: center;
    color: white;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.title h1 {
    font-size: 30px;
    font-weight: bold;
    position: relative; top: 60px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.logo{
    width: 50px;
    height: auto;
    position:relative; left:-150px;
    margin-bottom: -55px;
    
}
.banner { 
    background-image: url('banner.png');
    height: 175px;
    width: 1430px;
    text-align: center;
    padding: 50px;
    color: hsla(0, 10%, 96%, 0.952);
    font-size: 36px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-seri;
    border-radius: 20px;
}

.menu-section {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.menu-image{
        margin-top: 15px; 
        width: 50%;
        max-width: 50px;
        height: 50px;
        border-radius: 10px;
     
}
.menu-items{
    position: relative; left: -250px;

}
.info-box {
    background-color: rgb(232, 202, 202);
    padding: 50px;
    border-radius: 20px;
    text-align: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.admin-image{
    margin-top: 15px; 
        width: 50%;
        max-width: 100px;
        height: 100px;
        border-radius: 10px;
}
.working-image{
    margin-top: 15px; 
        width: 50%;
        max-width: 100px;
        height: 111px;
        border-radius: 10px;
}
.menu-section ul {
    list-style-type: none;
    padding: 0;
}

.menu-section ul li {
    margin: 10px 0;
    font-size: 18px;
}

.admin-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.admin-box {
    margin: 10px;
    text-align: center;
}

.admin-box img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
}

.contact-section {
    text-align: center;
    padding: 20px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0e0f0e;
    color: white;
}

```
# OUTPUT:
![Screenshot (65)](https://github.com/user-attachments/assets/0c9a338c-059b-41a4-a055-a7babb2cfcf8)
![Screenshot (66)](https://github.com/user-attachments/assets/051839ae-86ae-41f0-af44-4ffa0baea0cd)
![Screenshot (67)](https://github.com/user-attachments/assets/6be4c504-9d24-40d0-ad70-d73367adbec2)
![Screenshot (68)](https://github.com/user-attachments/assets/5c3b291e-512b-4916-91b9-c956a9e3485f)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
