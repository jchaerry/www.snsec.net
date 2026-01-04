---
layout: post
title: First submission, at the end of the day on Thursday, AoE

images:
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 001.jpeg
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 002.jpeg
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 003.jpeg
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 005.jpeg
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 007.jpeg
  - /assets/img/2025-12-05-conference-submission/KakaoTalk_Photo_2025-12-12-10-12-59 008.jpeg

---
Chaeri, Chaeyoung, and I submitted our very first paper to a cybersecurity conference. Hope it went through well.

<!--more-->

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
