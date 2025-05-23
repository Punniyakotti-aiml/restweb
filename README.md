## Ex.07 Restaurant Website
## Date:
23-05-2025
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
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HOTEL BROTHERS</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Montserrat:wght@600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      background: linear-gradient(to right, #1c1c3b, #2c2c54);
      color: #fdf7e3;
    }

    header {
      text-align: center;
      padding: 20px;
      background: linear-gradient(135deg, #26004f, #3b0071);
    }

    header img {
      height: 80px;
    }

    nav {
      display: flex;
      justify-content: center;
      background: linear-gradient(to right, #512884, #7952b3);
      padding: 12px;
    }

    nav a {
      color: #ffd700;
      text-decoration: none;
      font-weight: bold;
      padding: 10px 20px;
      border-radius: 8px;
      transition: 0.3s;
    }

    nav a:hover {
      background-color: rgba(255, 204, 0, 0.3);
    }

    .promo {
      text-align: center;
      padding: 40px;
      background: rgba(255, 204, 0, 0.15);
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
      max-width: 700px;
      margin: 40px auto;
    }

    .promo h2 {
      font-size: 24px;
      color: #ffd700;
    }

    .promo p {
      font-size: 18px;
    }

    .cards {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 30px;
      max-width: 900px;
      margin: 40px auto;
    }

    .card {
      background: linear-gradient(145deg, #2c2c3e, #3b3b5f);
      padding: 25px;
      border-radius: 12px;
      width: 280px;
      text-align: center;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
    }

    .card h3 {
      color: #ffcc00;
    }

    .card p {
      font-size: 16px;
    }

    .card a {
      display: inline-block;
      background: linear-gradient(to right, #ff9900, #ff6600);
      color: white;
      padding: 10px 18px;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.3s;
      font-weight: bold;
    }

    .card a:hover {
      background: linear-gradient(to right, #ff7700, #ff4400);
    }

    .hours p {
      font-size: 14px;
      color: #ffd700;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: linear-gradient(135deg, #26004f, #3b0071);
    }

    footer img {
      height: 60px;
    }

    footer p {
      font-size: 14px;
      color: #ffd700;
    }

    footer a {
      color: #ffcc00;
      text-decoration: none;
      font-weight: bold;
    }

    footer a:hover {
      color: #ffffff;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.webp" alt="HOTEL BROTHERS LOGO" />
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
    <a href="book.html">Book a Table</a>
  </nav>

  <section class="promo">
    <h2>Special Weekend Discount - 30% Off</h2>
    <p>Come enjoy our exclusive weekend promotion! Our dishes are crafted using fresh, high-quality ingredients. Don’t miss out on this amazing offer!</p>
  </section>

  <section class="cards">
    <div class="card">
      <h3>Our New Menu</h3>
      <p>Discover our brand-new menu, inspired by local and international flavors. We have something for every taste!</p>
      <a href="menu.html">Explore our new menu</a>
    </div>

    <div class="card">
      <h3>Book a Table</h3>
      <p>Reserve your table online with ease. Choose your date and time, and enjoy an unforgettable dining experience.</p>
      <a href="book.html">Book your table now</a>
    </div>

    <div class="card">
      <h3>Our Opening Hours</h3>
      <p>We are open every day to serve you! Check out our opening hours:</p>
      <div class="hours">
        <p>Mon - Fri: 2:00 PM - 10:00 PM</p>
        <p>Sat: 2:00 PM - 11:00 PM</p>
        <p>Sun: 2:00 PM - 9:00 PM</p>
      </div>
    </div>
  </section>

  <footer>
    <img src="logo.webp" alt="HOTEL BROTHERS" />
    <p>Designed and developed by <a href="#">DEIVARAJA</a></p>
  </footer>

</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - HOTEL A-cash</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #030303, #1f1f1f);
            color: white;
        }

        /* Logo Section */
        .logo-container {
            text-align: center;
            padding: 20px 10px 0;
            background: linear-gradient(90deg, #ffeb3b, #ff4081);
        }

        .logo-container img {
            height: 80px;
        }

        /* Navigation */
        nav {
            background: linear-gradient(90deg, #7c4dff, #ff4081);
            display: flex;
            justify-content: center;
            padding: 12px 0;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        nav a:hover {
            color: #ffeb3b;
            transform: scale(1.1);
        }

        /* Header */
        header {
            text-align: center;
            background: linear-gradient(90deg, #ff4081, #ffeb3b);
            padding: 25px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.4);
        }

        header h1 {
            margin: 0;
            font-size: 32px;
        }

        /* Menu Section */
        .menu-section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
            background: linear-gradient(135deg, #ffffff, #f1f1f1);
            border-radius: 16px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
            animation: fadeIn 0.8s ease;
        }

        .menu-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .menu-item {
            background: linear-gradient(135deg, #74708b, #5c5980);
            border-radius: 12px;
            padding: 15px;
            text-align: center;
            width: 200px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(116, 112, 139, 0.5);
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
            margin-bottom: 10px;
        }

        .menu-item h3 {
            margin: 5px 0;
            color: #ffeb3b;
        }

        .menu-item p {
            font-size: 14px;
        }

        .price {
            font-weight: bold;
            color: #ff4081;
            font-size: 18px;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                align-items: center;
            }

            .menu-section {
                margin: 20px;
                padding: 25px;
            }
        }
    </style>
</head>
<body>

    <!-- Logo -->
    <div class="logo-container">
        <img src="logo.webp" alt="HOTEL A-cash LOGO">
    </div>

    <!-- Navigation -->
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
        <a href="book.html">Book a Table</a>
    </nav>

    <!-- Header -->
    <header>
        <h1>Our Menu</h1>
    </header>

    <!-- Menu Items -->
    <div class="menu-section">
        <div class="menu-grid">
            <div class="menu-item">
                <img src="dosha.jpg" alt="Dosa">
                <h3>Dosa</h3>
                <p>Crispy and Yummy Dosa.</p>
                <div class="price">Rs. 30</div>
            </div>
            <div class="menu-item">
                <img src="dal.jpg" alt="Dal Rice">
                <h3>Dal Rice</h3>
                <p>Traditional Indian Dal and Rice.</p>
                <div class="price">Rs. 50</div>
            </div>
            <div class="menu-item">
                <img src="vada.jpg" alt="Vada">
                <h3>Vada</h3>
                <p>Crispy and Crunchy Vada.</p>
                <div class="price">Rs. 10</div>
            </div>
            <div class="menu-item">
                <img src="coffe.jpg" alt="Coffee">
                <h3>Coffee</h3>
                <p>A delightful Coffee.</p>
                <div class="price">Rs. 10</div>
            </div>
            <div class="menu-item">
                <img src="chapathii.jpg" alt="Chappathi">
                <h3>Chappathi</h3>
                <p>Soft Chappathi.</p>
                <div class="price">Rs. 15</div>
            </div>
            <div class="menu-item">
                <img src="noodles.png" alt="Noodles">
                <h3>Noodles</h3>
                <p>Nice and long Noodles.</p>
                <div class="price">Rs. 100</div>
            </div>
        </div>
    </div>

</body>
</html>

```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - HOTEL BROTHERS</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Montserrat:wght@600&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to right, #1c1c3b, #2c2c54);
            color: #fdf7e3;
        }

        .logo-container {
            text-align: center;
            padding: 20px 10px 0;
            background: linear-gradient(135deg, #26004f, #3b0071);
        }

        .logo-container img {
            height: 80px;
        }

        nav {
            display: flex;
            justify-content: center;
            background: linear-gradient(to right, #512884, #7952b3);
            padding: 12px;
        }

        nav a {
            color: #ffd700;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 8px;
            transition: 0.3s;
        }

        nav a:hover {
            background-color: rgba(255, 204, 0, 0.3);
        }

        header {
            text-align: center;
            padding: 25px;
            background: linear-gradient(135deg, #c70039 0%, #ff5733 100%);
            color: #ffd700;
            font-size: 2rem;
            font-family: 'Montserrat', sans-serif;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: 40px auto;
            background: rgba(255, 215, 0, 0.15);
            border-radius: 12px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
            text-align: center;
        }

        .admin-section h2 {
            font-size: 24px;
            color: #ffd700;
            margin-bottom: 20px;
        }

        .admin-team {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .team-member {
            background: linear-gradient(145deg, #2c2c3e, #3b3b5f);
            padding: 20px;
            border-radius: 12px;
            width: 250px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }

        .team-member h3 {
            color: #ffd700;
        }

        .team-member p {
            font-size: 16px;
        }

        .admin-login {
            margin-top: 30px;
        }

        .admin-login input {
            padding: 12px;
            margin: 10px 5px;
            border: 1px solid #ffd700;
            border-radius: 8px;
            font-size: 16px;
            background: rgba(255, 204, 0, 0.15);
        }

        .admin-login button {
            padding: 12px 25px;
            background: linear-gradient(to right, #c70039, #ff5733);
            color: white;
            font-weight: bold;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
        }

        .admin-login button:hover {
            background: linear-gradient(to right, #9a0000, #c70039);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: linear-gradient(135deg, #26004f, #3b0071);
            color: #ffd700;
            font-size: 15px;
        }

        footer a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            color: #ffffff;
        }
    </style>
</head>
<body>

    <div class="logo-container">
        <img src="logo.webp" alt="HOTEL BROTHERS LOGO">
    </div>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <header>
        Administration
    </header>

    <div class="admin-section">
        <h2>VIEW THE BACK BONES</h2>
        <div class="admin-team">
            <div class="team-member">
                <h3>Renick</h3>
                <p>Manager</p>
            </div>
            <div class="team-member">
                <h3>Akash</h3>
                <p>Assistant Manager</p>
            </div>
            <div class="team-member">
                <h3>Govind</h3>
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

    <footer>
        <p>Designed and developed by <a href="#">DEIVARAJA</a></p>
    </footer>

</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us - HOTEL A-cash</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #121212;
      color: #fff;
    }

    .logo-container {
      text-align: center;
      padding: 20px 10px 0;
      background: linear-gradient(135deg, #ffeb3b, #ff4081);
    }

    .logo-container img {
      height: 80px;
    }

    nav {
      background: linear-gradient(90deg, #7c4dff, #ff4081);
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 12px 0;
    }

    nav a {
      color: #ffffff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
      transition: transform 0.3s, color 0.3s;
    }

    nav a:hover {
      color: #ffeb3b;
      transform: scale(1.1);
    }

    header {
      text-align: center;
      background: linear-gradient(90deg, #ff4081, #ffeb3b);
      padding: 35px 20px;
      color: white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }

    .contact-section {
      background: linear-gradient(135deg, #ffffff, #f1f1f1);
      color: #212121;
      padding: 40px 30px;
      max-width: 700px;
      margin: 40px auto;
      border-radius: 16px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
      animation: fadeIn 0.8s ease;
    }

    .contact-section h2 {
      text-align: center;
      color: #7c4dff;
      margin-bottom: 25px;
    }

    .contact-section form {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .contact-section input,
    .contact-section textarea {
      padding: 14px;
      font-size: 16px;
      border: 2px solid #ccc;
      border-radius: 8px;
      transition: border-color 0.3s, box-shadow 0.3s;
    }

    .contact-section input:focus,
    .contact-section textarea:focus {
      border-color: #ff4081;
      box-shadow: 0 0 10px #ff4081;
      outline: none;
    }

    .contact-section textarea {
      resize: vertical;
      min-height: 100px;
    }

    .contact-section button {
      padding: 14px;
      font-size: 16px;
      background: linear-gradient(90deg, #ff4081, #ffeb3b);
      color: #212121;
      font-weight: bold;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: transform 0.2s ease, box-shadow 0.3s;
    }

    .contact-section button:hover {
      transform: scale(1.05);
      box-shadow: 0 5px 15px rgba(255, 64, 129, 0.5);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      nav a {
        margin: 10px;
        display: block;
      }

      .contact-section {
        margin: 20px;
        padding: 25px;
      }
    }
  </style>
</head>
<body>

  <!-- Logo -->
  <div class="logo-container">
    <img src="logo.webp" alt="HOTEL A-cash LOGO">
  </div>

  <!-- Navigation -->
  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>Contact HOTEL A-cash</h1>
    <p>We're excited to hear from you. Let's connect!</p>
  </header>

  <!-- Contact Form Section -->
  <div class="contact-section">
    <h2>We Love to Hear from You!</h2>
    <form action="#" method="POST">
      <input type="text" name="name" placeholder="Your Full Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

</body>
</html>
```
book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Advanced Booking - Restaurant</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: linear-gradient(to right, #3b0a0a, #731010);
      color: #fdf7e3;
    }

    .logo-container {
      text-align: center;
      padding: 20px;
      background-color: #ffd700;
    }

    .logo-container img {
      height: 80px;
    }

    nav {
      background: linear-gradient(to right, #9a0000, #c70039);
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px;
    }

    nav a {
      color: #fdf7e3;
      text-decoration: none;
      margin: 10px 15px;
      font-weight: bold;
      transition: color 0.3s;
      padding: 8px 12px;
      border-radius: 20px;
    }

    nav a:hover {
      background-color: rgba(255, 215, 0, 0.3);
      color: #ffd700;
    }

    header {
      background: linear-gradient(135deg, #c70039 0%, #ff5733 100%);
      text-align: center;
      padding: 25px 15px;
    }

    header h1 {
      color: #ffd700;
      margin: 0;
      font-size: 2.5rem;
    }

    .booking-section {
      background: rgba(255, 215, 0, 0.1);
      max-width: 600px;
      margin: 40px auto;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.4);
      backdrop-filter: blur(8px);
    }

    .booking-section h2 {
      text-align: center;
      color: #ffd700;
      margin-bottom: 20px;
      font-size: 24px;
    }

    .booking-form {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    label {
      font-weight: bold;
    }

    input, select, button {
      padding: 12px;
      font-size: 16px;
      border: 1px solid #ffd700;
      border-radius: 8px;
      transition: border-color 0.3s;
      background-color: #fdf7e3;
    }

    input:focus, select:focus {
      border-color: #ff5733;
      outline: none;
    }

    button {
      background: linear-gradient(to right, #c70039, #ff5733);
      color: white;
      font-weight: bold;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s;
      padding: 12px 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }

    button:hover {
      background: linear-gradient(to right, #9a0000, #c70039);
      transform: translateY(-2px);
    }

    #confirmation {
      text-align: center;
      margin-top: 20px;
      color: #ffd700;
      font-weight: bold;
      display: none;
    }

    #preview {
      text-align: center;
      margin-top: 10px;
      color: #fdf7e3;
      font-style: italic;
    }

    footer {
      background: linear-gradient(135deg, #731010 0%, #3b0a0a 100%);
      color: #fdf7e3;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
    }

    footer img {
      height: 40px;
      vertical-align: middle;
      margin-right: 10px;
    }

    footer p {
      display: inline;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <div class="logo-container">
    <img src="logo.webp" alt="Logo">
  </div>

  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <header>
    <h1>Book a Table</h1>
  </header>

  <div class="booking-section">
    <h2>Reserve Your Table</h2>
    <form class="booking-form" id="bookingForm">
      <label for="name">Full Name:</label>
      <input type="text" name="name" id="name" placeholder="Your Full Name" required>

      <label for="email">Email Address:</label>
      <input type="email" name="email" id="email" placeholder="you@example.com" required>

      <label for="phone">Phone Number:</label>
      <input type="tel" name="phone" id="phone" placeholder="123-456-7890" required>

      <label for="guests">Guests:</label>
      <select name="guests" id="guests" required>
        <option value="" disabled selected>Choose number of guests</option>
        <option value="1">1 Guest</option>
        <option value="2">2 Guests</option>
        <option value="3">3 Guests</option>
        <option value="4">4 Guests</option>
        <option value="5">5 Guests</option>
        <option value="6+">6+ Guests</option>
      </select>

      <label for="date">Date:</label>
      <input type="date" name="date" id="date" required>

      <label for="time">Time:</label>
      <input type="time" name="time" id="time" required>

      <div id="preview"></div>

      <button type="submit">Book Now</button>
    </form>

    <div id="confirmation">✅ Your booking has been submitted!</div>
  </div>

  <footer>
    <img src="logo.webp" alt="Logo">
    <p>© 2025 HOTEL BROTHERS | Designed by DEIVARAJA</p>
  </footer>

  <script>
    const form = document.getElementById('bookingForm');
    const confirmation = document.getElementById('confirmation');
    const preview = document.getElementById('preview');
    const dateInput = document.getElementById('date');
    const timeInput = document.getElementById('time');

    form.addEventListener('submit', function(event) {
      event.preventDefault();
      confirmation.style.display = 'block';
      form.reset();
      preview.innerHTML = '';
    });

    function updatePreview() {
      const date = dateInput.value;
      const time = timeInput.value;
      if (date && time) {
        preview.textContent = `📅 You selected: ${date} at ${time}`;
      } else {
        preview.textContent = '';
      }
    }

    dateInput.addEventListener('change', updatePreview);
    timeInput.addEventListener('change', updatePreview);
  </script>

</body>
</html>
```
style.css
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxury Hotel</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #181043;
            color: #f5f5f5;
        }

        header {
            text-align: center;
            padding: 25px 0;
            background: linear-gradient(135deg, #2a004f 0%, #3b0071 100%);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        header img {
            height: 55px;
            filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.4));
        }

        header h1 {
            display: inline-block;
            margin-left: 12px;
            font-family: 'Playfair Display', serif;
            color: #ffc107;
            vertical-align: middle;
            font-size: 2.2rem;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        nav {
            background: linear-gradient(to right, #512884, #7952b3);
            padding: 12px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        nav a {
            color: #ffdd57;
            text-decoration: none;
            margin: 0 20px;
            font-weight: 600;
            font-size: 17px;
            transition: all 0.3s ease;
            padding: 8px 12px;
            border-radius: 20px;
        }

        nav a:hover {
            background-color: rgba(255, 255, 255, 0.2);
            color: #ffffff;
            transform: translateY(-2px);
        }

        .promo {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('back.jpg');
            background-size: cover;
            background-position: center;
            color: #ffffff;
            padding: 100px 40px;
            text-align: left;
            border-radius: 12px;
            margin: 35px auto;
            width: 90%;
            max-width: 1140px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .promo h2 {
            font-size: 42px;
            margin-bottom: 20px;
            color: #ffc107;
            font-family: 'Playfair Display', serif;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        .promo p {
            max-width: 620px;
            color: #eeeeee;
            font-size: 18px;
            line-height: 1.6;
        }

        .promo .btn {
            display: inline-block;
            background: linear-gradient(to right, #c59d5f, #b5832b);
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        .promo .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin: 40px auto;
            max-width: 1140px;
        }

        .card {
            background: linear-gradient(145deg, #251f47, #362a6c);
            padding: 25px;
            border-radius: 14px;
            width: 320px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        .card img {
            width: 100%;
            border-radius: 8px;
            height: 200px;
            object-fit: cover;
        }

        .card h3 {
            margin-top: 20px;
            color: #fbc531;
            font-family: 'Playfair Display', serif;
            font-size: 22px;
        }

        .card p {
            font-size: 15px;
            color: #cccccc;
            line-height: 1.6;
        }

        .card a {
            display: inline-block;
            background-color: #7d56b2;
            color: white;
            text-decoration: none;
            padding: 8px 20px;
            border-radius: 20px;
            margin-top: 15px;
            font-size: 14px;
            transition: all 0.3s ease;
        }

        .card a:hover {
            background-color: #9d72e6;
            transform: translateY(-2px);
        }

        footer {
            margin-top: 70px;
            padding: 40px 25px;
            text-align: center;
            font-size: 15px;
            color: #aaaaaa;
            background: linear-gradient(135deg, #2a004f 0%, #3b0071 100%);
        }

        footer a {
            text-decoration: none;
            color: #ffc107;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffffff;
        }
    </style>
</head>
<body>
    <!-- Your HTML structure remains unchanged -->
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot (60).png>)
![alt text](<Screenshot (61).png>)
![alt text](<Screenshot (62).png>)
![alt text](<Screenshot (63).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
