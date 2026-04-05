---
layout: about
title: Home
permalink: /
nav_order: 1
social: true
carousels:
  - images:
      - image: /assets/img/edinburgh-castle.jpg
        attribution: Kim Traynor, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons
      - image: /assets/img/arthurs-seat.jpg
        attribution: Tilmandralle, Public Domain
      - image: /assets/img/holyrood-palace.jpg
        attribution: Saffron Blaze, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons
      - image: /assets/img/calton-hill.jpg
        attribution: Saffron Blaze, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons
---

{% include carousel.html height="50" unit="%" duration="7" number="1" %}

<div class="container-fluid text-center my-5">
    <div class="row mb-2 align-items-center d">
        <div class="col d-none d-md-block">
            <i class="fa-solid fa-people-roof fa-2xl" style="color: #5EBC67;"></i>
        </div>
        <div class="col d-none d-md-block">
            <i class="fa-regular fa-calendar-days fa-2xl" style="color: #5EBC67;"></i>
        </div>
        <div class="col d-none d-md-block">
            <i class="fa-solid fa-map-location-dot fa-2xl" style="color: #5EBC67;"></i>
        </div>
        <div class="col d-none d-md-block">
            <i class="fa-solid fa-hourglass-half fa-2xl" style="color: #5EBC67;"></i>
        </div>
    </div>
    <div class="row align-items-center">
        <div class="col-12 col-md-3">
            <strong>Co-located with:</strong> <br> <a href="https://2026.eurosys.org/">EuroSys 2026</a>
        </div>
        <div class="col-12 col-md-3">
            <strong>Date:</strong> <br> 27th April 2026
        </div>
        <div class="col-12 col-md-3">
            <strong>Location:</strong> <br> Edinburgh, Scotland
        </div>
        <div class="col-12 col-md-3">
            <strong>Submission:</strong> <br> 24th of February 2026 
        </div>
    </div>
</div>

<style>
  .home-overview {
    margin-top: 2rem;
    align-items: flex-start;
  }

  .home-main-column {
    flex: 0 0 70%;
    max-width: 70%;
  }

  .home-news-column {
    flex: 0 0 30%;
    max-width: 30%;
  }

  .home-news-panel {
    background: #f7fbf7;
    border: 1px solid #d7e6d9;
    border-radius: 16px;
    padding: 1rem;
    box-shadow: 0 10px 25px rgba(21, 73, 32, 0.08);
  }

  .home-news-panel h3 {
    margin-bottom: 0.25rem;
    font-size: 1.2rem;
  }

  .home-news-scroll {
    max-height: 22rem;
    overflow-y: auto;
    padding-right: 0.3rem;
  }

  .home-news-item {
    padding: 0.75rem 0;
    border-top: 1px solid #dfe9e0;
  }

  .home-news-item:first-child {
    border-top: 0;
    padding-top: 0.25rem;
  }

  .home-news-date {
    display: inline-block;
    margin-bottom: 0.25rem;
    font-size: 0.82rem;
    font-weight: 600;
    color: #2f6f3e;
  }

  .home-news-item p {
    margin-bottom: 0;
    font-size: 0.95rem;
    line-height: 1.45;
  }

  @media (max-width: 767.98px) {
    .home-main-column,
    .home-news-column {
      flex: 0 0 100%;
      max-width: 100%;
    }

    .home-news-panel {
      margin-top: 1.5rem;
    }

    .home-news-scroll {
      max-height: none;
    }
  }
</style>

<div class="row home-overview">
  <div class="col-12 home-main-column">
    <p>
      The GreenSys workshop, colocated with EuroSys 2026, aims to foster dialogue between systems and Artificial Intelligence (AI) researchers to identify solutions to key sustainability challenges in AI, ensuring a more sustainable future for AI development and deployment.
    </p>

    <p>
      The rapid expansion of Machine Learning (ML) and AI applications has brought significant sustainability challenges. These advanced computational models, with their intensive processing and data requirements, have substantially increased the energy consumption and carbon footprint of backend IT infrastructures.
    </p>

    <p>
      The sustainability of large-scale AI systems is particularly challenging due to the diversity in hardware architectures, software stacks, and model complexities. This variability necessitates innovative approaches to enhance energy and carbon efficiency throughout the AI model lifecycle. Addressing these challenges requires advancements in AI algorithms, hardware, and runtime systems that oversee complex cyber-physical infrastructures. Solutions must be data-driven and incorporate cross-layer optimization across models, hardware, software stacks, and energy sources.
    </p>

    <p><strong>GreenSys 2026 will feature:</strong></p>

    <ol>
      <li><strong>Invited Talks:</strong> Presentations from leading industry practitioners and academic researchers.</li>
      <li><strong>Workshop Proceedings:</strong> Presentations of accepted papers from the workshop.</li>
      <li><strong>Lightning Talks:</strong> Short presentations showcasing emerging ideas, provocative visions, or lessons learned from practice.</li>
    </ol>

    <p>
      Join us at GreenSys in Edinburgh to contribute to the conversation and drive innovation towards a greener AI future.
    </p>
  </div>

  <div class="col-12 home-news-column">
    <aside class="home-news-panel">
      <h3>Latest News</h3>
      <p class="text-muted">Recent workshop updates</p>
      <div class="home-news-scroll">
        <div class="home-news-item">
          <span class="home-news-date">April 2, 2026</span>
          <p>The <a href="{{ '/program/' | relative_url }}">workshop program</a> is now available.</p>
        </div>
        <div class="home-news-item">
          <span class="home-news-date">April 1, 2026</span>
          <p><a href="{{ '/speakers/' | relative_url }}">Speaker details</a> have been added to the website.</p>
        </div>
        <div class="home-news-item">
          <span class="home-news-date">March 16, 2026</span>
          <p>Paper notifications have been released.</p>
        </div>
        <div class="home-news-item">
          <span class="home-news-date">February 24, 2026</span>
          <p>The paper submission deadline has passed. Submission details remain available on the <a href="{{ '/call-for-papers/' | relative_url }}">Call for Papers</a> page.</p>
        </div>
      </div>
    </aside>
  </div>
</div>
