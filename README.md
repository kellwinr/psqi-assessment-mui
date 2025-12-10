# PSQI Calculator

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

A standalone, single-file clinical tool for scoring the **Pittsburgh Sleep Quality Index (PSQI)**. 

Designed with **Material Design 3 (Material You)** principles, this tool provides a beautiful, responsive, and animated interface for calculating sleep quality scores without needing Excel or SPSS.

## ✨ Key Features

* **⚡️ Single File Architecture:** No servers, no installation, and no internet required. Just one `.html` file.
* **🎨 Material You UI:** Features modern rounded aesthetics, "Surface" color roles, and smooth entry animations.
* **🖨️ Clinical Print Mode:** Press `Ctrl + P` to generate a clean, black-and-white medical report (automatically hides buttons and styling artifacts).
* **🧠 Smart Validation:** Prevents impossible inputs (e.g., >24 hours of sleep).
* **🔢 Auto-Scoring:** Instantly calculates all 7 components and the Global Score based on the official Buysse et al. (1989) algorithms.

## 🚀 Quick Start

1.  Download or save the file `psqi_final.html`.
2.  **Double-click** the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  Enter the patient's data.
4.  Click **Calculate Score**.

## 🧩 Technical Details

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
