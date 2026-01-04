---
layout: post
title: Two articles became available in IEEE Transactions.


images:
  - /assets/img/2024-03-15-X-CANIDS.png
  - /assets/img/2024-03-15-AERO.png
---

I'm very proud of the fact that my two papers---X-CANIDS and AERO---were just published in *IEEE Transactions on Vehicular Technology* and *IEEE Transactions on Industrial Informatics*, respectively.

<!--more-->

X-CANIDS is the first intrusion detection system (IDS) for a Controller Area Network-based in-vehicle network that provides interpretations (i.e., explanations) of detected intrusions. Specifically, it identifies compromised signals (*e.g.,* RPM, intake air temperature) and ECUs. It is designed unsupervised, so automakers can leverage X-CANIDS before publishing their vehicles in the wild.

AERO is the first unsupervised IDS for automotive Ethernet. AERO is carefully designed to be robust, responsive, and accurate to be enough to protect vehicles from zero-day attacks.

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

See more on my
[publications](./publications.html) page and
[Google Scholar profile](https://scholar.google.com/citations?user=9SOKjp4AAAAJ).