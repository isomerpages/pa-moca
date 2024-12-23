---
title: MoCa Heritage Trail
permalink: /heritage-trail/
variant: markdown
description: ""
---
<div class="content-container">
  <div class="hero">
    <div class="isomer-image-wrapper">
      <img width="100%" alt="Moulmein-Cairnhill Heritage Trail" src="/images/Header_Image.jpg">
    </div>
    <h4>
      <strong>Explore the rich history and culture of Moulmein-Cairnhill</strong>
    </h4>
    <p>
      This interactive guide takes you through significant landmarks and sites,
      revealing the rich history and diverse culture of our town,
      Moulmein-Cairnhill. The heritage trail offers a unique way to explore and
      connect with our community's past and present.
    </p>
    <a class="cta-button" href="/featured-sites">
      <strong>Let's go!</strong>
      <span class="arrow">→</span>
    </a>
  </div>
  <p class="section-title">
    <strong>As you navigate through the trail, you'll discover:</strong>
  </p>
  <div class="card-grid">
    <a class="card" href="/heritage-sites/tan-chin-tuan-mansion">
      <img class="card-image" alt="Historic Buildings" src="/images/Historic_Buildings.jpg">
      <div class="card-bottom">
        <p><strong>Historic buildings</strong></p>
      </div>
    </a>
    <a class="card" href="/heritage-sites/flood-level-gauge">
      <img class="card-image" alt="Hidden Gems" src="/images/Hidden_Gems.jpg">
      <div class="card-bottom">
        <p><strong>Hidden gems</strong></p>
      </div>
    </a>
    <a class="card" href="/heritage-sites/masjid-abdul-gaffoor">
      <img class="card-image" alt="Cultural Sites" src="/images/Cultural_Sites.jpg">
      <div class="card-bottom">
        <p class="small"><strong>Cultural sites</strong></p>
      </div>
    </a>
    <a class="card" href="/heritage-sites/singapore-botanic-gardens">
      <img class="card-image" alt="Green Spaces" src="/images/Green_Spaces.jpg">
      <div class="card-bottom">
        <p><strong>Green spaces</strong></p>
      </div>
    </a>
    <a class="card" href="/heritage-sites/kk-womens-and-childrens-hospital">
      <img class="card-image" alt="Local Institutions" src="/images/Local_Institutions.jpg">
      <div class="card-bottom">
        <p>
          <span class="small"><strong>Local institutions</strong></span>
        </p>
      </div>
    </a>
    <a class="card" href="/heritage-sites/farrer-park-rc-fields-old-race-course">
      <img class="card-image" alt="Community Stories" src="/images/Community_Stories.jpg">
      <div class="card-bottom">
        <p><strong>Community stories</strong></p>
      </div>
    </a>
  </div>
</div>

<style>
  /* Base styles */
  .content-container {
    display: flex;
    flex-direction: column;
  }

  .hero {
    display: flex;
    flex-direction: column;
  }

  /* Button styles */
  .cta-button {
    display: flex;
    justify-content: space-between;
    padding: 14px 28px;
    background-color: #da1f34;
    color: #fff !important;
    border-radius: 12px;
    text-decoration: none !important;
    transition: opacity 0.2s;
    cursor: pointer;
    margin-top: 28px;
  }

  .cta-button > strong {
    color: #fff !important;
  }

  .cta-button:hover {
    opacity: 0.8;
  }

  /* Card grid layout - updated */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 14px;
  }

  .card {
    color: #484848;
    text-decoration: none !important;
    border: 1px solid #98a2b3;
    border-radius: 6px;
    overflow: hidden;
    transition: opacity 0.2s;
    margin: 0 !important;
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
    background-color: #fff;
    padding: 8px 28px;
    line-height: 20px;
  }

  .section-title,
  .card-bottom > p {
    line-height: 28px !important;
  }
</style>
