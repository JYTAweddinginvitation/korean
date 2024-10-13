---
layout: home
home_text: request the pleasure of your company to celebrate our marriage
title: Junyoung + Thuc Anh
---


<!-- Sticky Header with Navigation Links -->
<header class="sticky-header">
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#location">Location</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <!-- Home Section -->
    <section id="home">
        {% include home.html %}
    </section>

    ---

    <!-- About Section -->
    <section id="about">
<div style="text-align: center;">
    <img src="{{'/img/about.jpeg' | relative_url }} " alt="img" style="width: 80%; max-width: 600px; height: auto;">
</div>

<div style="text-align: center;">
    <p>Request the pleasure of your company</p>
      <p></p>
    <p>to celebrate our marriage</p>
      <p></p>
    <p>on <strong>Saturday 11st January, 2025</strong></p>
      <p></p>
    <p>at <strong>Seven o'clock</strong></p>
      <p></p>
    <p>at <strong><a href="{{ '/location/' | relative_url }}">La Vela Saigon</a></strong></p>
      <p></p>
    <p>5th floor, Jupiter Hall</p>
      <p></p>
    <p>cutting of the cake is followed</p>
      <p></p>
    <p>dancing until late</p>
      <p></p>
    <p>RSVP</p>
</div>

    </section>
    
<section id="gallery">
    {% include_relative gallery.md %}
</section>

    ---

    <!-- Location Section -->
    <section id="location">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Location</title>
</head>
<body>
    <div style="text-align: center;">
        <img src="/homepage/mapimage.jpeg" alt="img" style="width: 80%; max-width: 600px; height: auto;">
    </div>

    <h3>LA VELA SAIGON HOTEL</h3>

    <h4>5th floor</h4>

    <h4>Jupiter Hall</h4>

    <p><a href="tel:+8402836222280">Tel: +84 (0) 28 3622 2280</a></p>
    <p><a href="mailto:lavelahotel@lavelasaigon.com">Email: lavelahotel@lavelasaigon.com</a></p>
    <p><a href="https://lavelasaigon.com/">Website</a></p>

    <p><a href="https://www.google.co.kr/maps/place/%EB%9D%BC+%EB%B2%A8%EB%9D%BC+%EC%82%AC%EC%9D%B4%EA%B3%B5+%ED%98%B8%ED%85%94/@10.7886761,106.6828959,17z/data=!3m1!4b1!4m9!3m8!1s0x31752f2d1f5cd9e7:0xd2284b6940329fcf!5m2!4m1!1i2!8m2!3d10.7886708!4d106.6854708!16s%2Fg%2F11h9kpyf0z?hl=ko&entry=ttu"><strong>GOOGLE MAP</strong></a></p>

    <script>
        console.log("We look forward to celebrating with you!");
        console.log("Join us at La Vela Hotel on January 11, 2025, at 7 PM for a day to remember");
    </script>
</body>
</html>
    </section>

    ---

    <!-- Contact Section -->
    <section id="contact">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation and Contact</title>
    <meta name="format-detection" content="telephone=no"> <!-- Disable automatic link detection for numbers -->
    <link rel="stylesheet" href="_sass/main.scss"> <!-- Link to your compiled CSS file -->
    <style>
        .account-popup {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.7); /* Dim background effect */
            justify-content: center;
            align-items: center;
        }

        .popup-content {
            background: white;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            color: black;
        }

        .popup-content h3, .popup-content p.account-number {
            color: black;
        }

        .popup-content button {
            background-color: #f0f0f0;
            color: black;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }

        .popup-content button:hover {
            background-color: #e0e0e0;
        }

        /* Style remittance buttons */
        .remittance-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* Creates a 2x2 layout */
            grid-gap: 10px; /* Adds spacing between the buttons */
            justify-content: center; /* Centers the grid */
        }

        .remittance-button {
            padding: 10px 20px;
            background-color: black; /* Set the button background to black */
            color: white; /* Set text color to white */
            border: none;
            cursor: pointer;
            border-radius: 5px;
            text-align: center;
            min-width: 150px; /* Ensure a consistent width */
            font-size: 14px; /* Reduce the font size slightly */
            transition: background-color 0.3s ease;
        }

        .remittance-button:hover {
            background-color: #333; /* Darken slightly on hover */
        }

        /* Center and size the thank you image */
        .thank-you-image {
            display: block;
            margin: 20px auto; /* Centers the image */
            max-width: 100%; /* Ensures it doesn’t overflow the page */
            width: 300px; /* You can adjust the width here */
            height: auto; /* Maintain the aspect ratio */
        }

        /* Icon styling */
        .contact-item a img {
            width: 40px; /* Size of the icons */
            margin-right: 10px;
            transition: opacity 0.3s ease;
        }

        .contact-item a img:hover {
            opacity: 0.8; /* Add a hover effect to icons */
        }
    </style>
</head>
<body>
<section id="contact">
        {% include contact.html %}   

</section>
</div>
