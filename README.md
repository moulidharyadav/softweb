# Ex.07 Restaurant Website
# Date:28/04/25
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
~~~
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abheek Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="navbar background">
        <div class="logo">
            <img src="images/sheraton-atlanta-hotel-logo.png" style="height: 40px;" alt="Logo">
        </div>
        <ul class="nav-list">
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
       
    </nav>

    <section class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="text-big" id="program">
                    Welcome to Sheraton Atlanta - A Luxurious Retreat
                </h1>
                <p class="text-small">
                    ...At Sheraton Atlanta, we believe that dining is an art form. Located within the luxurious setting of Sheraton, our restaurant offers an unforgettable culinary experience that tantalizes the senses and celebrates the finest flavors from around the world.
                </p>
            </div>



        </div>
    </section>

    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Amenities</div>
            <img src="images/img10.jpg" alt="Bottom Image 1">
            <div class="bottom-text">
                World Class Dining
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Infinite Pool</div>
            <img src="images/img11.jpg" alt="Bottom Image 2">
            <div class="bottom-text">
                Infinite Pool Dining Which Gives Luxury To The Max
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Party Hub</div>
            <img src="images/img12.jpg" alt="Bottom Image 3">
            <div class="bottom-text">
                Party All Night With The Best Food.
            </div>
        </div>
    </div>

    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
        <p>
            email:abc@gmail.com Number:2156725382>
        </p>
    </footer>
</body>

</html>


~~~
## about
~~~
<!DOCTYPE html>
<html>

<head>
    <title>Abheek Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="navbar background">
        <div class="logo">
            <img src="images/sheraton-atlanta-hotel-logo.png" style="height: 40px;" alt="Logo">
        </div>
        <ul class="nav-list">
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
        
    </nav>

   

    <div class="about-container">
        <div class="about-image">
            <img src="images/img8.jpg" alt="About Us Image">
        </div>
        <div class="about-text">
            <h2>About Us</h2>
            <p>Welcome to Sheraton Atlanta, where culinary artistry meets a warm and inviting atmosphere. Nestled in the heart of [Location], our restaurant is a celebration of fresh, locally-sourced ingredients and time-honored recipes. We believe that dining should be more than just a meal—it should be an experience that delights all the senses.

                At Sheraton Atlanta, our chefs blend innovation with tradition to create dishes that are both familiar and unexpected. From seasonal favorites to signature creations, every plate is crafted with care, passion, and attention to detail. Whether you're joining us for a casual lunch, a special dinner, or a weekend brunch, we aim to make every visit memorable.
                
                Our philosophy is simple: quality ingredients, exceptional service, and a relaxed yet refined setting. We invite you to come, savor, and enjoy.
        </div>
    </div>

   

    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
    </footer>
</body>

</html>
~~~
## contact us
~~~
<!DOCTYPE html>
<html>

<head>
    <title>Abheek Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="navbar background">
        <div class="logo">
            <img src="images/sheraton-atlanta-hotel-logo.png" style="height: 40px;" alt="Logo">
        </div>
        <ul class="nav-list">
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
        
    </nav>


    <div class="contact-container">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out to us using the form below.</p>
        <p>email:abc@gmail.com</p>
        <p>contact number:+217257364314</p>
        
        <form class="contact-form" action="submit_form.php" method="post">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" rows="6" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
    </footer>
</body>

</html>
~~~
##menu
~~~
<!DOCTYPE html>
<html>

<head>
    <title>Abheek Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <nav class="navbar background">
        <div class="logo">
            <img src="images/sheraton-atlanta-hotel-logo.png" style="height: 40px;" alt="Logo">
        </div>
        <ul class="nav-list">
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
       
    </nav>

    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Chicken Burger</div>
            <img src="images/image1.jpg" alt="Bottom Image 1">
            <div class="bottom-text">
                Juicy grilled chicken, fresh lettuce, tomato, and creamy mayo in a bun.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Salmon Platter</div>
            <img src="images/image2.jpg" alt="Bottom Image 2">
            <div class="bottom-text">
                A fresh salmon platter with herbs, lemon slices, and creamy dip.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Sushi Rolls</div>
            <img src="images/image3.jpg" alt="Bottom Image 3">
            <div class="bottom-text">
                Fresh seafood, vinegared rice, wrapped in seaweed, flavorful and delicious!
            </div>
        </div>
    </div>


    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Japanese Platter</div>
            <img src="images/image4.jpg" alt="Bottom Image 1">
            <div class="bottom-text">
                Elegant assortment of sushi, sashimi, tempura, and pickled vegetables.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Seafood Platter</div>
            <img src="images/image5.jpg" alt="Bottom Image 2">
            <div class="bottom-text">
                A lavish seafood platter with oysters, lobster, shrimp, and crab.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">3 Piece Platter</div>
            <img src="images/image6.jpg" alt="Bottom Image 3">
            <div class="bottom-text">
                A three-piece platter featuring a main dish, side, and garnish.
            </div>
        </div>
    </div>


    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Sushi Salmon Combo</div>
            <img src="images/image7.jpg" alt="Bottom Image 1">
            <div class="bottom-text">
                Fresh sushi platter featuring tender salmon slices and flavorful accompaniments.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Sushi Plate</div>
            <img src="images/image8.jpg" alt="Bottom Image 2">
            <div class="bottom-text">
                A vibrant sushi plate with colorful rolls, fresh fish, and garnishes.
            </div>
            
        </div>
        <div class="image-container">
            <div class="image-text">Double Deck Burger</div>
            <img src="images/image1.jpg" alt="Bottom Image 3">
            <div class="bottom-text">
                A towering burger with two juicy patties and flavorful toppings.
            </div>
        </div>
    </div>


    

    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
    </footer>
