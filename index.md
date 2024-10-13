---
layout: home
home_text: 저희의 결혼식에 소중한 당신을 초대합니다
title: Junyoung + Thuc Anh
---

<!-- Sticky Header with Navigation Links -->
<header class="sticky-header">
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
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

  <hr>

    <!-- About Section -->
    <section id="about">
        <h2 style="text-align: center;">About</h2>
        <div style="text-align: center;">
            <img src="{{'/img/about.jpeg' | relative_url }} " alt="img" style="width: 80%; max-width: 600px; height: auto;">
        </div>

        <div style="text-align: center;">
            <p>1월의 어느날</p>
            <p></p>
            <p>오랜 시간 만나온 저희 두사람</p>
            <p></p>
            <p>이제 평생을 함께 하고자 합니다</p>
            <p></p>
            <p>믿음과 사랑을 약속하는 자리에</p>
            <p></p>
            <p>늘 곁에서 아껴주셨던</p>
            <p></p>
            <p>소중한 분들을 모시고자 합니다</p>
            <p></p>
            <p>부디 귀한 발걸음 하시어</p>
            <p></p>
            <p>저희 두사람의 앞날을</p>
            <p></p>
            <p>축복해주시면 감사하겠습니다</p>
            <p></p>
            <p>장소 : La Vela Saigon</p>
            <p></p>
            <p>시간 : 2025년 1월 11일 토요일, 오후 7시</p>
            <p></p>
            <p><strong>김제중·김희원</strong>의 차남 <strong>준영</strong> </p>
            <p></p>
            <p><strong>Luong Quoc Vinh·Nguyen Trong Anh Tuyet</strong>의 차녀 <strong>Thuc Anh</strong> </p>
        </div>
    </section>

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

        <h3 style="text-align: center;">LA VELA SAIGON HOTEL 라벨라 호텔 사이공</h3>
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
        <h2 style="text-align: center;">마음 전하실 곳</h2>
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
