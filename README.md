Geotechnical & Materials Engineering Lab Suite

A comprehensive collection of lightweight, high-performance web applications
designed for civil engineering laboratory testing and Quality Control (QC/QA)
reporting.


📋 Project Overview

This suite provides browser-based tools for critical geotechnical and
construction material tests. These applications eliminate the need for manual
spreadsheets by providing instant calculations, statistical analysis, automated
graphing, and professional reporting directly from the field or laboratory.

Included Applications:

1.  Field Density Report (Sand Cone Method): Automated calculation of relative
    density and field dry density.
2.  Compressive Strength Report: Statistical analysis of concrete/mortar samples
    with automated outlier detection.
3.  Soil Classification Tool: Group classification and Group Index (GI)
    calculation based on AASHTO/ASTM standards.
4.  Proctor Compaction Report: Relationship analysis between moisture and
    density with automated curve plotting and oversize correction.
5.  Sieve Analysis (Grain Size): Cumulative retained method featuring log-linear
    interpolation for D_{10}, D_{30}, D_{60} values and C_u/C_c coefficients.

🚀 Core Features

  - Engineering Precision: Calculations strictly follow international standards
    (AASHTO T191, T99, T180, M145, T27 and ASTM D1556, C39, D3282, D4718, C136).
  - Adaptive Dark Mode: High-contrast dark theme for low-light lab environments,
    persistent via localStorage.
  - CSV Export Engine: One-click data extraction for seamless integration with
    Microsoft Excel or Google Sheets.
  - Mobile-First Design: Optimized for field use on tablets and smartphones with
    touch-friendly inputs and bold UI borders.
  - Automated Visualization: Dynamic plotting of Compaction and Gradation curves
    using Logarithmic scaling where required.
  - Client-Side Auto-Save: Automatically caches data in the browser so work is
    never lost due to page refreshes.

🛠️ Technical Stack

  - Frontend: HTML5, CSS3, JavaScript (ES6+).
  - Styling: Tailwind CSS 3.x (JIT Engine).
  - Data Visualization: Chart.js (for Compaction and Gradation Curves).
  - Persistence: Browser localStorage API.

🤖 Development & AI Collaboration

This project represents a modern approach to engineering software development, developed with the assistance of Google Gemini (Advanced
    Large Language Models).
      - The AI was utilized to optimize the Tailwind CSS architecture, implement
        the persistent dark mode system, build the CSV export engine, and assist
        in complex mathematical interpolations (Log-Linear) for sieve analysis.

⚖️ Engineering Standards Compliance

| Test                     | Standard Reference               |
| :----------------------- | :------------------------------- |
| **Sand Cone**            | AASHTO T 191 / ASTM D1556        |
| **Compressive Strength** | ASTM C39 / EN 12390              |
| **Soil Classification**  | AASHTO M 145 / ASTM D3282        |
| **Proctor Compaction**   | AASHTO T 99 / T 180 / ASTM D4718 |
| **Sieve Analysis**       | ASTM C136 / AASHTO T 27          |

📖 How to Use

1.  Direct Access: Open any .html file in a modern web browser.
2.  Input Data: Enter laboratory measurements into the bolded input fields.
3.  Real-time Analysis: Results calculate and graphs update automatically as you
    type.
4.  Export/Save:
      - Click "CSV" to save a spreadsheet of the raw and calculated data.
      - Click "PDF" (or Ctrl+P) to generate a clean, professionally formatted
        print report.
      - Toggle the Moon/Sun icon to switch between light and dark modes.

👤 Author

Mohamed A. Elnaggar

  - QC/QA Engineer, Civil Engineering Testing and Consulting Unit - Egypt-Japan University of Science and Technology (E-JUST)

📜 License

This project is licensed under the MIT License - see the LICENSE file for
details.

© 2026 Mohamed Abdelazim • Engineering Quality Control Systems