</body>

</html>
~~~
##admin
~~~
<!DOCTYPE html>
<html>

<head>
    <title>Aravind Web Page</title>
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <nav class="navbar background">
        <div class="logo">
            <img src="images/sheraton-atlanta-hotel-logo.png" style="height: 40px;" alt="Logo">
        </div>
        <ul class="nav-list">
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="admin.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>

    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Dong Lee</div>
            <img src="images/chef1.png" alt="Chef 1">
            <div class="bottom-text">
                Head Chef.
            </div>
        </div>
        <div class="image-container">
            <div class="image-text">Naruto</div>
            <img src="images/chef6.jpg" alt="Chef 2">
            <div class="bottom-text">
              Asst Head Chef.
            </div>
        </div>
        <div class="image-container">
            <div class="image-text">Damu</div>
            <img src="images/chef3.jpeg" alt="Chef 3">
            <div class="bottom-text">
                Chief Manager.
            </div>
        </div>
    </div>

    <div class="bottom-images">
        <div class="image-container">
            <div class="image-text">Kevin Hart</div>
            <img src="images/chef4.avif" alt="Chef 4">
            <div class="bottom-text">
                Chinese chef.
            </div>
        </div>
        <div class="image-container">
            <div class="image-text">John</div>
            <img src="images/chef5.avif" alt="Chef 5">
            <div class="bottom-text">
                Indo Asian chef.
            </div>
        </div>
        <div class="image-container">
            <div class="image-text">Smith</div>
            <img src="images/chef2.jpeg" alt="Chef 6">
            <div class="bottom-text">
                Indian chef.
            </div>
        </div>
    </div>

    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
    </footer>
</body>

</html>
~~~
##css
~~~
* {
    margin: 0;
    padding: 0;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #3338;
    top: 0;
    padding: 15px;
    cursor: pointer;
}

.background {
    background: wheat;
    background-blend-mode: darken;
    background-size: bottom;
}

.nav-list {
    width: 70%;
    display: flex;
    align-items: center;
    gap: 50px;
    list-style: none;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo img {
    width: 250px;
    border-radius: 50px;
}

.nav-list li {
    list-style: none;
    padding: 26px 30px;
    padding: 10px;
}

.nav-list li a {
    color: black;
    text-decoration: none;
    padding: 10px 20px;
    font-size: 20px;
    transition: background-color 0.3s ease; 

}

.nav-list li a:hover {
    color: grey;
}

.rightnav {
    width: 30%;
    text-align: right;
}

#search {
    padding: 5px;
    font-size: 17px;
    border: 2px solid grey;
    border-radius: 9px;
}

.firstsection {
    background-color: rgb(244, 246, 244);
    height: 420px;
}

.secondsection {
    background-color: blue;
    height: 400px;
}

.box-main {
        background-image: url('images/top1.jpg'); /* Path to your background image */
        background-size: cover; /* Ensures the image covers the whole background */
        background-position: center; /* Centers the image */
        height: 420px; /* Makes sure the image fills the entire viewport */
        margin: 0;
}

