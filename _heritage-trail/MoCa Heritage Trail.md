---
title: MoCa Heritage Trail
permalink: /heritage-trail/
variant: markdown
description: ""
---
<div class="content-container">
  <div class="hero">
    <img width="100%" alt="Moulmein-Cairnhill Heritage Trail" src="/images/Header_Image.jpg">
    <h4>
      <strong>Explore the rich history and culture of Moulmein-Cairnhill</strong>
    </h4>
    <p>
      This interactive guide takes you through significant landmarks and sites,
      revealing the rich history and diverse culture of our town,
      Moulmein-Cairnhill. The heritage trail offers a unique way to explore and
      connect with our community's past and present.
    </p>
    <a class="cta-button" href="/heritage-trail/featured-sites">
      <p class="button-text"><strong>Let's go!</strong></p>
      <p class="button-text"><span class="arrow">→</span></p>
    </a>
  </div>
  <p class="section-title">
    <strong>As you navigate through the trail, you'll discover:</strong>
  </p>
  <div class="card-grid">
    <a class="card" href="/heritage-trail/black-white-bungalows">
      <img class="card-image" alt="Historic Buildings" src="/images/Historic_Buildings.jpg">
      <div class="card-bottom">
        <strong>Historic buildings</strong>
      </div>
    </a>
    <a class="card" href="/heritage-trail/mount_emily_swimming_pool_and_coat_of_arms">
      <img class="card-image" alt="Hidden Gems" src="/images/Hidden_Gems.jpg">
      <div class="card-bottom">
        <strong>Hidden gems</strong>
      </div>
    </a>
    <a class="card" href="/heritage-trail/masjid-tasek-utara">
      <img class="card-image" alt="Cultural Sites" src="/images/Cultural_Sites.jpg">
      <div class="card-bottom">
        <strong>Cultural sites</strong>
      </div>
    </a>
    <a class="card" href="/heritage-trail/singapore-botanic-gardens">
      <img class="card-image" alt="Green Spaces" src="/images/Green_Spaces.jpg">
      <div class="card-bottom">
        <strong>Green spaces</strong>
      </div>
    </a>
    <a class="card" href="/heritage-trail/kk-womens-and-childrens-hospital">
      <img class="card-image" alt="Local Institutions" src="/images/Local_Institutions.jpg">
      <div class="card-bottom">
        <strong>Local institutions</strong>
      </div>
    </a>
    <a class="card" href="/heritage-trail/birthplace_of_lee_kuan_yew">
      <img class="card-image" alt="Community Stories" src="/images/Community_Stories.jpg">
      <div class="card-bottom">
        <strong>Community stories</strong>
      </div>
    </a>
  </div>
</div>

<style>
  /* Layout containers */
  .content-container {
    display: flex;
    flex-direction: column;
  }

  .hero {
    display: flex;
    flex-direction: column;
  }

  /* Typography */
  .section-title,
  .card-bottom > p {
    line-height: 28px !important;
  }

  /* CTA Button */
  .cta-button {
    display: flex;
    justify-content: space-between;
    margin-top: 28px;
    padding: 14px 28px;
    background-color: #d0021b;
    border-radius: 12px;
    color: #fff !important;
    text-decoration: none !important;
    cursor: pointer;
    width: fit-content;
    gap: 14px;
  }

  .cta-button:hover {
    background-color: #9d0214;
  }

  .button-text,
  .button-text > strong,
  .cta-button > strong {
    color: #fff !important;
    margin: 0 !important;
  }

  /* Card Grid */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 14px;
  }

  .card {
    margin: 0 !important;
    color: #484848;
    text-decoration: none !important;
    border: 1px solid #98a2b3;
    border-radius: 6px;
    overflow: hidden;
    transition: opacity 0.2s;
  }

  .card:hover {
    opacity: 0.8;
  }

  .card-image {
    width: 100%;
    aspect-ratio: 2.39;
    object-fit: cover;
  }

  .card-bottom {
    padding: 8px 28px;
    background-color: #fff;
    line-height: 20px;
  }

  /* Responsive */
  @media screen and (max-width: 375px) {
    .card-grid {
      grid-template-columns: 1fr; /* Switch to single column */
    }
  }
</style>
