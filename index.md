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

<!-- Inline CSS to force max-width only on larger screens -->
<style>
    body {
        margin: 0;
        padding: 0;
    }

/* Sticky Header Styles */
.sticky-header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%; /* Change to 100% to cover the full width */
    background-color: white;
    padding: 10px 0; /* Add padding for better spacing */
    z-index: 1000;
    text-align: center; /* Center-align the contents */
}

.sticky-header nav ul {
    display: flex;
    justify-content: center; /* Center the navigation links */
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.sticky-header nav ul li {
    margin: 0 15px;
}

.sticky-header nav ul li a {
    color: black;
    text-decoration: none;
    font-weight: bold;
    padding: 10px;
    transition: color 0.3s;
}

.sticky-header nav ul li a:hover {
    color: #f0f0f0;
}

/* Add spacing to prevent content from being hidden by the sticky header */
section {
    margin-top: 60px;
}
</style>

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

    ---

    <!-- Gallery Section -->
    <section id="gallery">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>

    <!-- Gallery Styles -->
    <style>
        .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .gallery-item {
            width: calc(33.333% - 10px);
            margin-bottom: 15px;
            position: relative;
        }

        .gallery-item figure {
            margin: 0;
            position: relative;
            overflow: hidden;
        }

        .gallery-item .thumb-container {
            position: relative;
            width: 100%;
            padding-bottom: 100%;
            overflow: hidden;
        }

        .gallery-item img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            cursor: pointer;
        }

        /* Blank placeholder for centering */
        .blank-gallery-item {
            width: calc(33.333% - 10px);
            margin-bottom: 15px;
            visibility: hidden;
        }
    </style>

</head>

<body>
    <section class="gallery line" id="gallery">
        <div class="area gallery-container">
            <!-- First row with blank spaces and small picture -->
            <div class="blank-gallery-item"></div> <!-- Blank space on the left -->
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/gallery.JPG' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/gallery.JPG' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="Little Picture">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="blank-gallery-item"></div> <!-- Blank space on the right -->
            <!-- Gallery Items -->
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/01.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/01.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/02.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/02.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/03.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/03.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/04.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/04.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/05.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/05.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/06.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/06.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/07.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/07.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/08.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/08.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/09.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/09.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/10.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/10.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/11.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/11.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/12.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/12.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/13.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/13.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/14.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/14.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/15.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/15.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/16.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/16.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/17.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/17.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/18.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/18.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/19.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/19.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/20.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/20.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>
            <div class="gallery-item">
                <figure>
                    <div class="thumb-container">
                        <a href="{{ '/img/galleryimage/21.jpeg' | relative_url }}" class="setimgsize" itemprop="contentUrl" data-size="2150x1536">
                            <img src="{{ '/img/thumbnail/21.jpeg' | relative_url }}" class="img_frame" itemprop="thumbnail" alt="">
                        </a>
                    </div>
                </figure>
            </div>

            <!-- Add more gallery items as needed -->
        </div>
    </section>
</body>
    </section>

    ---

    <!-- Location Section -->
    <section id="location">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Location</title>