/* Style for content inside the page */
.content {
    color: white;
    text-align: center;
    padding: 100px 20px;
}
.firsthalf {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.secondhalf {
    width: 30%;
}

.secondhalf img {
    width: 70%;
    border: 4px solid white;
    border-radius: 150px;
    display: block;
    margin: auto;
}

.text-big {
    font-family: 'Piazzolla', serif;
    font-weight: bold;
    text-align: center;
    font-size: 35px;
    color: aliceblue;
    padding:5%;
}

.text-small {
    font-size: 24px;
    color: aliceblue
}

.btn {
    padding: 8px 20px;
    margin: 7px 0;
    border: 2px solid white;
    border-radius: 8px;
    background: none;
    color: white;
    cursor: pointer;
}

.btn-sm {
    padding: 6px 10px;
    vertical-align: middle;
}

.section {
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    max-width: 90%;
    margin: auto;
}

.section-Left {
    flex-direction: row-reverse;
}

.paras {
    padding: 0px 65px;
}

.thumbnail img {
    width: 250px;
    border: 2px solid black;
    border-radius: 26px;
    margin-top: 19px;
}

.center {
    text-align: center;
}

.text-footer {
    text-align: center;
    padding: 30px 0;
    font-family: 'Ubuntu', sans-serif;
    display: flex;
    justify-content: center;
    color: black;
}

footer {
    text-align: center;
    padding: 15px;
}


.rightnav {
    width: 100%;
    text-align: right;
    margin-top: 10px;
}

#search {
    box-sizing: border-box;
    width: 70%;
    padding: 8px;
    font-size: 17px;
    border: 2px solid grey;
    border-radius: 9px;
}

.btn-sm {
    padding: 8px 20px;
    margin: 7px 5px;
}

img {
    max-width: 100%;
    height: auto;
}

/* Basic reset for consistent styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Main container for the image layout */
.image-layout {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 20px;
}

/* Container for each image and its text */
.image-container {
    position: relative;
    width: 100%;
    max-width: 100%; /* Ensures the image fits the container */
    text-align: center; /* Centers the text horizontally */
}

/* Style for the images */
.image-container img {
    width: 100%; /* Ensure the image fits the container */
    height: auto;
    display: block;
}

/* Text overlaid on the image */
.image-text {
    position: absolute;
    top: 0; /* Position the text at the top of the image */
    left: 0; /* Make the background cover the full width */
    right: 0; /* Extend the background across the entire width */
    color: white;
    font-size: 24px;
    font-weight: bold;
    padding: 10px;
    background-color: rgba(0, 0, 0, 0.6); /* Full-width background shading */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

/* Bottom images styling */
.bottom-images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

/* Ensure bottom images are responsive */
.bottom-images .image-container {
    width: 30%; /* Each image takes up 30% of the container width */
}

/* Text placed below each image */
.bottom-text {
    margin-top: 10px; /* Adds space between the image and the bottom text */
    text-align: center;
    font-size: 18px;
    color: #333; /* You can adjust the color to match your design */
}



/* Styling for the contact form container */
.contact-container {
    max-width: 600px;
    margin: 50px auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 10px;
    background-color: #f9f9f9;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

/* Heading styles */
.contact-container h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.contact-container p {
    font-size: 16px;
    margin-bottom: 20px;
    color: #666;
}

/* Styling for the form */
.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

/* Input fields and textarea styling */
.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 5px;
    outline: none;
    background-color: #fff;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #007BFF;
}

/* Button styling */
.contact-form button {
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #007BFF;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.contact-form button:hover {
    background-color: #0056b3;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    .contact-container {
        margin: 20px;
        padding: 15px;
    }
}


/* Main container for the About Us section */
.about-container {
    display: flex;
    flex-direction: row; /* Align items in a row */
    align-items: center; /* Center vertically */
    max-width: 1000px; /* Max width for the container */
    margin: 50px auto; /* Center the container */
    padding: 20px; /* Add some padding */
}

/* Image styling */
.about-image {
    flex: 1; /* Image takes 1 part of the flex space */
    padding: 20px; /* Add some padding around the image */
}

.about-image img {
    width: 100%; /* Make the image responsive */
    height: auto; /* Maintain aspect ratio */
    border-radius: 10px; /* Optional: rounded corners for the image */
}

/* Text styling */
.about-text {
    flex: 1; /* Text takes 1 part of the flex space */
    padding: 20px; /* Add some padding around the text */
}

.about-text h2 {
    font-size: 28px; /* Size of the heading */
    margin-bottom: 15px; /* Space below the heading */
}

.about-text p {
    font-size: 16px; /* Size of the paragraph text */
    line-height: 1.6; /* Line height for readability */
    margin-bottom: 10px; /* Space between paragraphs */
}

/* Responsive adjustments */
@media (max-width: 768px) {
    .about-container {
        flex-direction: column; /* Stack elements on smaller screens */
    }

    .about-image, .about-text {
        padding: 10px; /* Reduce padding */
    }
}
~~~
# OUTPUT:
![image](https://github.com/user-attachments/assets/9b4c1ea9-a603-4034-968b-658da81f0d96)
![image](https://github.com/user-attachments/assets/9eecd885-5c32-41b4-9eff-d1108a8be506)
![image](https://github.com/user-attachments/assets/b0d5bb21-621e-4056-84aa-72ba729f8af5)
![image](https://github.com/user-attachments/assets/62d422e4-c833-4b07-a488-e5cb3d820657)
![image](https://github.com/user-attachments/assets/7813f8a6-88c6-45b3-89e2-6958969986a5)






# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
