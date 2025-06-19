# CS-5463 • Advanced Computer Architecture (AdvCA)
### Homework, Practice Exams & Trace-Analysis Notebook

> **University of Oklahoma – Spring 2025**  
> Maintainer: **Naveen Jajapur**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.9 – 3.11](https://img.shields.io/badge/python-3.9%20|%203.10%20|%203.11-blue.svg)](#)

---

## 📂 Repository contents

| File / group | Purpose |
|--------------|---------|
| **ACA-HomeWork-1.docx / .pdf** | Homework 1 prompt & submission |
| **HW2-1.pdf** | Homework 2 |
| **HW4-1.pdf**, **HW4 Solutions.pdf** | Homework 4 prompt + worked solutions |
| **Cache Coherence.pdf** | Lecture summary on MESI protocol |
| **cache_coherence_sequence_*.txt** | 10 000-access memory traces used in cache-coherence analysis |
| **trace**, **trace2** | Generic instruction-level traces for the simulation project |
| **Simulation project.pdf** | Specification for the cycle-accurate simulator you will implement |
| **ADVCA.ipynb** | Jupyter notebook that parses trace files, computes hit/miss & branch-predictor stats, and plots results |
| **Adv CA Mid Term Practice.docx / Midterm 1 Practice*.pdf** | Mid-term practice questions & answer key |
| **Final Exam Practice Solutions.pdf** | Comprehensive final-exam review problems with fully worked solutions |

Both the original **Word (.docx)** sources *and* exported **PDFs** are retained so future students can edit or read the material easily.

---

## 🚀 Quick-start – run the notebook

```bash
# 1) (optional) create an isolated env
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

# 2) install minimal dependencies
pip install numpy pandas matplotlib jupyter

# 3) launch
jupyter notebook ADVCA.ipynb
