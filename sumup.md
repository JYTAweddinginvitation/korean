---
layout: description
title: Sumup
permalink: /sumup/
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

    /* Only apply max-width for larger screens (desktops) */
    @media (min-width: 376px) {
        .container {
            margin: 0 auto;
            max-width: 375px; /* Limit width to 480px on larger screens */
            padding: 0 10px;
        }
    }

    /* Make sure smaller screens (phones) use full width */
    @media (max-width: 375px) {
        .container {
            width: 100%; /* Use full width for small devices */
            padding: 0 10px; /* Add padding so it doesn’t touch edges */
        }
    }

    /* Sticky Header Styles */
    .sticky-header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: white;
        padding: 10px 0;
        z-index: 1000;
    }

    .sticky-header nav ul {
        display: flex;
        justify-content: center;
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
        {% include_relative about.md %}
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
        {% include_relative location.md %}
    </section>

    ---

    <!-- Contact Section -->
    <section id="contact">
        {% include contact.html %}
    </section>
</div>
