# Pro-Rubric Evaluator & Cohort Analytics 📊
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A lightweight, single-page web application (SPA) designed to standardize academic evaluations, streamline live grading during presentations/mock defenses, and provide instant cohort analytics.

## 🚀 Live Demo
[https://suryamarthen-prog.github.io/simple-rubric-grader-app](https://suryamarthen-prog.github.io/simple-rubric-grader-app/)

## 💡 Why This Tool?
Traditional LMS grading systems are often too bulky for live, fast-paced evaluations. This tool is built specifically for **evaluators, lecturers, and technical reviewers** who need a distraction-free, highly consistent grading interface that operates entirely offline in the browser. 

It eliminates grading fatigue and provides instant visual feedback on student performance gaps.

## ✨ Key Features
* **100% Client-Side & Offline:** Built with Vanilla HTML/CSS/JS. No backend, no server, no installation required. Student data privacy is guaranteed as it only uses local browser memory.
* **Live Grading Interface:** Dynamic slider-based scoring with visual color-coded rank indicators.
* **EXCEL Template Engine:** Export and import grading rubrics as `.xlsx` files to instantly switch between different courses or evaluation matrices.
* **Auto-Save Draft:** Accidentally closed the tab? Your current grading progress and feedback text are automatically saved to `sessionStorage`.
* **Cohort Analytics:** Save multiple student evaluations to build a localized database (`localStorage`). View class averages, total students evaluated, and identify systemic bottlenecks.
* **Radar Chart Gap Analysis:** Generate instant SVG spider charts comparing individual student performance against the cohort average. Perfect for 1-on-1 feedback sessions.
* **One-Click Export:** Copy evaluation summaries to the clipboard for instant messaging, or export the entire cohort database to a `.xlsx` file for further system analysis.

## 🛠️ How to Use
1. Clone this repository or download the `index.html` file.
2. Open `index.html` in any modern web browser (Chrome, Edge, Safari, iPad).
3. Click **✏️ Edit template** to set up your grading dimensions, weights, and criteria.
4. Save your template via **📥 Download Template** for future use.
5. Start grading! Use the **💾 Save to Database** button to build your class analytics.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to fork, modify, and use it for your own academic or professional evaluations!
