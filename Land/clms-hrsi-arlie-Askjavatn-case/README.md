
# Copernicus Land Monitoring Service (CLMS) - ARLIE Use Case

## Overview

This repository contains a demo notebook that has been slightly adjusted from the original notebook created by the [European Environment Agency (EEA)](https://github.com/eea). The use case demonstrates how to analyze data from the Aggregated River and Lake Ice Extent (ARLIE) product, which is part of the **High-Resolution Snow and Ice (HR-S&I)** monitoring suite offered by the Copernicus Land Monitoring Service (CLMS). This data allows for an in-depth analysis of ice conditions on rivers and lakes in Europe.

## About ARLIE

ARLIE, which stands for **Aggregated River and Lake Ice Extent**, provides a comprehensive spatial overview of ice conditions in European rivers and lakes. This dataset integrates data from the **Sentinel-2** and **Sentinel-1** satellite constellations, offering valuable insights into not just ice cover, but also water presence, clouds, vegetation, and bare soil.

The ARLIE data describes surface coverage for rivers and lakes based on 10 km river sections and lake boundaries defined by the **EU-Hydro database**. The geodatabase storing ARLIE data uses the **European ETRS89 LAEA** coordinate system (EPSG: 3035) and is updated daily.

For more detailed information about ARLIE, refer to the [Copernicus homepage](https://land.copernicus.eu/), the [Product User Manual](https://land.copernicus.eu/user-corner/technical-library/hrsi-pum), and the [Technical Note](https://land.copernicus.eu/user-corner/technical-library/hrsi-tn) for the HR-S&I products.

<div style="display: flex; align-items: center;">
    <img src="https://www.copernicus.eu/sites/default/files/styles/image_img_fluid/public/images/media/low/295955-Copernicus_logo_node_full_image_2.jpg?itok=rxBru8V4" alt="Copernicus Logo" style="width: 150px; height: 80px; margin-right: 20px;"/>
    <img src="https://www.eea.europa.eu/en/newsroom/branding-materials/eea_logo_compact_en.png/@@images/image/preview" alt="EEA Logo" style="width: 150px;"/>
</div>


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

### Running the Use Case on WEkEO

This use case is designed to be run on the **WEkEO** platform. Follow the steps below to set up and execute the Jupyter Notebook on WEkEO.

1. **Log in to WEkEO JupyterLab**:
   - Sign in to your WEkEO account and navigate to the **JupyterLab** environment.
   - Ensure you have the required access to the dataset and compute resources.

2. **Clone the Repository**:
   Inside your WEkEO JupyterLab terminal, clone the repository:
    ```bash
    git clone https://lmi/Copernicus/Land/clms-hrsi-arlie-use-case-demo.git
    cd yourfolder/clms-hrsi-arlie-use-case-demo/
    ```

3. **Open and Run the Notebook**:
   - Navigate to the `use_case_Oskjuvatn.ipynb` notebook.
   - Follow the steps in the notebook to execute the use case for analyzing ice cover changes using **ARLIE** data for **Lake Öskjuvatn**, Iceland

4. **Install Required Dependencies, uncomment cells in the notebook** (if necessary):
   - Open the Jupyter Notebook `use_case_Oskjuvatn.ipynb`.
   - Some cells may be commented out intentionally. Uncomment them to activate certain pieces of code for execution.
   
   Here's an example of what you may see in the notebook:

    ```python
    # Example commented code:
    # import rasterio
    # import matplotlib.pyplot as plt
    #
    # with rasterio.open('/path/to/sentinel-2-image.tif') as src:
    #     band1 = src.read(1)  # Read the first band (e.g., red band)
    #
    # plt.imshow(band1, cmap='gray')
    # plt.title('Sentinel-2 Band 1')
    # plt.show()
    ```

   **To uncomment**, remove the `#` symbols to enable the code:

    ```python
    import rasterio
    import matplotlib.pyplot as plt
    
    with rasterio.open('/path/to/sentinel-2-image.tif') as src:
        band1 = src.read(1)  # Read the first band (e.g., red band)
    
    plt.imshow(band1, cmap='gray')
    plt.title('Sentinel-2 Band 1')
    plt.show()
    ```

---

### Future Local Installation (To Be Added)
We will later provide instructions on how to run this demo locally or on other platforms like **local Jupyter** installations or alternative cloud environments. Stay tuned for updates!


***

## Legal Notice

Access to Copernicus data is provided under a principle of full, open, and free access as established by the **Copernicus Data and Information Policy** (Regulation (EU) No 1159/2013). More information can be found [here](http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159).

***

## License

This repository and its contents are licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

