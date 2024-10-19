---
layout: home
home_text: request the pleasure of your company to celebrate our marriage
title: Junyoung + Thuc Anh
---

<head>
  <!-- Google Fonts for Noto Serif KR -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@200..900&display=swap" rel="stylesheet">

  <!-- Other metadata or stylesheets -->
</head>



<!-- Sticky Header with Navigation Links -->
<header class="sticky-header">
    <nav>
        <ul>
            <li><a href="#home">홈</a></li>
            <li><a href="#about">초대장</a></li>
            <li><a href="#gallery">갤러리</a></li>
            <li><a href="#location">오시는곳</a></li>
            <li><a href="#contact">마음전할곳</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <!-- Home Section -->
    <section id="home">
        {% include home.html %}
    </section>

<hr style="margin-top: 30px;">

    <!-- About Section -->
    <section id="about">
        <h2 style="text-align: center;">초대장</h2>
        <div style="text-align: center;">
            <img src="{{'/img/about.jpeg' | relative_url }} " alt="img" style="width: 80%; max-width: 600px; height: auto;">
        </div>

        <div style="text-align: center;">
            <p>두 다른 나라의 아름다운 인연이</p>
            <p>한 인연의 사랑으로 이어졌습니다</p>
            <p>·</p>
            <p>언어와 문화가 다른 두 사람이지만</p>
            <p>서로를 존중하고 배려하며 살아가겠습니다</p>
            <p>·</p>
            <p>공항에서 수없이 아쉬운 이별을 하며</p>
            <p>펑펑 울었던 저희 두 사람,</p>
            <p>이제는 평생 떨어지지 않기로</p>
            <p>같은 비행기에 오르기로 약속했습니다</p>
            <p>·</p>
            <p>저희들의 새로운 여정에 함께해 주신다면</p>
            <p>더없는 기쁨으로 간직하겠습니다.</p>
            <p>·</p>
            <p>·</p>
            <p><strong>김제중·김희원</strong>의 차남 <strong>준영</strong> </p>
            <p><strong>르엉국빈·응우옌종안두윗</strong>의 차녀 <strong>툭안</strong></p>
            <p>·</p>
            <p>장소 : <strong><a href="#location">La Vela Saigon</a></strong></p>
            <p>시간 : 2025년 1월 11일 토요일, 오후 6시 30분</p>
            <img src="/homepage/calender.jpg" alt="calender" style="width: 420px; height: 420px; display: block; margin: 0 auto;">

        </div>
    </section>

    <div class="countdown-container">
        <p style="text-align: center;" id="countdown-message"></p>
    </div>

    <script>
        // Function to calculate and update the days left or passed
        function updateCountdown() {
            const weddingDate = new Date("January 11, 2025").getTime();
            const today = new Date().getTime();
            const timeDifference = weddingDate - today;

            const daysDifference = Math.ceil(timeDifference / (1000 * 60 * 60 * 24));

            let countdownMessage = "";
            if (daysDifference > 0) {
                countdownMessage = `준영, 안의 결혼식이 ${daysDifference}일 남았습니다`;
            } else if (daysDifference === 0) {
                countdownMessage = "오늘은 준영, 안의 결혼식입니다";
            } else {
                countdownMessage = `준영, 안의 결혼식이 ${Math.abs(daysDifference)}일 지났습니다`;
            }

            // Update the countdown display
            document.getElementById("countdown-message").textContent = countdownMessage;
        }

        // Call the function to update the countdown
        updateCountdown();
    </script>
  <hr>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2 style="text-align: center;">갤러리</h2>
        {% include_relative gallery.md %}
    </section>

  <hr>

    <!-- Location Section -->
    <section id="location">
        <h2 style="text-align: center;">오시는 곳</h2>
        <div style="text-align: center;">
            <img src="/homepage/mapimage.jpeg" alt="img" style="width: 80%; max-width: 600px; height: auto;">
        </div>

        <h3 style="text-align: center;">LA VELA SAIGON HOTEL</h3>
        <h3 style="text-align: center;">라벨라 호텔 사이공</h3>

        <h4 style="text-align: center;">5층 Jupiter Hall 주피터 홀</h4>

        <p style="text-align: center;"><a href="tel:+8402836222280">전화번호 : +84 (0) 28 3622 2280</a></p>
        <p style="text-align: center;"><a href="mailto:lavelahotel@lavelasaigon.com">이메일 : lavelahotel@lavelasaigon.com</a></p>
        <p style="text-align: center;"><a href="https://lavelasaigon.com/">웹사이트</a></p>

        <p style="text-align: center;">
            <a href="https://www.google.co.kr/maps/place/%EB%9D%BC+%EB%B2%A8%EB%9D%BC+%EC%82%AC%EC%9D%B4%EA%B3%B5+%ED%98%B8%ED%85%94/@10.7886761,106.6828959,17z/data=!3m1!4b1!4m9!3m8!1s0x31752f2d1f5cd9e7:0xd2284b6940329fcf!5m2!4m1!1i2!8m2!3d10.7886708!4d106.6854708!16s%2Fg%2F11h9kpyf0z?hl=ko&entry=ttu">
                <strong>구글맵 링크</strong>
            </a>
        </p>

    </section>

  <hr>

    <!-- Contact Section -->
    <section id="contact">
        <h2 style="text-align: center;">연락처</h2>
        {% include contact.html %}   
    </section>


   <hr>
<!-- Add this after the last <hr> -->
<section id="language-selection">
    <h3 style="text-align: center;">Language</h3>
    <div style="text-align: center;">
        <a href="https://jytaweddinginvitation.github.io/homepagekr/">
            <img src="/homepage/img/kr.JPG" alt="Korean Language" style="width: 35px; height: 35px; margin-right: 10px;">
        </a>
        <a href="https://jytaweddinginvitation.github.io/homepage/">
            <img src="/homepage/img/eng.JPG" alt="English Language" style="width: 35px; height: 35px; margin-right: 10px;">
        </a>
        <a href="https://jytaweddinginvitation.github.io/homepagevn/">
            <img src="/homepage/img/vn.JPG" alt="Vietnamese Language" style="width: 35px; height: 35px;">
        </a>
    </div>
</section>
   
</div>

<!-- Additional Styling -->
<style>
    /* Center-align section titles */
    section h2 {
        text-align: center;
    }

    /* Change hyperlink color to black */
    a {
        color: black;
        text-decoration: none; /* Optional: Remove underline */
    }

    a:hover {
        text-decoration: underline; /* Optional: Add underline on hover */
    }
</style>
