---
layout: page
title: Education
permalink: /education/
nav: true
nav_order: 6
_styles: |
  .post-header {
    display: none;
  }

  .education {
    margin-top: 1.5rem;
    padding: clamp(1rem, 3vw, 2rem);
    border: 1px solid #3f4854;
    border-radius: 18px;
    background:
      radial-gradient(circle at top right, rgba(125, 211, 252, 0.12), transparent 32%),
      linear-gradient(145deg, #11151a 0%, #242b33 100%);
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.22);
  }

  .education .card {
    margin: 0 0 1rem !important;
    overflow: hidden;
    border: 1px solid rgba(255, 255, 255, 0.11);
    border-left: 4px solid #7dd3fc;
    border-radius: 13px;
    background: rgba(15, 18, 22, 0.82);
    color: #e8edf2;
    box-shadow: 0 7px 20px rgba(0, 0, 0, 0.18);
    transition: transform 180ms ease, border-color 180ms ease, box-shadow 180ms ease;
  }

  .education .card:last-child {
    margin-bottom: 0 !important;
  }

  .education .card:hover {
    transform: translateY(-3px);
    border-color: rgba(125, 211, 252, 0.58);
    box-shadow: 0 12px 26px rgba(0, 0, 0, 0.28);
  }

  .education .card-body {
    padding: clamp(1rem, 2.5vw, 1.5rem);
  }

  .education .card-title {
    color: #ffffff;
    letter-spacing: 0.01em;
  }

  .education .card-text {
    margin-bottom: 0.35rem;
    color: #cbd3dc;
  }

  .education .card-text strong {
    color: #7dd3fc;
  }

  .education img {
    padding: 10px;
    border-radius: 12px;
    background: #ffffff;
    box-shadow: 0 5px 14px rgba(0, 0, 0, 0.3);
    transition: transform 180ms ease;
  }

  .education a:hover img {
    transform: scale(1.04);
  }

  @media (max-width: 575.98px) {
    .education {
      border-radius: 13px;
    }

    .education .card {
      border-left-width: 3px;
    }
  }
---

<div class="education">
  <div class="card mt-3">
    <div class="card-body">
      <div class="row align-items-center">
        <div class="col-12 col-sm-3 text-center mb-3 mb-sm-0">
          <a href="https://www.universityofgalway.ie/" target="_blank" rel="noopener">
            <img src="https://stories.nuigalway.ie/prof-caroline-mcintosh/assets/KVZKw6d9kZ/university_of_galway_logo__positive_landscape_stacked-4096x2537.png" alt="University of Galway logo" style="width: 96px; height: 96px; object-fit: contain;">
          </a>
        </div>
        <div class="col-12 col-sm-9">
          <h5 class="card-title" style="font-size: 1rem; line-height: 1.35; margin-bottom: 0.5rem;"><strong><em>PhD in Electrical and Electronic Engineering</em></strong></h5>
          <p class="card-text"><em>University of Galway, Ireland</em></p>
          <p class="card-text"><strong>Completed:</strong> 2024</p>
        </div>
      </div>
    </div>
  </div>

  <div class="card mt-3">
    <div class="card-body">
      <div class="row align-items-center">
        <div class="col-12 col-sm-3 text-center mb-3 mb-sm-0">
          <a href="https://www.jbnu.ac.kr/en/" target="_blank" rel="noopener">
            <img src="https://www.timeshighereducation.com/cms-academic/sites/default/files/migrated_institution_logos/logo_jeonbuk-natonal-uni.jpg" alt="Jeonbuk National University logo" style="width: 96px; height: 96px; object-fit: contain;">
          </a>
        </div>
        <div class="col-12 col-sm-9">
          <h5 class="card-title" style="font-size: 1rem; line-height: 1.35; margin-bottom: 0.5rem;"><strong><em>MS in Electronics and Information Engineering</em></strong></h5>
          <p class="card-text"><em>Chonbuk National University, South Korea</em></p>
          <p class="card-text"><strong>Completed:</strong> 2016</p>
        </div>
      </div>
    </div>
  </div>

  <div class="card mt-3">
    <div class="card-body">
      <div class="row align-items-center">
        <div class="col-12 col-sm-3 text-center mb-3 mb-sm-0">
          <a href="https://www.bgsbu.ac.in/" target="_blank" rel="noopener">
            <img src="https://successphd.com/wp-content/uploads/2025/12/Baba-Ghulam-Shah-Badshah-University-logo.png" alt="Baba Ghulam Shah Badshah University logo" style="width: 96px; height: 96px; object-fit: contain;">
          </a>
        </div>
        <div class="col-12 col-sm-9">
          <h5 class="card-title" style="font-size: 1rem; line-height: 1.35; margin-bottom: 0.5rem;"><strong><em>Bachelor of Technology in Information Technology Engineering</em></strong></h5>
          <p class="card-text"><em>Baba Ghulam Shah Badshah University, India</em></p>
          <p class="card-text"><strong>Completed:</strong> 2012</p>
        </div>
      </div>
    </div>
  </div>
</div>
