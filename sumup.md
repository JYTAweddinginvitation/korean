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

<!-- Home Section -->
<section id="home">
    {% include _layout/home.html %}
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
    {% include _layout/contact.html %}
</section>
