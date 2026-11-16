# Giuliano Marra Laraia | Personal Portfolio

A minimalist, high-contrast static landing page built to present my profile, technical skills, and software development repositories. Hosted for free on **GitHub Pages**, this project operates without databases, external trackers, or client-side JavaScript.

**Live Site:** [(giulianoml.github.io/Portfolio/)](giulianoml.github.io/Portfolio/)
**Live Site:** []
## Overview

As an **Information Systems** student at the **University of Uberaba (Uniube)**, I designed this portfolio to serve as a fast, reliable central hub connecting my code repositories and professional profiles. Every project card acts as a direct gateway to its respective repository on GitHub.

## Visual Identity & Color Hierarchy

The interface follows a strict dark-mode palette engineered for readability and clear visual hierarchy:

* **Dominant Background (`#050507` & `#0e0e14`):** Deep matte black surfaces reduce eye strain and frame visual elements cleanly.
* **High-Contrast Typography (`#ffffff` & `#c4c4d4`):** Pure white headings and light neutral body text ensure immediate legibility.
* **Strategic Purple Accents (`#8b5cf6` & `#c084fc`):** Used intentionally to guide user attention toward primary call-to-action buttons, skill badges, interactive card borders, and the custom profile emblem.

## Security-First Static Architecture

Even as a pure presentation landing page, the codebase applies front-end hardening best practices:

* **Zero Backend & Zero Scripts:** Built 100% with semantic **HTML5** and modern **CSS3**, eliminating database vulnerabilities and third-party script dependencies.
* **Strict Content Security Policy (CSP):** Configured via `<meta>` tags with `script-src 'none'`, `form-action 'none'`, `frame-src 'none'`, and `connect-src 'none'` to block unauthorized code execution or data exfiltration.
* **Privacy & Browser Hardening:** Enforces `strict-origin-when-cross-origin` referrer rules, `X-Content-Type-Options: nosniff`, and a restrictive `Permissions-Policy` disabling camera, microphone, and geolocation APIs.
* **Safe Outbound Navigation:** All external links use `target="_blank"` paired with `rel="noopener noreferrer external"` to prevent reverse tabnabbing.

## Repository Structure

```text
GiulianoML.github.io/
├── assets/
│   └── perfil.jpg       # Custom minimalist profile illustration
├── index.html           # Semantic HTML5 markup and embedded CSS3 styles
└── README.md            # Project documentation
