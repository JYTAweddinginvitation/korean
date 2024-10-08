---
layout: description
title: Sumup
permalink: /sumup/
---
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

<!-- Inline CSS to force max-width of 480px -->
<style>
    body {
        margin: 0 auto;
        max-width: 480px;
    }

    /* Center content for larger screens */
    .container {
        margin: 0 auto;
        width: 100%;
        max-width: 480px; /* Maximum width is always 480px */
        padding: 0 10px; /* Add padding to ensure content doesn't touch edges */
    }


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
