# Ex.07 Restaurant Website
# Date:9.5.2025
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
administartion.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MM Biriyani - Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">MM Biriyani</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html" class="active">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="administration">
            <h2>Our Team</h2>
            <div class="admin-grid">
                <div class="admin-item">
                    <img src="images/chef1.jpg" alt="Chef Rajesh Kumar">
                    <h3>Rajesh Kumar</h3>
                    <p>Head Chef</p>
                </div>
                <div class="admin-item">
                    <img src="images/manager1.jpg" alt="Manager Priya Sharma">
                    <h3>Priya Sharma</h3>
                    <p>Restaurant Manager</p>
                </div>
                <div class="admin-item">
                    <img src="images/chef2.jpg" alt="Sous Chef Anil Menon">
                    <h3>Anil Menon</h3>
                    <p>Sous Chef</p>
                </div>
                <div class="admin-item">
                    <img src="images/staff1.jpg" alt="Server Lakshmi Rao">
                    <h3>Lakshmi Rao</h3>
                    <p>Head Server</p>
                </div>
                <div class="admin-item">
                    <img src="images/staff2.jpg" alt="Cashier Sanjay Patel">
                    <h3>Sanjay Patel</h3>
                    <p>Cashier</p>
                </div>
                <div class="admin-item">
                    <img src="images/marketing1.jpg" alt="Marketing Head Meena Iyer">
                    <h3>Meena Iyer</h3>
                    <p>Marketing Head</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MM Biriyani | Designed by M Malligesh (212223230119)</p>
    </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MM Biriyani - Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">MM Biriyani</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html" class="active">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="contact">
            <h2>Contact Us</h2>
            <div class="contact-details">
                <img src="images/restaurant.jpg" alt="MM Biriyani Restaurant">
                <p><strong>Address:</strong> 123 Anna Salai, Chennai, Tamil Nadu 600002, India</p>
                <p><strong>Phone:</strong> +91 98765 43210</p>
                <p><strong>Email:</strong> info@mmbiriyani.com</p>
            </div>
            <h3>Send Us a Message</h3>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MM Biriyani | Designed by M Malligesh (212223230119)</p>
    </footer>
</body>
</html>

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MM Biriyani - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">MM Biriyani</div>
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
        <div class="banner">
            <img src="images/banner.jpg" alt="South Indian Biriyani Banner">
            <h1>Welcome to MM Biriyani</h1>
        </div>
    </header>
    <main>
        <section class="welcome">
            <h2>Experience Authentic South Indian Cuisine</h2>
            <p>At MM Biriyani, we bring the rich flavors of South India to your plate. Our signature biriyanis, dosas, and curries are crafted with traditional recipes and fresh ingredients. Join us for a culinary journey that celebrates the essence of South Indian hospitality.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 MM Biriyani | Designed by M Malligesh (212223230119)</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MM Biriyani - Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">MM Biriyani</div>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html" class="active">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="menu-section">
            <h2>Our Delicious Menu</h2>
            <div class="menu-grid">
                <div class="menu-item">
                    <img src="images/chicken_biriyani.jpg" alt="Chicken Biriyani">
                    <h3>Chicken Biriyani</h3>
                </div>
                <div class="menu-item">
                    <img src="images/mutton_biriyani.jpg" alt="Mutton Biriyani">
                    <h3>Mutton Biriyani</h3>
                </div>
                <div class="menu-item">
                    <img src="images/veg_biriyani.jpg" alt="Veg Biriyani">
                    <h3>Veg Biriyani</h3>
                </div>
                <div class="menu-item">
                    <img src="images/panner_tikka.jpg" alt="Paneer Tikka">
                    <h3>Paneer Tikka</h3>
                </div>
                <div class="menu-item">
                    <img src="images/masala_dosa.jpg" alt="Masala Dosa">
                    <h3>Masala Dosa</h3>
                </div>
                <div class="menu-item">
                    <img src="images/fish_fry.jpg" alt="Fish Fry">
                    <h3>Fish Fry</h3>
                </div>
                <div class="menu-item">
                    <img src="images/idli.jpg" alt="Idli">
                    <h3>Idli</h3>
                </div>
                <div class="menu-item">
                    <img src="images/vada.jpg" alt="Vada">
                    <h3>Vada</h3>
                </div>
                <div class="menu-item">
                    <img src="images/sambar_rice.jpg" alt="Sambar Rice">
                    <h3>Sambar Rice</h3>
                </div>
                <div class="menu-item">
                    <img src="images/rasam.jpg" alt="Rasam">
                    <h3>Rasam</h3>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 MM Biriyani | Designed by M Malligesh (212223230119)</p>
    </footer>
</body>
</html>
```

# OUTPUT:
![Screenshot 2025-05-09 130733](https://github.com/user-attachments/assets/4c30e3c1-e483-46c9-bc56-8ecbbf43825b)

![Screenshot 2025-05-09 130746](https://github.com/user-attachments/assets/e1964605-136f-4805-9287-027cefca0481)

![Screenshot 2025-05-09 130811](https://github.com/user-attachments/assets/f36893a5-e04d-4595-95f5-6d63a3649faa)

![Screenshot 2025-05-09 130833](https://github.com/user-attachments/assets/7f4ddf23-792d-4c82-994f-135e5b7c7a01)

![Screenshot 2025-05-09 131143](https://github.com/user-attachments/assets/4bfa2eea-bf46-4a00-9b8f-50a794379112)




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
