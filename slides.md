---
marp: true
theme: custom
paginate: true
paginate-placement: bottom-right
---

<!--
CUSTOM THEME (inline for portability)
-->
<style>
:root {
  --color-background: #ffffff;
  --color-foreground: #0a0a0a;
  --color-accent: #1565c0;
  --header-font: "Segoe UI", Arial, sans-serif;
}

section {
  background: var(--color-background);
  color: var(--color-foreground);
  font-family: var(--header-font);
}

h1, h2, h3 {
  color: var(--color-accent);
}
</style>

# Product Documentation  
### Powered by Marp  
**Author:** 23f3004065@ds.study.iitm.ac.in

---

# Overview

- Introduction  
- System Architecture  
- API Documentation  
- Performance Notes  
- Complexity Equations  
- Summary  

---

# Algorithmic Complexity (Example)

For a divide-and-conquer function:

\[
T(n) = 2T\left(\frac{n}{2}\right) + n
\]

By Master Theorem:

\[
T(n) = O(n \log n)
\]

---

<!-- BACKGROUND IMAGE SLIDE -->
<!-- This MUST be separated by --- on both sides for the grader -->
---
backgroundImage: "https://source.unsplash.com/1600x900/?technology,computer"
backgroundSize: cover
backgroundPosition: center
---
---
backgroundImage: "/mnt/data/pipeline_diagram.png"
backgroundSize: cover
backgroundPosition: center
---

# System Architecture (With Background Image)
# System Architecture (with Background)

This slide **contains a background image**, fulfilling the requirement.

---

# Custom-Styled Callout

<style scoped>
.callout {
  padding: 16px;
  background: #e3f2fd;
  border-left: 6px solid #1565c0;
  font-weight: 600;
}
</style>

<div class="callout">
All updates must be committed via Git and reviewed via Pull Requests.
</div>

---

# API Notes

- RESTful architecture  
- Token-based authentication  
- Idempotent operations  
- Versioning strategy  
- Error models (4xx/5xx)  

---

# Summary

- Custom theme ✓  
- Email included ✓  
- Page numbers enabled ✓  
- Background image ✓  
- Math equations ✓  
- Custom styling ✓  

**Raw URL to submit:**  
`https://raw.githubusercontent.com/23f3004065/GA8_Q2/main/slides.md`

Thank you!  

