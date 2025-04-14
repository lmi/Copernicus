# Copernicus Monitoring Service Workshop Series

This repository contains code, scripts, and resources for hands-on sessions covering **Land**, **Marine**, and **Atmosphere** monitoring using data and services from Copernicus.


## Overview

This workshop series is designed to be beginner-friendly, with a focus on practical applications of Copernicus data. Each session includes morning presentations followed by afternoon coding and demo sessions. Participants will get hands-on experience using pre-prepared scripts and notebooks, which they can adapt for their own needs.

### Workshop Topics

1. **Land Monitoring Service**
   - Morning: Overview of Copernicus Land Monitoring Services and user cases 
   - Afternoon: Hands-on session using adjusted scripts from the EEA repository to explore land monitoring datasets and workflows.
   
2. **Marine Monitoring Service** 
   - Morning: Overview of Copernicus Marine Monitoring Services
   - Afternoon: Hands-on session exploring marine datasets.

3. **Atmosphere Monitoring Service** 
   - Morning: Overview of Copernicus Atmosphere Monitoring Services
   - Afternoon: Hands-on session exploring atmospheric datasets and tools for air quality assessment.

---

## Workshop: Land Monitoring Service

### Description

In this session, we will use pre-adjusted scripts derived from the **EEA Land Monitoring Repository**, with additional functionality that we’ve added to enhance the workflows. Participants will learn to about ARLINE data, snow and ice monitoring, and assess data using various Copernicus Land Monitoring datasets.

### Structure

- `Land/`: Contains notebooks for the hands-on session for Copernicus Land monitroing service.
- `/clms-hrsi-arlie_demo-iceland/`: Contains examples and exercisse of how to download and process ARLIE data.
- `/land_use/`: Contains notebooks for download and processing data from WEkEO such is Urban Atlas and Corine lulc in the near future.

## Workshop: Marine Monitoring Service

### Description

In this session, we will use pre-adjusted scripts derived from the **Mercator Ocean International - Copernicus Marine**, with additional functionality that we’ve added to enhance the workflows. Participants will learn to about biogeochemical data, marine heat wave, and assess data using various Copernicus Marine Monitoring datasets.

### Structure

- `Marine/`: Contains the folders for the hands-on session for Copernicus Marine monitroing service.
- `/Biogeochemical/`: Contains the biogeochemical notebooks for the hands-on session for Copernicus Marine monitroing service.
   - `/out/`: Contains the output from the notebook results.
- `/Marine_Heat_Wave/`: Contains the marine heat wave notebooks for the hands-on session for Copernicus Marine monitroing service.
   - `/out/`: Contains the output from the notebook results.
   - `/img/`: Contains images to fully display the notebook.

## Workshop: Atmosphere Monitoring Service

### Description

In this session, we will use pre-adjusted scripts derived from the ****, with additional functionality that we’ve added to enhance the workflows. Participants will learn to about ....

### Structure

- `Atmosphere/`: Contains notebook for the hands-on session for Copernicus Atmosphere monitroing service.
   - `/img/`: Contains images to fully display the notebook.



---

## Getting Started

### Prerequisites

- Basic Python knowledge is useful but not required.
- A modern web browser and internet connection for accessing Copernicus services.
- Participants should have [Jupyter Notebook](https://jupyter.org/install) installed or use online platform (e.g. WEkEO, Kaggle, Google Colab or Copernicus )

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/lmi/copernicus.git
    cd copernicus
    ```

2. Install required dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Navigate to the relevant hands-on session folder (e.g., `LAND`) to start exploring the scripts.

---
## License

This repository is licensed under the [CC BY 4.0 License](LICENSE).

