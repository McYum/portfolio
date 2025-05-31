# Portfolio Development & Accessibility Compliance Process

This document outlines the tools and methodologies used in the development and accessibility compliance checking for the portfolio website hosted at: `https://mcyum.github.io/portfolio/index.html#about`.

## Accessibility Compliance Testing (AA/WCAG)

Ensuring the portfolio is accessible to a wide range of users, including those with disabilities, was a key objective. The following tools were employed to check for AA/WCAG (Web Content Accessibility Guidelines) compliancy:

1.  **accessiBe AccessScan:**
    *   An automated scan was performed using accessiBe's AccessScan tool to get an initial overview of potential accessibility issues.
    *   **Scan Link:** [accessiBe Scan for mcyum.github.io/portfolio](https://accessibe.com/accessscan?website=https://mcyum.github.io/portfolio/index.html#about)

2.  **Friendly Captcha Accessibility Check:**
    *   This tool provided another automated audit of the website's accessibility status.
    *   **Audit Link:** [Friendly Captcha Audit for mcyum.github.io/portfolio](https://accessibilitycheck.friendlycaptcha.com/audit?t=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL21jeXVtLmdpdGh1Yi5pby9wb3J0Zm9saW8vIiwiaWF0IjoxNzQ4NzEyMDMzLCJleHAiOjE3NDg3OTg0MzN9.PK7VeGcFzqjxhiHzE-2MkAt8mZsTfir1lKttsEuMqZU)

3.  **WAVE Evaluation Tool:**
    *   The WAVE Web Accessibility Evaluation Tool (typically used as a browser extension or via their website) was also utilized for in-depth analysis and identification of accessibility concerns.
    *   **Note on Contrast Errors:** It was observed during testing that the WAVE tool sometimes reported contrast errors in situations where, upon manual inspection and verification with other tools (like browser developer tools' color pickers), the contrast ratios appeared to meet AA/WCAG requirements. While WAVE is an invaluable tool, these occasional discrepancies were noted and cross-verified.

4.  **NVDA Screen Reader:**
    *   Additionally, the website was manually tested using the NVDA (NonVisual Desktop Access) screen reader. This was done to evaluate the user experience for individuals who rely on assistive technologies and to ensure that navigation, content structure, and semantic markup are correctly interpreted.

## Development Workflow & Tools

The development process incorporated modern tools for efficiency and collaboration:

1.  **Version Control & Hosting:**
    *   **GitHub:** All source code for the portfolio was managed using Git for version control, with GitHub serving as the remote repository.
    *   **GitHub Pages:** The website was hosted using GitHub Pages, which also facilitated easy access for the aforementioned accessibility scans on the live version.

2.  **AI-Powered Assistance:**
    *   **GitHub Copilot:** Used for real-time code suggestions, autocompletion, and boilerplate code generation, speeding up the development process.
    *   **Gemini 2.5 (or your specific Gemini version):** Leveraged for code refactoring, problem-solving, generating explanations, and general assistance with more complex coding tasks.

3.  **Responsive Design & Browser Compatibility:**
    *   **Responsive Design:** The website was designed to be responsive, ensuring optimal display and interaction across various device sizes (desktops, tablets, mobile devices). This also supports accessibility for users who utilize zoom features or have different viewport sizes.
    *   **Browser Testing:** Compatibility was ensured by testing with the current stable versions of major browsers: Google Chrome, Mozilla Firefox, and Microsoft Edge, to guarantee consistent rendering and functionality.

## Design Inspiration

The initial layout and structural design of this current portfolio were vaguely based on a previous iteration of my personal portfolio, serving as a familiar starting point for the new design.

---

This combination of automated and manual checks, along with robust development tools, aimed to create an accessible and well-structured portfolio.