# Copernicus Monitoring Service Workshop Series

This repository contains code, scripts, and resources for hands-on sessions covering **Land**, **Marine**, and **Atmosphere** monitoring using data and services from Copernicus.

## Overview

This workshop series is designed to be beginner-friendly, with a focus on practical applications of Copernicus data. Each session includes morning presentations followed by afternoon coding and demo sessions. Participants will get hands-on experience using pre-prepared scripts and notebooks, which they can adapt for their own needs.

### Workshop Topics

1. **Land Monitoring Service**
   - Morning: Overview of Copernicus Land Monitoring Services and user cases 
   - Afternoon: Hands-on session using adjusted scripts from the EEA repository to explore land monitoring datasets and workflows.
   
2. **Marine Monitoring Service** (to be added)
   - Morning: Overview of Copernicus Marine Monitoring Services
   - Afternoon: Hands-on session exploring marine datasets.

3. **Atmosphere Monitoring Service** (to be added)
   - Morning: Overview of Copernicus Atmosphere Monitoring Services
   - Afternoon: Hands-on session exploring atmospheric datasets and tools for air quality assessment.

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

## Workshop: Land Monitoring Service

### Description

In this session, we will use pre-adjusted scripts derived from the **EEA Land Monitoring Repository**, with additional functionality that we’ve added to enhance the workflows. Participants will learn to about ARLINE data, snow and ice monitoring, and assess data using various Copernicus Land Monitoring datasets.

### Structure

- `land/`: Contains notebooks for the hands-on session for Copernicus Land monitroing service.
- `/clms-hrsi-arlie_demo-iceland/`: Contains examples and exercisse of how to download and process ARLIE data.
- `/land_use/`: Contains notebooks for download and processing data from WEkEO such is Urban Atlas and Corine lulc in the near future.

## Workshop: Atmosphere Monitoring Service

### Description

In this session, we will use pre-adjusted scripts derived from the **EEA Land Monitoring Repository**, with additional functionality that we’ve added to enhance the workflows. Participants will learn to about ARLINE data, snow and ice monitoring, and assess data using various Copernicus Land Monitoring datasets.

### Structure

- `..`: Contains notebook for the hands-on session for Copernicus Land monitroing service.
- `marine/`: Contains notebook for the hands-on session for Copernicus Marine monitroing service.
- `Land_use/`: Contains notebook for the hands-on session for Copernicus Atmosphere monitroing service.

### How to Run the Notebook

---

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for more details on how to help improve this repository.

---

## License

This repository is licensed under the [MIT License](LICENSE).

