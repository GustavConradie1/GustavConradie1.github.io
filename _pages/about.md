---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at the University of Cambridge supervised by Matthew Colbrook and Nicolas Boullé.

My background is predominantly in analysis and numerical analysis. The main topic of my PhD so far is verified data-driven computations for Koopman operators, including spectral properties and control, but I am also interested in contour methods, spectral geometry and numerical solution to PDEs.

<style>
.about-figures {
  margin-top: 1.5rem;
}

.about-figures-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.about-figure {
  margin: 0;
  border: 1px solid #dde3ea;
  border-radius: 10px;
  padding: 0.65rem;
  background: #fff;
  box-shadow: 0 2px 6px rgba(15, 23, 42, 0.06);
}

.about-figure-link {
  display: block;
  color: inherit;
  text-decoration: none;
}

.about-figure-link,
.about-figure-link:hover,
.about-figure-link:focus,
.about-figure-link * {
  text-decoration: none !important;
}

.about-figure-link:hover figcaption {
  text-decoration: underline;
}

.about-figure img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 260px;
  object-fit: contain;
  background: #f8fafc;
  border-radius: 6px;
}

.about-figure figcaption {
  margin-top: 0.5rem;
  font-size: 0.92rem;
  line-height: 1.35;
  color: #3f5162;
}

.about-figure--wide {
  grid-column: 1 / -1;
}

.about-figure--wide img {
  max-height: 420px;
}

@media (max-width: 900px) {
  .about-figures-grid {
    grid-template-columns: 1fr;
  }

  .about-figure img {
    max-height: none;
  }

  .about-figure--wide img {
    max-height: none;
  }
}
</style>

<section class="about-figures" aria-label="Selected figures from recent papers">
  <div class="about-figures-grid">
    <figure class="about-figure about-figure--wide">
      <a class="about-figure-link" href="https://arxiv.org/abs/2603.15091">
        <img src="/files/trustworthy_koopman.png" alt="Figure from Koopman operator learning work">
        <figcaption>Trustworthy Koopman operator learning</figcaption>
      </a>
    </figure>
  </div>
</section>
