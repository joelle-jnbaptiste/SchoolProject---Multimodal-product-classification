<p align="center">
  <img src="https://img.shields.io/github/license/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification?style=for-the-badge" />
  <img src="https://img.shields.io/badge/School%20Project-ML%20%26%20Data-blueviolet?style=for-the-badge" />
</p>

<h1 align="center">✨ Multimodal Product Classification ✨</h1>

<div align="center">
  <em>
     *When text and images work together to understand products*
  </em>
</br>

 <b>Automatic classification of consumer products using both textual descriptions and product images, combining multimodal feature extraction and supervised learning</b>
</br>
</br>
🗃️ **Datasets**  
 https://www.kaggle.com/datasets/abhishek14398/flipkart-ecommerce-dataset  
 https://world.openfoodfacts.org/
  
</div>

---


<!-- TABLE OF CONTENTS -->
<details>
  <summary>🧭 Table of Contents</summary>
  <ol>
    <li><a href="#-built-with">Built With</a></li>
    <li><a href="#-about-the-project">About The Project</a></li>
    <li><a href="#-dataset">Dataset</a></li>
    <li><a href="#-analysis-workflow">Analysis Workflow</a></li>
    <li><a href="#-repository-structure">Repository Structure</a></li>
    <li><a href="#-getting-started">Getting Started</a></li>
    <li><a href="#-license">License</a></li>
    <li><a href="#-contact">Contact</a></li>
  </ol>
</details>

---
### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![NumPy][NumPy-shield]][NumPy-url]
[![ScikitLearn][ScikitLearn-shield]][ScikitLearn-url]
[![Matplotlib][Matplotlib-shield]][Matplotlib-url]
[![Seaborn][Seaborn-shield]][Seaborn-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 About The Project

This project implements a **multimodal product classification pipeline**, combining **textual product information** and **product images** to automatically categorize consumer goods.

The main objective is to demonstrate how **combining multiple data modalities** improves classification performance compared to unimodal approaches.

Key aspects of the project include:

- Text preprocessing and feature extraction
- Image feature extraction
- Dimensionality reduction and visualization
- Supervised machine learning models
- Comparative evaluation between modalities (text vs image vs combined)

The entire workflow is implemented in **Jupyter Notebooks**, with a strong focus on **methodology**, **interpretability**, and **experimental comparison**.

---

## 🗃️  Dataset

This project relies on two complementary open data sources:

### Flipkart E-commerce Dataset (Kaggle)
- Product titles and descriptions
- Product categories

https://www.kaggle.com/datasets/abhishek14398/flipkart-ecommerce-dataset

### Open Food Facts (API)
- Food product textual fields
- Product images
- Category metadata

https://world.openfoodfacts.org/

A dedicated notebook is used to **collect data via the Open Food Facts API** and build a reusable dataset for experimentation.

---

## 🧠 Analysis Workflow

The notebooks follow a structured multimodal workflow:

1. **Data Collection**
   - API calls to Open Food Facts
   - Dataset construction and export

2. **Text Processing**
   - Cleaning and normalization
   - Feature extraction (TF-IDF / embeddings)

3. **Image Processing**
   - Image URL handling / downloads
   - Visual feature extraction

4. **Dimensionality Reduction**
   - Visualization of feature spaces
   - Comparative analysis between modalities

5. **Supervised Classification**
   - Training classification models
   - Performance evaluation

6. **Multimodal Comparison**
   - Text-only vs image-only vs combined
   - Interpretation of results

---

## 🗺️ Repository Structure

    SchoolProject---Multimodal-product-classification/
    ├── notebooks/
    │   ├── JEANBAPTISTE_Joelle_1_notebook_pretraitement.ipynb
    │   ├── JEANBAPTISTE_Joelle_2_notebook_classification.ipynb
    │   └── JEANBAPTISTE_Joelle_3_script_Python_Collecte.ipynb
    │
    ├── champagne_products.csv     # Example dataset from Open Food Facts
    └── README.md

---

## ⚔️ Getting Started

This project is designed to be explored locally using **Jupyter Notebook**.

### Prerequisites

- Python 3.9+
- pip or conda
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification.git

2. Navigate to the project folder:

       cd SchoolProject---Multimodal-product-classification

3. Install dependencies:

       pip install -r requirements.txt

   If no requirements file is available:

       pip install pandas numpy scikit-learn matplotlib seaborn requests jupyter

4. Launch Jupyter Notebook:

       jupyter notebook

---

## ✒️ License

This project is provided for educational purposes.  
Data licenses remain governed by their original sources (Kaggle and Open Food Facts).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🕊️ Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link: https://github.com/joelle-jnbaptiste/SchoolProject---Multimodal-product-classification

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[NumPy-shield]: https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[ScikitLearn-shield]: https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white
[ScikitLearn-url]: https://scikit-learn.org/
[Matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge
[Matplotlib-url]: https://matplotlib.org/
[Seaborn-shield]: https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge
[Seaborn-url]: https://seaborn.pydata.org/