</head>
<body>
    <div style="text-align: center;">
        <img src="/mapimage.jpeg" alt="img" style="width: 80%; max-width: 600px; height: auto;">
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
    <div class="mid-section-cover">
        <main class="sub-mid-section-cover">
            <section id="contact">
                <h2>Contact</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <h3>Groom: Junyoung Kim</h3>
                        <!-- Replace text with icons for call, SMS, and email -->
                        <a href="tel:+821041351599">
                            <img src="/homepage/img/callicon.JPG" alt="Call">
                        </a>
                        <a href="sms:+821041351599">
                            <img src="/homepage/img/mmsicon.JPG" alt="SMS">
                        </a>
                        <a href="mailto:tyjy1825@gmail.com">
                            <img src="/homepage/img/mailicon.JPG" alt="Email">
                        </a>
                    </div>
                    <div class="contact-item">
                        <h3>Bride: Luong Thuc Anh</h3>
                        <!-- Replace text with icons for call, SMS, and email -->
                        <a href="tel:+821048651599">
                            <img src="/homepage/img/callicon.JPG" alt="Call">
                        </a>
                        <a href="sms:+821048651599">
                            <img src="/homepage/img/mmsicon.JPG" alt="SMS">
                        </a>
                        <a href="mailto:anhluong.uah@gmail.com">
                            <img src="/homepage/img/mailicon.JPG" alt="Email">
                        </a>
                    </div>
                </div>
            </section>

            <section id="family">
                <h2>Family</h2>
                <div class="family-grid">
                    <div class="family-item">
                        <h3>Groom's Family</h3>
                        <p>Father : Kim Je-jung</p>
                        <div class="contact-item">
                        <a href="tel:+84908501939">
                            <img src="/homepage/img/callvnicon.JPG" alt="Call">
                        </a>
                        <a href="sms:+84908501939">
                            <img src="/homepage/img/mmsvnicon.JPG" alt="SMS">
                        </a>

                        <p>Mother : Kim Hee-won</p>
                        <div class="contact-item">
                        <a href="tel:+931479720">
                            <img src="/homepage/img/callvnicon.JPG" alt="Call">
                        </a>
                        <a href="sms:+931479720">
                            <img src="/homepage/img/mmsvnicon.JPG" alt="SMS">
                        </a>
                        </div>

                        <div class="contact-item">
                        <a href="tel:+821028021599">
                            <img src="/homepage/img/callkricon.JPG" alt="Call">
                        </a>
                        <a href="sms:+821028021599">
                            <img src="/homepage/img/mmskricon.JPG" alt="SMS">
                        </a>


                    </div>
                    <div class="family-item">
                        <h3>Bride's Family</h3>
                        <p>Father : Luong Quac Vinh</p>
                        <p>Mother : Nguyen Trong Anh Tuyet</p>
                        <div class="contact-item">
                        <a href="tel:+821048651599">
                            <img src="/homepage/img/callicon.JPG" alt="Call">
                        </a>
                        <a href="sms:+821048651599">
                            <img src="/homepage/img/mmsicon.JPG" alt="SMS">
                        </a>

                    </div>
                </div>
            </section>

            <section id="remittance">
                <h2>Remittance</h2>
                <p>For those unable to attend in person but wishing to send their congratulations, we have included our bank account details. We kindly ask for your understanding, and we will cherish your heartfelt gestures as we strive to build a loving marriage.</p>
                <div class="remittance-grid">
                    <button class="remittance-button" data-idx="1">Groom</button>
                    <button class="remittance-button" data-idx="2">Bride</button>
                    <button class="remittance-button" data-idx="3">Groom's Family</button>
                    <button class="remittance-button" data-idx="4">Bride's Family</button>
                </div>
            </section>
        </main>
    </div>
        <!-- Add the thank you image -->
    <img src="/homepage/img/thankyou.JPG" alt="Thank You" class="thank-you-image">

    <!-- Horizontal rule at the end -->
    <hr>

    <div class="account-popup" data-idx="1">
        <div class="popup-content">
            <h3>Groom's Account Number</h3>
            <p>Account Holder: Kim Jun young 김준영</p>
            <p class="account-number" id="groom-account">신한은행 110581193664
            <button class="copy-button" data-account="groom-account">Copy</button> <!-- Copy button --> </p>
            <button class="close-popup">Close</button>
        </div>
    </div>

    <div class="account-popup" data-idx="2">
        <div class="popup-content">
            <h3>Bride's Account Number</h3>
            <p>Account Holder : Luong Thuc Anh</p>
            <p class="account-number" id="bride-account"> 우리은행 1002035203849 
            <button class="copy-button" data-account="bride-account">Copy</button> <!-- Copy button --> </p>
            <button class="close-popup">Close</button>
        </div>
    </div>

    <div class="account-popup" data-idx="3">
        <div class="popup-content">
            <h3>Groom's Family's Account Number</h3>
            <p>Groom's Father (Account Holder: Kim Je-Jung 김제중)</p>
            <p class="account-number" id="kimjejung_account">농협 84512322040
            <button class="copy-button" data-account="kimjejung_account">Copy</button> <!-- Copy button --> </p>
            <p>Groom's Mother (Account Holder: Kim Hee-Won 김희원)</p>
            <p class="account-number" id="kimheewon_account">우리은행 27908039244
            <button class="copy-button" data-account="kimheewon_account">Copy</button> <!-- Copy button --> </p>
            <button class="close-popup">Close</button>
        </div>
    </div>

    <div class="account-popup" data-idx="4">
        <div class="popup-content">
            <h3>Bride's Family's Account number</h3>
            <p>Woori Bank (Account Holder: Luong Thuc Anh)</p>
            <p class="account-number" id="bride-account">우리은행 1002035203849
            <button class="copy-button" data-account="bride-account">Copy</button> <!-- Copy button --> </p>
            <button class="close-popup">Close</button>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const remittanceButtons = document.querySelectorAll('.remittance-button');
            const accountPopups = document.querySelectorAll('.account-popup');
            const closePopupButtons = document.querySelectorAll('.close-popup');
            const copyButtons = document.querySelectorAll('.copy-button');

            remittanceButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const idx = button.getAttribute('data-idx');
                    document.querySelector(`.account-popup[data-idx="${idx}"]`).style.display = 'flex';
                });
            });

            closePopupButtons.forEach(button => {
                button.addEventListener('click', () => {
                    button.closest('.account-popup').style.display = 'none';
                });
            });

            // Copy account number functionality
            copyButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const accountId = button.getAttribute('data-account');
                    const accountText = document.getElementById(accountId).textContent;
                    const tempInput = document.createElement('input');
                    tempInput.style.position = 'absolute';
                    tempInput.style.left = '-9999px';
                    document.body.appendChild(tempInput);
                    tempInput.value = accountText;
                    tempInput.select();
                    document.execCommand('copy');
                    document.body.removeChild(tempInput);
                    alert("Account number copied to clipboard!");
                });
            });

            accountPopups.forEach(popup => {
                popup.addEventListener('click', (event) => {
                    if (event.target === popup) {
                        popup.style.display = 'none';
                    }
                });
            });
        });
    </script>
</body>
</html>
    </section>
</div>
