# Ex.07 Restaurant Website
# Date:
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
administration.html
<!DOCTYPE html>
<html>
<head>
    <title>Administration - HOTSPOT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .admin-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .team-member {
            background-color: lightblue;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        .team-member img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .admin-login {
            margin-top: 30px;
            text-align: center;
        }
        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid gray;
            border-radius: 5px;
            font-size: 14px;
        }
        .admin-login button {
            padding: 10px 20px;
            background-color: darkslateblue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .admin-login button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>HOTSPOT Administration</h1>
</header>

<div class="admin-section">
    <h2>Meet the Team</h2>
    <div class="admin-team">
        <div class="team-member">
            <h3>John Doe</h3>
            <p>Manager</p>
        </div>
        <div class="team-member">
            <h3>Jane Smith</h3>
            <p>Assistant Manager</p>
        </div>
        <div class="team-member">
            <h3>Emily Johnson</h3>
            <p>HR Head</p>
        </div>
    </div>

    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <title>Contact Us - HOTSPOT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: white;
            padding: 20px;
        }
        .contact-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .contact-section form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-section input, .contact-section textarea, .contact-section button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid whitesmoke;
            border-radius: 5px;
        }
        .contact-section textarea {
            resize: none;
            height: 100px;
        }
        .contact-section button {
            background-color: #4a4a4a;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-section">
    <h2>We'd Love to Hear from You!</h2>
    <form>j
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>

index.html

<!DOCTYPE html>
<html>
<head>=
    <title>PALMAZA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        header {
            background-color: wheat;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 50px;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        .banner {
            text-align: right;
            background-image: url('banner.png');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 50px;
        }
        .banner h2 {
            margin: 0;
        }
        .banner p {
            margin-top: 10px;
        }
        .sections {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            gap: 10px;
        }
        .section {
            background-color: wheat;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 30%;
        }
        .section img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            background-color: white;
            padding: 10px;
            margin-top: 20px;
        }
        footer a {
            text-decoration: none;
            color: blanchedalmond;
        }
    </style>
</head>
<body>

<header>
    <img src="HOTSPOT.png" alt="HOTSPOT Logo"> 
    <h1>HOTSPOT</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special offer! Visit us this weekend and enjoy delicious meals at discounted prices.</p>
</div>

<div class="sections">
    <div class="section">
        <img src="../static/menu.png" alt="Menu"> 
        <h3>Our New Menu</h3>
        <p>Explore a variety of mouthwatering dishes crafted to satisfy every taste. From savory appetizers to hearty main courses, there's something for everyone.</p>
        <a href="menu.html">See our new menu</a>
    </div>
    <div class="section">
        <img src="../static/table.png" alt="Book a Table"> 
        <h3>Reserve Your Spot</h3>
        <p>Enjoy an unforgettable dining experience at HOTSPOT. Book your table today and treat yourself to a fantastic meal in a cozy ambiance.</p>
        <a href="booktable.html">Book your table now</a>
    </div>
    <div class="section">
        <img src="../static/hrs.png" alt="Opening Hours"> 
        <h3>Opening Hours</h3>
        <p>
            Mon - Fri: 2pm - 10pm<br>
            Sat: 2pm - 11pm<br>
            Sun: 2pm - 9pm
        </p>
    </div>
</div>
</body>
</html>

menu.html

<html>
    <head>
        <title>resturant</title>
        <link rel="stylesheet" href="style.css">
        <style>
            .container 
{
  		display: flex;
  		flex-wrap: wrap;
  		justify-content: center;
  		gap: 20px;
        left :20px;
}
.card 
{
  		width: 300px;
        height: 45%;
  		background-color:blanchedalmond;
        border: 1px solid blanchedalmond;
  		margin: 10px;
        padding-top: 25px;
  		border-radius: 20px;
  		box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  		text-align: center;
  		transition: transform 0.2s;
        color: rgb(133, 40, 40);
        font-style: italic;
}
.card img
{
    top:15px;
    width:300;
	height: 200px;
}
.card h3
{
	color:  rgb(133, 40, 40);
}
.mybutton:hover
{
	background-color: greenyellow;
}
.mybutton
{
	color: rgb(133, 40, 40);
	background-color: blanchedalmond;
	border: 1px solid black;
	padding-top: 2px;
	padding-bottom: 5px;
}
.cart
{
	padding:5px;
}
        </style>
    </head>
    <body style="background-color:rgb(253, 244, 230); font-style: italic;color:  rgb(133, 40, 40);">
        <center>
        <h1>Menu</h1>
        </center>
        <div class="container">
            <div class="card">
                <img src="../static/pizza.png">
                <h3>Margherita Pizza</h3>
                <p><B>Freshly Baked Pizza </B>with San Marzano tomatoes, fresh mozzarella, fresh basil, and extra virgin olive oil.</p>
                <h3>150 Rs.</h3>
                <div class="cart">
                <button class="myButton" type="button">Add To Cart</button>
                </div>
            </div>
            <div class="card">
                <img src="../static/burger.png">
                <h3>Zinger Burger</h3>
                <p><b>Zinger Burger</b> with crispy, spicy chicken fillet, fresh lettuce, and creamy mayonnaise on a soft bun</p>
                <h3>140 Rs.</h3>
                <div class="cart">
                <button class="myButton" type="button">Add To Cart</button>
                </div>
            </div>
            <div class="card">
                <img src="../static/salad.png">
                <h3>Greek Salad</h3>
                <p><b>Greek Salad </b>with refreshing mix of vegitables, Kalamata olives, and feta cheese, seasoned with oregano and drizzled with olive oil</p>
                <h3>100 Rs.</h3>
                <div class="cart">
                <button class="myButton" type="button">Add To Cart</button>
                </div>
            </div>
            <div class="card">
                <img src="../static/salmond.png">
                <h3>Grilled Salmond</h3>
                <p>Experience a <B>Healthy Grilled Salmond</B> with flavorful dish of tender, flaky fish with a smoky, slightly crispy exterior.</p>
                <h3>200 Rs.</h3>
                <div class="cart">
                <button class="myButton" type="button">Add To Cart</button>
                </div>
            </div>
        </div>
    </body>
</html>
```

# OUTPUT:
<img width="1920" height="1080" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/3139b38f-4a70-4453-b282-014f971aa5c3" />
<img width="1920" height="1080" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/eeb70d45-2c40-4736-9cb5-66293d339a68" />
<img width="1920" height="1080" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/959378fa-1711-41b0-b4bb-a93165f8a7fe" />
<img width="1920" height="1080" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/53117a6c-6561-47e6-8d24-da82f8d512d0" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
