# 🗺️ Geospatial Data Processing and Visualization with Python

This repository contains materials for the graduate workshop taught by **Minsu Jang** at the **Behave Lab, University of Milan** (June 4, 2025). The workshop introduces students to geospatial data processing and visualization techniques in `Python`, combining structured data, text analysis, and interactive mapping.

---

## 📦 Repository Structure

| File | Description |
|------|-------------|
| `TopicModel_Visualizing.ipynb` | Jupyter Notebook for the full hands-on session. Covers geospatial data, topic modeling with BERT, and interactive map generation. |
| `LanguageDetection_Translation.ipynb` | Preprocessing pipeline: detects review language, translates non-English content using Google Translate API. |
| `css-python-geo.yml` | Conda environment file. Reproduces the working environment for the workshop. |

> **Note**: Pleasedownload all necessary data files from [Inside Airbnb](https://insideairbnb.com/get-the-data/) — including listings, reviews, and neighborhood GeoJSON files for Milan — and place them under a local `data/` directory. Also, make sure to include `preprocessed_comment_data.csv`,  which is generated after running `LanguageDetection_Translation.ipynb.`

---

## 🚀 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/minsujang25/doing_css_MJ.git
cd GeospatialData
```

### 2. Create the environment

```bash
conda env create -f css-python-geo.yml
conda activate css-python-geo
```

### 3. Launch Jupyter Notebook or Lab

```bash
jupyter notebook
# or
jupyter lab
```

> **Note**: This environment includes `rise` for slide presentations and `streamlit` for app-based extensions.

---

## 🧭 Workshop Topics

- Introduction to geospatial data
- Working with GeoJSON, Shapefiles, and polygons using GeoPandas
- Topic modeling using BERT and BERTopic
- Language detection & translation pipeline with Google Cloud
- Visualizing topic distribution using Folium and Plotly
- Building interactive maps with hover-based insights

---

## 📝 Requirements

- A stable Python 3.9 environment (see `css-python-geo.yml`)
- Google Cloud Translate credentials (for language translation notebook)
- A GeoJSON file for Milan neighborhoods (go to [Inside Airbnb](https://insideairbnb.com/get-the-data/))

---

