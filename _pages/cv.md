---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---
<style>
/* Wrapper for the embedded CV */
.cv-embed-wrapper {
  width: 100%;
  display: flex;
  justify-content: center;
  margin: 1.5rem 0;
}

/* The iframe itself */
.cv-embed-wrapper iframe {
  width: 100%;
  max-width: 900px;
  height: 85vh;           /* scales with viewport instead of a fixed px height */
  max-height: 1200px;
  border: 1px solid #ccc;
  border-radius: 8px;
  -webkit-overflow-scrolling: touch;  /* smooth momentum scroll on iOS */
}

/* Fallback download link (shown on all devices, below the embed) */
.cv-download {
  text-align: center;
  margin: 1rem 0 2rem;
}
.cv-download a {
  display: inline-block;
  padding: 10px 18px;
  background: #2a7ae2;
  color: #ffffff;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.95rem;
  font-weight: 500;
}

/* Tighten up spacing on small screens */
@media (max-width: 768px) {
  .cv-embed-wrapper iframe {
    height: 75vh;
    border-radius: 6px;
  }
}
</style>

<!-- Embedded CV (desktop + iPhone) -->
<div
