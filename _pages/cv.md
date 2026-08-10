---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---
```html
<style>
  /* CV viewer */
  .cv-iframe {
    width: 100%;
    height: 1000px;
    border: none;
    display: block;
  }

  /* Mobile download section */
  .cv-mobile {
    display: none;
    text-align: center;
    padding: 40px 20px;
  }

  .download-cv {
    display: inline-block;
    padding: 12px 24px;
    background-color: #000;
    color: #fff !important;
    text-decoration: none;
    border-radius: 8px;
    font-weight: 600;
  }

  .download-cv:hover {
    background-color: #333;
  }

  /* Phones */
  @media (max-width: 768px) {
    .cv-iframe {
      display: none;
    }

    .cv-mobile {
      display: block;
    }
  }
</style>

<h2>My CV</h2>

<!-- Desktop / tablet: show the CV inside the page -->
<iframe
  class="cv-iframe"
  src="https://docs.google.com/document/d/13SmAmiU46pZHb3BbJMQa6AihOLB_16Hz/preview"
  title="CV"
  frameborder="0">
</iframe>

<!-- Phone: show a download button instead -->
<div class="cv-mobile">
  <p>View or download my CV:</p>

  <a
    href="https://docs.google.com/document/d/13SmAmiU46pZHb3BbJMQa6AihOLB_16Hz/export?format=pdf"
    class="download-cv">
    Download CV
  </a>
</div>
```
