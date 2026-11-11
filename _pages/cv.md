---
layout: archive
title: "cv"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---
{% comment %}
  To update your CV: replace files/Chatterjee_CV.pdf with the new PDF
  (keep the same file name), then git add / commit / push.
{% endcomment %}
{% include base_path %}
{% assign cv_pdf = base_path | append: "/files/Chatterjee_CV.pdf" %}

<p class="cv-actions">
  <a href="{{ cv_pdf }}" class="cv-btn" target="_blank" rel="noopener">Download PDF</a>
  <span class="cv-updated">Last updated November 2026</span>
</p>

<div class="cv-embed">
  <iframe src="{{ cv_pdf }}#view=FitH&navpanes=0" title="Srishti Chatterjee CV" loading="lazy"></iframe>
</div>

<p class="cv-fallback">If the CV doesn't appear above, <a href="{{ cv_pdf }}" target="_blank" rel="noopener">open it in a new tab</a>.</p>
