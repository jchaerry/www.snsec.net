---
layout: post
title: Teaching Award in Korea University

images:
  - /assets/img/2024-11-28-TeachingAward/ceremony1.jpeg 
  - /assets/img/2024-11-28-TeachingAward/ceremony2.jpeg
  - /assets/img/2024-11-28-TeachingAward/+0I4A2059.jpg
  - /assets/img/2024-11-28-TeachingAward/+0I4A2125.jpg
  - /assets/img/2024-11-28-TeachingAward/+0I4A2130.jpg
  # - /assets/img/2024-11-28-TeachingAward/ceremony3.png 
  - /assets/img/2024-11-28-TeachingAward/ceremony4.png 
  - /assets/img/2024-11-28-TeachingAward/ceremony5.png
---

My lecture---CYDF311: Attack & Defense: Theory and Practice---has been selected as one of the best lectures in Spring 2023 in Korea University.

<!--more-->

<div class="card-columns">
    {% for img in page.images %}
    <div class="card" data-toggle="modal" data-target="#exampleModal" data-img="{{ img }}">
        <img class="card-img-top" src="{{ img }}" />
    </div>
    {% endfor %}
</div>

<div class="modal fade" id="exampleModal">
  <div class="modal-dialog modal-lg modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-body">
        <img class="modal-img w-100" />
      </div>
    </div>
  </div>
</div>

<script type="text/javascript">
  $(document).ready(function() {
    $('#exampleModal').on('show.bs.modal', function (event) {
      var button = $(event.relatedTarget)
      var img = button.data('img')
      var modal = $(this)
      modal.find('.modal-img').attr('src', img)
    })
  })
</script>
