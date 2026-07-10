# Performance Property Analytics Hub v2026 - property analytics tool 2026

> **Performance Property Analytics Hub is a browser-based property analytics workspace for research, dashboards, and controlled-access tooling, built around Supabase, GitHub Pages, and a 2026 release cycle.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leox70/performance-analytics-property-tools-2026?style=flat-square)](https://github.com/leox70/performance-analytics-property-tools-2026)

---

<p align="center">
  <a href="https://leox70.github.io/performance-analytics-property-tools-2026/">
    <img src="https://img.shields.io/badge/Download-Performance%20Property%20Analytics%20Hub%20Latest-brightgreen?style=for-the-badge" alt="Download Performance Property Analytics Hub">
  </a>
</p>

> **[Direct Download - Performance Property Analytics Hub v2026](https://leox70.github.io/performance-analytics-property-tools-2026/)**

---

[Download Latest Build](https://leox70.github.io/performance-analytics-property-tools-2026/)

---

## Overview

Performance Property Analytics Hub combines a set of web-based tools for property analysis, presentation, and gated access into one static-site workflow. The project includes a landing experience, a login page, and dashboard-oriented views that are meant to give fast access to research screens and operational utilities.

It is intended for use in the browser and supports workflows built around live data, layered access, and lightweight session handling. The setup is suited to teams or operators who want a straightforward front end that connects to backend services such as Supabase while remaining easy to deploy through GitHub Pages and compatible with Netlify redirect handling.

---

## Key Capabilities

- Login screen and hub landing page that create a clear starting point
- Multi-file static site layout for easier page-by-page management
- Property clock tool for time-sensitive property workflows
- Runway vs demand tool for comparing two planning perspectives
- Demand score dashboard with live data display
- Tier-based access control for different user roles
- sessionStorage auth gating for browser session management
- Netlify SPA redirect support for cleaner single-page routing

---

## Installation

Clone or download the repository, then open the static site structure in your preferred web server or deployment target.

1. Clone the repository:
   git clone https://github.com/leox70/performance-analytics-property-tools-2026.git
2. Move into the project folder:
   cd performance-property-tools
3. Serve the files locally or publish them to your web host.

For a local preview, open the main HTML entry point in a browser, or use a simple static server if your setup needs routed navigation support.

---

## Usage

Once the hub loads, begin at the login screen and then move into the dashboard or tool pages according to your access level.

Typical workflow:
1. Authenticate through the front-end gate.
2. Open the landing hub or dashboard view.
3. Use the property clock tool for timing-related checks.
4. Compare runway and demand inputs in the analysis tool.
5. Review the demand score dashboard for live data summaries.
6. Switch between pages as needed within the static site.

If the site is deployed behind Netlify or a similar host, make sure routing and redirect rules are configured so page refreshes continue to resolve correctly.

---

## Configuration

Most behavior is controlled through front-end files and deployment settings rather than a large runtime config. Common areas to tune include:
- Auth-related gating logic stored in browser sessionStorage
- Supabase connection details in the site scripts
- Access tiers and dashboard visibility rules
- Netlify redirect rules for SPA-style navigation

Example configuration pattern:

{
  "auth": "sessionStorage",
  "backend": "Supabase",
  "hosting": "GitHub Pages",
  "redirects": "Netlify SPA"
}

---

## Requirements

- A modern web browser
- Static hosting support, such as GitHub Pages
- Optional Supabase backend access for live data and authentication flows
- Deployment support for SPA redirects if using routed views
- A browser environment that supports sessionStorage

---

## FAQ

**How do I get into the hub?**  
Open the deployed web link in a browser and sign in through the login screen if access control is enabled.

**Where does the data come from?**  
The project profile shows a Supabase-backed setup, with live data used in the dashboard experience.

**Is it possible to customize the tools?**  
Yes. Because the site is split across multiple static files, individual pages and tool logic can be adjusted as needed.

**Why do redirects matter?**  
If you host the app as a single-page-style web experience, redirect rules help page refreshes and direct routes resolve properly.

**What if authentication does not persist?**  
Check the sessionStorage-based gating logic and confirm the browser is allowing site storage for the session.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
