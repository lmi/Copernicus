
# Copernicus Land Monitoring Service (CLMS) - ARLIE Use Case

## Overview

This repository contains a demo notebook that has been slightly adjusted from the original notebook created by the [European Environment Agency (EEA)](https://github.com/eea). The use case demonstrates how to analyze data from the Aggregated River and Lake Ice Extent (ARLIE) product, which is part of the **High-Resolution Snow and Ice (HR-S&I)** monitoring suite offered by the Copernicus Land Monitoring Service (CLMS). This data allows for an in-depth analysis of ice conditions on rivers and lakes in Europe.

## About ARLIE

ARLIE, which stands for **Aggregated River and Lake Ice Extent**, provides a comprehensive spatial overview of ice conditions in European rivers and lakes. This dataset integrates data from the **Sentinel-2** and **Sentinel-1** satellite constellations, offering valuable insights into not just ice cover, but also water presence, clouds, vegetation, and bare soil.

The ARLIE data describes surface coverage for rivers and lakes based on 10 km river sections and lake boundaries defined by the **EU-Hydro database**. The geodatabase storing ARLIE data uses the **European ETRS89 LAEA** coordinate system (EPSG: 3035) and is updated daily.

For more detailed information about ARLIE, refer to the [Copernicus homepage](https://land.copernicus.eu/), the [Product User Manual](https://land.copernicus.eu/user-corner/technical-library/hrsi-pum), and the [Technical Note](https://land.copernicus.eu/user-corner/technical-library/hrsi-tn) for the HR-S&I products.

![Copernicus Logo](https://dataspace.copernicus.eu/themes/custom/copernicus/logo.svg)
![EEA Logo](https://www.eea.europa.eu/en/newsroom/branding-materials/eea_logo_compact_en.png/@@images/image/preview)

***

## Demo Notebook: Unexpected Melting of Lake Öskjuvatn

This demo notebook focuses on an analysis of an unexpected melting event at **Lake Öskjuvatn** in Iceland using ARLIE data. The lake, which typically stays frozen until June or July, experienced early melting in **February 2023**. 

### Original Notebook Source:
This notebook was forked from the EEA repository, and the original can be found here: [EEA CLMS HR-S&I ARLIE Use Case](https://github.com/eea/clms-hrsi-arlie-use-case).

### Adjustments:
We have made some slight adjustments to the original notebook to tailor it for this specific use case. This includes:
- Addition of Icelandic data for Lake Öskjuvatn.
- Enhanced time series analysis.
- Additional visualizations for seasonal trends.

### Steps Covered in the Notebook:
1. **Retrieve and Organize ARLIE Data**: How to use ARLIE's REST API to retrieve data for Lake Öskjuvatn.
2. **Sanity Check Data**: Filter out noisy observations and clean the dataset.
3. **Analyze Ice Cover Trends**: Perform a time-series analysis to identify patterns in ice coverage from 2017–2023.

***

## Running the Notebook

To run the notebook, you can either use Jupyter Notebooks locally or take advantage of online platforms like [WEkEO](https://www.wekeo.eu/), which is specifically designed to run Copernicus-related code and services.

### Prerequisites

- **Jupyter Notebook** installed locally or access to an online platform (e.g., WEkEO).
- Basic Python knowledge is useful but not required.
- An internet connection to access the ARLIE API.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/copernicus-workshops.git
    cd copernicus-workshops/CLMS
    ```

2. Install required dependencies (listed in `requirements.txt`):
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run `use_case_2_Oskjuvatn.ipynb` to begin the demo.

---

## Legal Notice

Access to Copernicus data is provided under a principle of full, open, and free access as established by the **Copernicus Data and Information Policy** (Regulation (EU) No 1159/2013). More information can be found [here](http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159).

---

## License

This repository and its contents are licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

