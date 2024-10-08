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
    @media (min-width: 481px) {
        .container {
            margin: 0 auto;
            max-width: 480px; /* Limit width to 480px on larger screens */
            padding: 0 10px;
        }
    }

    /* Make sure smaller screens (phones) use full width */
    @media (max-width: 480px) {
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
        background-color: #333;
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
        color: white;
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
        {% include_relative gallery.md %}
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
