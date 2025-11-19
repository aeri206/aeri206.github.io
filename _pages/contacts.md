---
layout: page
title: contacts
permalink: /contacts/
nav: false
nav_order: 3
---


<div class="contacts-page">
  <p style="margin-bottom: 1.5em;">
    <i class="fas fa-comment-dots"></i> Feel free to contact me for research discussions, collaborations, opportunities, or anything else!
  </p>
  
  <div style="font-size: 1.5em; display: flex; gap: 1em; align-items: center;">
    <a href="mailto:{{ site.email }}" title="Email"><i class="fas fa-envelope"></i></a>
    <a href="https://x.com/aericho_" target="_blank" rel="noopener noreferrer" title="X"><i class="fab fa-twitter"></i></a>
    {% if site.github_username %}
      <a href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener noreferrer" title="GitHub"><i class="fab fa-github"></i></a>
    {% endif %}
    {% if site.linkedin_username %}
      <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank" rel="noopener noreferrer" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    {% endif %}
    {% if site.scholar_userid %}
      <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}" target="_blank" rel="noopener noreferrer" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    {% endif %}
  </div>
</div>
