# Ex04 Places Around Me
# Date:04/12/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="C:\\Users\\Arun\\Pictures\\Screenshots\\Screenshot 2024-12-03 212847.png" width="1520" height="750" usemap="#mymap">
    <map name="mymap">
        <area shape="rect" coords="784,58,1080,138" title="Electronics store" href=file:///C:/Users/Arun/HTML%20PRACTICE/imap1.html>
        <area shape="rect" coords="705,276,889,383" title="Medical store" href=file:///C:/Users/Arun/HTML%20PRACTICE/imap2.html>
        <area shape="rect" coords="299,580,473,679" title="Book store" href=file:///C:/Users/Arun/HTML%20PRACTICE/imap3.html>
    </map>
</body>
</html>

mohan electic store.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohan Electric Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            height: auto;
        }
        .container {
            padding: 20px;
        }
        .product {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
            float: left;
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Mohan Electric Store</h1>
    <p>Your one-stop shop for all your electric needs</p>
</header>

<img class="banner" src="C:\\Users\\Arun\\Documents\\electronics store.jpg" alt="Electric Store Banner">

<div class="container">
    <h2>Our Products</h2>

    <div class="product">
        <p>Mohan Electronics Store is a trusted and customer-friendly destination for all your electronic needs. Established with the vision of providing high-quality products at affordable prices, the store offers a wide range of gadgets, including smartphones, laptops, headphones, smartwatches, and tablets. Known for its excellent customer service and reliable after-sales support, Mohan Electronics Store ensures a seamless shopping experience. Whether you're a tech enthusiast looking for the latest devices or someone in need of everyday electronics, the store caters to all requirements with competitive pricing and attractive deals. With a commitment to innovation and customer satisfaction, Mohan Electronics Store has become a go-to choice for electronics in the community.</p>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Electric Avenue,Ramnadu</p>
    <p><strong>Phone:</strong>9874563210</p>
    <p><strong>Email:</strong> contact@mohanelectric.com</p>
</div>

<footer>
    <p>&copy; 2024 Mohan Electric Store. All rights reserved.</p>
</footer>

</body>
</html>

saravana medical store.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medical Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            margin-top: 20px;
            padding: 10px;
            background-color: #e8f5e9;
            border-left: 5px solid #4caf50;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4caf50;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Saravana Medical Store</h1>
    </header>
    <main>
        <img src="C:\\Users\\Arun\\Documents\\medical store.jpg" alt="Medical Store Image">
        <h2>About Us</h2>
        <p>Welcome to Saravana Medical Store, your trusted partner for quality medicines and healthcare products. We provide a wide range of prescription and over-the-counter medications, health supplements, and medical equipment. Our dedicated team ensures the highest standards of service and care.</p>
        <h3>Why Choose Us?</h3>
        <ul>
            <li>Authentic and certified medicines</li>
            <li>Friendly and knowledgeable staff</li>
            <li>Convenient location and home delivery services</li>
            <li>24/7 customer support for emergencies</li>
        </ul>
        <div class="contact">
            <h3>Contact Us</h3>
            <p><strong>Address:</strong> Wellness Street,Ramnadu</p>
            <p><strong>Phone:</strong>9632014587</p>
            <p><strong>Email:</strong> info@saravanamedical.com</p>
            <p><strong>Opening Hours:</strong> Mon-Sun: 8:00 AM - 10:00 PM</p>
        </div>
    </main>
    <footer>
        &copy; 2024 Saravana Medical Store. All Rights Reserved.
    </footer>
</body>
</html>

book store.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f3e9;
            color: #333;
        }
        header {
            background-color: #6c5ce7;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: 20px auto;
            background: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            margin-top: 20px;
            padding: 10px;
            background-color: #e3d9fc;
            border-left: 5px solid #6c5ce7;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #6c5ce7;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Aruna Book Store</h1>
    </header>
    <main>
        <img src="C:\\Users\\Arun\\Documents\\book store.jpg" alt="Bookstore Image">
        <h2>Welcome to Aruna Book Store</h2>
        <p>Your one-stop destination for a wide range of books! At Book Haven, we believe in the power of stories to inspire, educate, and entertain. Whether you’re a fan of fiction, non-fiction, academic textbooks, or rare collectibles, we have something for everyone.</p>
        <h3>Why Shop With Us?</h3>
        <ul>
            <li>A vast collection of books across all genres</li>
            <li>Affordable prices and great deals</li>
            <li>Friendly staff to assist you in finding the perfect read</li>
            <li>Book clubs and author meet-ups</li>
        </ul>
        <div class="contact">
            <h3>Contact Us</h3>
            <p><strong>Address:</strong> Literary Lane,Ramnadu</p>
            <p><strong>Phone:</strong>9510236547</p>
            <p><strong>Email:</strong> info@arunabookstore.com</p>
            <p><strong>Opening Hours:</strong> Mon-Sat: 9:00 AM - 8:00 PM, Sun: 10:00 AM - 6:00 PM</p>
        </div>
    </main>
    <footer>
        &copy; 2024 Aruna Book Store. All Rights Reserved.
    </footer>
</body>
</html>
```
# OUTPUT
![Screenshot 2024-12-04 214602](https://github.com/user-attachments/assets/223ef8f9-6284-4cb7-9a9d-091a42f25a21)
![Screenshot 2024-12-04 214810](https://github.com/user-attachments/assets/da3dd297-e89a-447b-a6d5-1921d9523a71)
![Screenshot 2024-12-04 214822](https://github.com/user-attachments/assets/45bdb5dc-a2e2-43ce-9776-a8e13ba99d68)
![Screenshot 2024-12-04 214937](https://github.com/user-attachments/assets/1fb1091e-5986-4234-916d-3fbf1ecdabf6)
![Screenshot 2024-12-04 215100](https://github.com/user-attachments/assets/afd1e9d4-9fca-4a84-94f8-c7de34b1becd)



# RESULT
The program for implementing image maps using HTML is executed successfully.
