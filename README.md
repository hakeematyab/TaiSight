<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]  
[![Forks][forks-shield]][forks-url]  
[![Stargazers][stars-shield]][stars-url]  
[![Issues][issues-shield]][issues-url]  

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/hakeematyab/TaiSight">
    <img src="assets/TaiSight.png" alt="TaiSight Logo" width="200" height="200">
  </a>

  <h3 align="center">🏔️ TaiSight: Never Miss a Page</h3>

  <p align="center">
    “Before TaiSight, it was like ‘I had eyes but couldn’t see Mt. Tai.’ Now we never miss a page.”  
    <br />
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#key-benefits">Key Benefits</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>
 -->

<!-- ABOUT THE PROJECT -->
## 📌 About The Project

**TaiSight** is an image‑first document intelligence solution that **embeds entire pages**—PDFs, slides, scanned forms, and handwritten notes—end‑to‑end and layers on multi‑stage retrieval and reasoning agents.

### 🚀 Core Features
- **📄 Full‑Page Embedding**  
  Raw image embeddings for print and handwriting—no OCR, no parsing.
- **🤖 Multi‑Stage Reasoning**  
  Coarse‑to‑fine retrieval, graph‑based agents, and confidence gating.
- **☁️ Cloud ↔ Edge Ready**  
  Containerized microservices on GCP/AWS & quantized Vision‑LMs for on‑device inference.
- **🔍 Transparent AI**  
  Attention heatmaps, retrieval trace logs, and explainable QA workflows.

### 🌟 Key Benefits
- **🎯 Never Miss a Detail**: Handwritten or printed, every page is fully “seen.”  
- **✅ Accurate Answers**: State‑of‑the‑art vision‑LMs + retrieval + generation.  
- **⚙️ Flexible Deployment**: Deploy on cloud servers or edge devices with the same pipeline.  
- **🔎 Explainable Workflows**: Visualize exactly what the model attended to and why.  

<!-- GETTING STARTED -->
## 🚀 Getting Started

### 📂 Folder Structure

**Main Repo**  
```
TaiSight/
│
├── .github/workflows/
├── requirements.txt
├── .gitignore
├── .dvcignore
├── TaiSight.yml
└── README.md
```

**Modules**  
Each module/pipeline follows this layout:
```
ModuleName/
├── inputs/
├── outputs/
├── logs/
├── script.py
├── test_script.py
├── dockerfile
├── requirements.txt
├── environment.yml
└── README.md
```

### ⚙️ Prerequisites

1. **Anaconda** 🐍: [Download and install Anaconda](https://www.anaconda.com/download)  
   ```bash
   conda --version
   ```
2. **Python 3.x** 🐍: [Download and install Python](https://www.python.org/downloads/)  
   ```bash
   python --version
   ```
3. **Git** 🔧: [Download and install Git](https://git-scm.com/downloads)  
   ```bash
   git --version
   ```

### ⚡ Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/hakeematyab/TaiSight.git
   cd TaiSight
   ```
2. **Create env & install dependencies**  
   ```bash
   conda env create -f TaiSight.yml
   conda activate TaiSight
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- 
---

## 🖥️ Usage

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🤝 Contributing

### Top contributors  
<a href="https://github.com/hakeematyab/TaiSight/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hakeematyab/TaiSight" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📜 License

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
-->
## 📞 Contact

Atyab Hakeem – hakeematyab.official@gmail.com  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/hakeematyab/TaiSight.svg?style=for-the-badge
[contributors-url]: https://github.com/hakeematyab/TaiSight/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hakeematyab/TaiSight.svg?style=for-the-badge
[forks-url]: https://github.com/hakeematyab/TaiSight/network/members
[stars-shield]: https://img.shields.io/github/stars/hakeematyab/TaiSight.svg?style=for-the-badge
[stars-url]: https://github.com/hakeematyab/TaiSight/stargazers
[issues-shield]: https://img.shields.io/github/issues/hakeematyab/TaiSight.svg?style=for-the-badge
[issues-url]: https://github.com/hakeematyab/TaiSight/issues
[license-shield]: https://img.shields.io/github/license/hakeematyab/TaiSight.svg?style=for-the-badge
[license-url]: https://github.com/hakeematyab/TaiSight/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/hakeematyab
