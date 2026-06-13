# Engineering Laboratory Information System (ELIS)
### Unified Geotechnical & Quality Control Suite
**Developed by:** Mohamed Abdelazim  
**Affiliation:** Lab Engineer, Egypt-Japan University for Science and Technology (E-JUST)

---

## 🔬 Overview
The **Engineering Lab Suite** is a professional-grade web portal designed for civil and geotechnical engineers to perform critical laboratory calculations with high precision. This suite adheres to international standards including **AASHTO** and **ASTM**, providing instant analysis, statistical cleansing, and visualization of laboratory data.

## 🛠 Included Applications

### 1. Sand Cone Density Analysis 🏜️
*   **Standards:** AASHTO T 191 / ASTM D1556.
*   **Features:** Field density calculations, volume of hole determination, and relative density reporting.

### 2. Compressive Strength Averager 🏗️
*   **Logic:** Features a **2-Cycle Statistical Outlier Cleanse**.
*   **Features:** Automatically filters samples deviating by more than ±20% from the mean across two consecutive verification passes to ensure ASTM compliance.

### 3. AASHTO Soil Classification 🌍
*   **Standards:** AASHTO M 145 / ASTM D3282.
*   **Features:** Instant determination of Soil Group, Group Index (GI), and Subgrade Rating based on Sieve and Atterberg inputs.

### 4. Proctor Compaction Test 📈
*   **Standards:** AASHTO T 99 / T 180.
*   **Features:** Dynamic **Compaction Curve plotting** using Chart.js. Includes **Oversize Correction (ASTM D4718)** for materials containing gravel.

### 5. Atterberg Limits & Free Swell 💧
*   **Standards:** AASHTO T 89, T 90 / ASTM D4318.
*   **Features:** 
    *   Linear regression on a semi-log scale for Liquid Limit (LL) at 25 blows.
    *   Live **Casagrande Plasticity Chart** plotting.
    *   Free Swelling Index (FSI) calculation.

### 6. Sieve Analysis (Gradation) 📐
*   **Logic:** Advanced Log-Linear Interpolation.
*   **Features:** 
    *   Replicates VBA-style interpolation for **D10, D30, and D60**.
    *   Automated Uniformity (Cu) and Curvature (Cc) calculation.
    *   Semi-logarithmic Grain Size Distribution curve.

---

## 🚀 Technical Highlights
*   **Client-Side Processing:** All calculations are performed instantly in the browser.
*   **Local Persistence:** Uses `localStorage` to cache your laboratory data so it remains available if you refresh the page.
*   **Print-to-PDF:** Every application is optimized with `@media print` CSS to generate clean, professional laboratory submittals.
*   **Responsive UI:** Built with **Tailwind CSS** for a professional look on tablets, laptops, and mobile devices.

## 📖 How to Deploy
1. Clone this repository or download the HTML files.
2. Ensure `index.html` remains in the root directory alongside the tool files.
3. Access the suite via **GitHub Pages** or any static web server.

---

## ⚖️ License & Copyright
© 2026 Mohamed A. Elnaggar  
This software is provided for engineering and educational purposes. Developed at the **Egypt-Japan University for Science and Technology (E-JUST)**.

> **Note:** For official engineering submittals, results should be verified by a licensed professional engineer.
