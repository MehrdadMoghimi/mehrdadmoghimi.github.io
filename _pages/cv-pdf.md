---
layout: single
permalink: /cv-pdf/
author_profile: false
header:
  overlay_filter: "0.5"
  show_overlay_excerpt: false
title: " "
---

<div class="cv-container">
  <div class="cv-header">
    <h1>Mehrdad Moghimi - CV</h1>
    <div class="cv-actions">
      <a href="../files/cv.pdf" class="btn btn--primary" download>
        <i class="fas fa-download"></i> Download PDF
      </a>
      <a href="../files/cv.pdf" class="btn btn--secondary" target="_blank">
        <i class="fas fa-external-link-alt"></i> Open in New Tab
      </a>
    </div>
  </div>
  
  <div class="pdf-viewer">
    <iframe src="../files/cv.pdf" width="100%" height="800px" type="application/pdf">
      <p>Your browser does not support PDFs. 
        <a href="../files/cv.pdf">Download the PDF</a> to view it.
      </p>
    </iframe>
  </div>
</div>

<style>
.cv-container {
  max-width: 100%;
  margin: 0 auto;
}

.cv-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 2rem;
  padding: 1rem;
  background: var(--global-bg-color, #f8f9fa);
  border-radius: 8px;
  border: 1px solid var(--global-border-color, #dee2e6);
}

.cv-header h1 {
  margin: 0;
  font-size: 1.5rem;
  color: var(--global-text-color, #333);
}

.cv-actions {
  display: flex;
  gap: 1rem;
}

.cv-actions .btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  text-decoration: none;
  border-radius: 4px;
  font-weight: 500;
  transition: all 0.2s ease;
}

.btn--primary {
  background-color: #5bc0de;
  color: white;
  border: 2px solid #5bc0de;
}

.btn--primary:hover {
  background-color: #31b0d5;
  color: white;
  border-color: #31b0d5;
}

.btn--secondary {
  background-color: #5bc0de;
  color: white;
  border: 2px solid #5bc0de;
}

.btn--secondary:hover {
  background-color: #31b0d5;
  color: white;
  border-color: #31b0d5;
}

/* Dark mode specific styling for buttons */
html[data-theme="dark"] .btn--primary {
  background-color: #5bc0de;
  color: white;
  border-color: #5bc0de;
}

html[data-theme="dark"] .btn--primary:hover {
  background-color: #31b0d5;
  color: white;
  border-color: #31b0d5;
}

html[data-theme="dark"] .btn--secondary {
  background-color: #5bc0de;
  color: white;
  border-color: #5bc0de;
}

html[data-theme="dark"] .btn--secondary:hover {
  background-color: #31b0d5;
  color: white;
  border-color: #31b0d5;
}

.pdf-viewer {
  border: 1px solid var(--global-border-color, #dee2e6);
  border-radius: 8px;
  overflow: hidden;
  background: white;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.pdf-viewer iframe {
  display: block;
  border: none;
  width: 100%;
  min-height: 800px;
}

/* Dark mode adjustments */
html[data-theme="dark"] .cv-header {
  background: var(--global-bg-color);
  border-color: var(--global-border-color);
}

html[data-theme="dark"] .pdf-viewer {
  border-color: var(--global-border-color);
  background: var(--global-bg-color);
}

/* Responsive design */
@media (max-width: 768px) {
  .cv-header {
    flex-direction: column;
    text-align: center;
    gap: 1rem;
  }
  
  .cv-header h1 {
    font-size: 1.25rem;
  }
  
  .cv-actions {
    flex-direction: column;
    width: 100%;
  }
  
  .cv-actions .btn {
    justify-content: center;
  }
  
  .pdf-viewer iframe {
    min-height: 600px;
  }
}
</style>
