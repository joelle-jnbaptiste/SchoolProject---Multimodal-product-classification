<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Stars][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">🪄 Multimodal Product Classification</h3>

<p align="center">
  Automatic classification of consumer goods using both textual descriptions and product images, combining text preprocessing, image feature extraction, dimensionality reduction, and supervised machine learning.
  <br />
  <br />
  <a href="https://www.kaggle.com/datasets/atharvjairath/flipkart-ecommerce-dataset"><strong>View Dataset (Flipkart) »</strong></a>
  <br />
  <br />
  <a href="https://world.openfoodfacts.org/"><strong>View Dataset (Open Food Facts) »</strong></a>
  <br />
  <br />
  <a href="https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification">Solution Repository</a>
</p>
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>📜 Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">🔮 About The Project</a>
      <ul>
        <li><a href="#datasets">🧺 Datasets</a></li>
        <li><a href="#built-with">✨ Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">🪄 Getting Started</a>
      <ul>
        <li><a href="#prerequisites">📘 Prerequisites</a></li>
        <li><a href="#installation">🧙 Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">📖 Usage</a></li>
    <li><a href="#roadmap">🗺️ Roadmap</a></li>
    <li><a href="#license">📄 License</a></li>
    <li><a href="#contact">📬 Contact</a></li>
  </ol>
</details>

---

## 🔮 About The Project

This repository contains a **multimodal product classification** pipeline built from **textual product information** and **product images**.

The goal is to demonstrate how combining modalities can improve product categorization compared to unimodal approaches.

Key topics covered:
- Text preprocessing and feature extraction
- Image feature extraction
- Dimensionality reduction for analysis and visualization
- Supervised machine learning models
- Comparative evaluation between modalities (text vs image vs combined)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🧺 Datasets

This project uses two open data sources:

- **Flipkart Ecommerce Dataset (Kaggle)**  
  Includes product metadata such as titles/descriptions and categories.  
  https://www.kaggle.com/datasets/atharvjairath/flipkart-ecommerce-dataset

- **Open Food Facts (Public Database + API)**  
  Used to retrieve real food products with text fields and product images.  
  https://world.openfoodfacts.org/

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![ScikitLearn][Sklearn-shield]][Sklearn-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🪄 Getting Started

This project is built with **Python notebooks**.  
To reproduce results locally, follow these steps.

### 📘 Prerequisites

- Python 3.9+
- pip (or conda)
- Jupyter Notebook / JupyterLab

### 🧙 Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification.git

2. Install dependencies:

       pip install -r requirements.txt

> If you don’t have a `requirements.txt` yet, you can install the main packages:
>
>       pip install pandas numpy scikit-learn matplotlib seaborn requests jupyter

3. Launch Jupyter:

       jupyter notebook

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📖 Usage

Open the notebooks in this order:

1. **Preprocessing notebook**  
   - Loads datasets  
   - Cleans text fields  
   - Prepares image URLs / downloads assets if needed  

2. **Classification notebook**  
   - Extracts features (text + image)  
   - Applies dimensionality reduction  
   - Trains supervised models and evaluates performance  

3. **Data collection script notebook (Open Food Facts)**  
   - Calls the Open Food Facts API  
   - Builds a dataset (example: champagne products)  
   - Exports a CSV file used for downstream experiments  

Files included in the repository:
- `champagne_products.csv`: sample dataset built from Open Food Facts
- Notebooks: end-to-end pipeline from data collection to modeling

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🗺️ Roadmap

- [ ] Add a reproducible `requirements.txt`
- [ ] Improve dataset balancing and category mapping
- [ ] Add a unified multimodal training pipeline (single entrypoint)
- [ ] Add model comparison report (text vs image vs multimodal)
- [ ] Add evaluation on unseen categories/products
- [ ] Package inference as a simple API (FastAPI) or a demo app (Streamlit)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📄 License

This project is provided for educational purposes.

Data licensing is governed by the original sources:
- Kaggle dataset terms for Flipkart
- Open Food Facts database terms for Open Food Facts

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📬 Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link:  
https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- MARKDOWN LINKS & IMAGES -->
[stars-shield]: https://img.shields.io/github/stars/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification.svg?style=for-the-badge
[stars-url]: https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification/stargazers
[issues-shield]: https://img.shields.io/github/issues/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification.svg?style=for-the-badge
[issues-url]: https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification/issues
[license-shield]: https://img.shields.io/badge/License-Educational-purple?style=for-the-badge
[license-url]: #
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-4B0082?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://fr.linkedin.com/in/joëllejnbaptiste

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[Sklearn-shield]: https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white
[Sklearn-url]: https://scikit-learn.org/
