# PSQI Calculator

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

A standalone, single-file clinical tool for scoring the **Pittsburgh Sleep Quality Index (PSQI)**.

Completely redesigned with a **Modern** user interface, this tool provides a visually responsive, and animated interface for calculating sleep quality scores without needing Excel or SPSS.

## ✨ Key Features

* **⚡️ Single File Architecture:** No servers, no installation, and no internet required. Just one `.html` file containing all HTML, CSS, and JS.
* **💎 Glassmorphism UI:** Features frosted glass effects, dynamic background animations, and sleek transparency for a premium feel.
* **🎨 Dynamic Visuals:** Includes animated floating background orbs and smooth, staggered entry animations for results.
* **🖨️ Clinical Print Mode:** Press `Ctrl + P` to generate a clean, ink-saving black-and-white medical report (automatically strips glass effects and background colors).
* **🧠 Smart Validation:** Prevents impossible inputs (e.g., >24 hours of sleep) and validates time fields.
* **🔢 Auto-Scoring:** Instantly calculates all 7 components and the Global Score based on the official Buysse et al. (1989) algorithms.

## 🚀 Quick Start

1.  Download or save the file `index.html` or https://kellwinr.github.io/psqi-assessment-mui/.
2.  **Double-click** the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  Enter the patient's data.
4.  Click **Calculate Score**.

## 🧩 Technical Details

### The "Glass" Effect
The interface uses modern CSS properties like `backdrop-filter: blur()` and semi-transparent RGBA backgrounds to create the frosted glass look, while ensuring text remains readable through high contrast ratios.

### The "Decimal Time" Logic
The calculator handles the complex logic of converting "Clock Time" to "Decimal Time" automatically to calculate sleep efficiency accurately.

* *Input:* `11:30 PM`
* *Backend Math:* Converts to `23.5`
* *Efficiency Calc:* `(Sleep Duration / Time in Bed) * 100`

### Browser Support
* **Chrome / Edge:** ✅ Perfect support (Input type="time" works best here).
* **Firefox / Safari:** ✅ Fully supported.
* **Mobile:** ✅ Responsive design adapts to phones and tablets.

## 📊 Scoring Reference

The tool outputs the following:

| Component | Description |
| :--- | :--- |
| **Global Score** | **< 5** = Good Quality, **≥ 5** = Poor Quality |
| Component 1 | Subjective Sleep Quality |
| Component 2 | Sleep Latency |
| Component 3 | Sleep Duration |
| Component 4 | Habitual Sleep Efficiency |
| Component 5 | Sleep Disturbances |
| Component 6 | Use of Sleeping Medication |
| Component 7 | Daytime Dysfunction |

## ⚖️ License

**MIT License** - You are free to modify, distribute, and use this tool for academic, clinical, or personal use.

> **Disclaimer:** This tool is for educational and research purposes. It is not a substitute for professional medical advice or diagnosis.
