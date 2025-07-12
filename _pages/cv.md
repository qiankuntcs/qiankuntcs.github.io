---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-container {
  position: relative;
  margin-bottom: 20px;
}

.cv-actions {
  position: absolute;
  top: 10px;
  right: 10px;
  z-index: 100;
  display: flex;
  gap: 10px;
}

.cv-btn {
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid #ddd;
  padding: 8px 16px;
  text-decoration: none;
  border-radius: 4px;
  font-size: 0.9em;
  color: #333;
  backdrop-filter: blur(5px);
  transition: all 0.2s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.cv-btn:hover {
  background: rgba(52, 152, 219, 0.9);
  color: white;
  text-decoration: none;
}

.cv-btn i {
  margin-right: 5px;
}

.pdf-viewer {
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

@media screen and (max-width: 768px) {
  .cv-actions {
    position: static;
    justify-content: center;
    margin-bottom: 15px;
  }
  
  .cv-btn {
    font-size: 0.85em;
    padding: 6px 12px;
  }
}
</style>

<div class="cv-container">
  <div class="cv-actions">
    <a href="{{ base_path }}/files/CV.pdf" class="cv-btn" download>
      <i class="fa fa-download" aria-hidden="true"></i>Download
    </a>
    <a href="{{ base_path }}/files/CV.pdf" target="_blank" class="cv-btn">
      <i class="fa fa-external-link" aria-hidden="true"></i>Open
    </a>
  </div>
  
  <div class="pdf-viewer">
    <object data="{{ base_path }}/files/CV.pdf" type="application/pdf" width="100%" height="800px">
      <p style="text-align: center; padding: 40px; color: #666;">
        Your browser doesn't support PDF viewing. 
        <a href="{{ base_path }}/files/CV.pdf" style="color: #3498db;">Click here to download the PDF</a>.
      </p>
    </object>
  </div>
</div>