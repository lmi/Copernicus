# 🌊 Exploring Copernicus Marine Data in Google Colab

**An interactive notebook for retrieving and exploring Copernicus Marine datasets, created by Náttúrufræðistofnun.**

---

### Overview
This notebook connects to **Copernicus Marine Service** to retrieve and list all available datasets.
Using Python, it fetches dataset descriptions automatically and generates markdown documentation.

The script logs in using credentials stored in `login.json` and queries Copernicus Marine API for metadata.

### How to Use
1. Open this notebook in Google Colab or another cloud platform.
2. Ensure you have the correct `login.json` file with valid credentials.
3. Run the provided code cells to explore dataset descriptions and available services.

| Try the code via free cloud platforms: | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lmi/Copernicus/blob/master/Marine/Overview/ConnectMarine.ipynb)

---

### Useful Reading Material
- **Copernicus Marine Toolbox**: [Toolbox Installation](https://help.marine.copernicus.eu/en/articles/7970514-copernicus-marine-toolbox-installation)
- **Visualize Copernicus Marine Data in Python**: [Data Marine Visualization](https://help.marine.copernicus.eu/en/articles/4854800-how-to-open-and-visualize-copernicus-marine-data-using-python)

---

### Attribution
- **License**: This notebook is published under **CC BY 4.0**.
- **Citation**: "*Credits: Náttúrufræðistofnun*"
- **Author**: Marco Pizzolato
- **Data Sources**: [Copernicus Marine Service](https://marine.copernicus.eu/)
- **Created in**: Python with `requests`, `json`, and `pandas` for data extraction and formatting.

---

**This notebook provides an automated way to explore and document Copernicus Marine datasets, making ocean data more accessible.**