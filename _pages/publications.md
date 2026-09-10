---
layout: page
permalink: /publications/
title: Research
nav: true
nav_order: 2
---

<style>
  .research-banner {
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }

  .research-banner img {
    display: block;
    width: 100%;
    max-width: 30rem;
    aspect-ratio: 3 / 2;
    object-fit: cover;
    margin: 0 auto;
    border-radius: 6px;
  }
  .research-columns {
    display: grid;
    grid-template-columns: minmax(0, 1fr) 15rem;
    gap: 2rem;
    align-items: start;
  }

  .research-publications {
    min-width: 0;
  }

  .research-activities {
    min-width: 0;
    padding-left: 1.5rem;
    border-left: 1px solid var(--global-divider-color, #dce2e8);
    font-size: 0.95rem;
    line-height: 1.65;
    overflow-wrap: anywhere;
  }

  .post article .research-activities h2 {
    margin-top: 0;
    font-size: 1.5rem;
    color: #17365d;
  }

  .research-activities ul {
    padding-left: 1.1rem;
  }

  .research-activities li {
    margin-bottom: 0.85rem;
  }

  .post article .publications-heading {
    margin-top: 0;
  }
  
  @media (max-width: 850px) {
    .research-columns {
      grid-template-columns: minmax(0, 1fr);
    }

    .research-activities {
      padding-left: 0;
      padding-top: 1.5rem;
      border-left: 0;
      border-top: 1px solid var(--global-divider-color, #dce2e8);
    }
  }
</style>

<img
class="research-banner"
src="{{ '/assets/img/bamboo.png' | relative_url }}"
alt="A tree with aerial roots reaching toward the ground, evoking the growth of a research programme."
loading="eager"

>

<div class="research-columns">
  <div class="research-publications">
    <h2 class="publications-heading">Publications</h2>
    {% include bib_search.liquid %}
    <div class="publications">
      {% bibliography %}
    </div>
  </div>

  <aside class="research-activities" aria-labelledby="professional-activities-title">
    <h2 id="professional-activities-title">Professional Activities</h2>
    <p>Some events and reading groups I have organized:</p>
    <ul>
      <li><a href="https://algorithmiclearningtheory.org/alt2023/">ALT 2023</a></li>
      <li><a href="{{ '/assets/research/causalityrg/causalityrg.html' | relative_url }}">Causality &amp; Algorithms Virtual Reading Group</a></li>
      <li><a href="https://events.csa.iisc.ac.in/LAC15/">Symposium on Learning, Algorithms and Complexity</a></li>
      <li><a href="{{ '/assets/research/fourier/' | relative_url }}">FOURIER</a></li>
      <li><a href="{{ '/assets/research/hofa/' | relative_url }}">Higher-Order Fourier Analysis</a></li>
    </ul>
    <p>See <a href="{{ '/assets/pdf/cur-cv.pdf' | relative_url }}">my CV (PDF)</a> for more information.</p>
  </aside>
</div>

## Travels

<iframe
  class="travel-map"
  src="https://www.google.com/maps/d/embed?mid=1AKAB09AotmBXAJ8pDDTPnv6fx9c"
  title="Arnab Bhattacharyya's travel map"
  width="930"
  height="440"
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade"
></iframe>

[Open the travel map in a new window](https://www.google.com/maps/d/embed?mid=1AKAB09AotmBXAJ8pDDTPnv6fx9c)
