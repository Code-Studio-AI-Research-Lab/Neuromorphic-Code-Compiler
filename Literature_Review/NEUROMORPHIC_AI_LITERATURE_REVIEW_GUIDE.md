# 🧠 Onboarding Guide: Literature Review & Research Matrix for Neuromorphic Code Compilers

Welcome to the **Code Studio AI Research Lab**. This guide establishes the mandatory workflow, literature logging standards, and Git guidelines for all team members working on our project: **"Neuromorphic Code Compiler"**.

---

## 🔍 1. Where to Find High-Impact Papers
This is a highly elite, multidisciplinary frontier crossing Neural Engineering, Linguistics, and Theoretical Computer Science. Do not look for standard web development documentation; find papers exclusively via:
* **Google Scholar:** [scholar.google.com](https://scholar.google.com/) (Filter: *Since 2024/2025* for the latest deep neural tokenizers and non-invasive BCI architectures).
* **Premier Journals:** *Journal of Neural Engineering*, *IEEE Transactions on Neural Systems and Rehabilitation Engineering*, and *Nature Electronics*.
* **Top AI & Systems Conferences:** **NeurIPS**, **ICLR**, **ASPLOS** (Architectural Support for Programming Languages and Operating Systems), and **CHI**.

---

## 🛠️ 2. Search Strategy & Keywords
Use advanced, precise **Boolean Operators** (`AND`, `OR`, `""`) to filter for compiling logic:
* **Core Signal-to-Code Query:** `"Brain-computer interface" AND "Source code generation" AND "EEG"`
* **Tokenization Query:** `"Neural tokenization" AND "Transformers" AND "Electroencephalogram"`
* **Neuromorphic Compiler Query:** `"Neuromorphic computing" AND "Compiler architecture" AND "Abstract Syntax Tree"`

---

## 📖 3. How to Read & Critically Evaluate a BCI Paper
1.  **The Electrode Configuration:** Check whether the research used *invasive* electrodes (implants inside the brain) or *non-invasive* electrodes (an external cap on the head). *Our focus is strictly non-invasive (EEG).*
2.  **The Generation Paradigm:** Did the paper do true generative translation (compiling sequences dynamically), or did it just map specific brainwaves to simple pre-written macros (like clicking a button)?
3.  **The Performance Gap (Our Opportunity):** Look at their **Limitations**. Most BCI models suffer from massive inference latency, making live programming impossible. *Our core gap is optimizing a lightweight parser that runs instantly matching real-time human cognitive output.*

---

## 📂 4. GitHub Directory Structure & Collaborative Git Rules
To avoid chaotic repository states and maintain perfect pipeline safety, adhere strictly to these steps:

### Folder Architecture:
```text
Neuromorphic-Code-Compiler/
└── Literature_Review/
    ├── PDFs/                 # Store downloaded paper PDFs here
    │   └── Format: FirstAuthor_Year.pdf (e.g., Wolpaw_2024.pdf)
    ├── BibTeX/               # Raw BibTeX snippets for LaTeX compilation
    │   └── citations.bib     # Open and append your BibTeX blocks here
    └── Research_Matrix.md    # The central markdown table file
