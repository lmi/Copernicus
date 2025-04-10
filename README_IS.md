# Vinnustofur um vöktunarþjónustu Copernicus

Þessi gagnageymsla inniheldur skriftur, kóða og heimildir úr verklegum vinnustofum þar sem fjallað var um vöktun á **Landi**, **Hafi**, and **Andrúmslofti**. Á vinnustofunum var notast var við gögn og þjónustur frá Copernicus.


## Yfirlit

Vinnustofurnar eru hannaðar með byrjendur í huga þar sem áhersla var lögð á að læra að nota Copernicusargögn á hagnýtan hátt. Hver vinnustofa skiptist upp í tvo hluta með fyrirlestrum fyrir hádegi og verklegum æfingu eftir hádegi. Þátttakendur fá að spreyta sig á fyrirfram undirbúnum skriftum og "vinnubókum", sem þeir geta svo aðlagað að eigin þörfum.

### Viðfangsefni vinnustofanna

1. **Vöktun lands**
   - Fyrir hádegi: Yfirlit yfir landvöktunarþjónustu Copernicusar og dæmi sýnd um notkun á henni. 
   - Eftir hádegi: Verklegur hluti þar sem notaðar verða aðlagaðar skriftur úr gagnageymslu EEA til þess að skoða betur gagnasett úr landvöktunarþjónustunni og kynnast betur vinnulaginu með þau
   
2. **Vöktun hafs** 
   - Fyrir hádegi: Overview of Copernicus Marine Monitoring Services
   - Eftir hádegi: Hands-on session exploring marine datasets.

3. **Vöktun andrúmslofts** 
   - Fyrir hádegi: Overview of Copernicus Atmosphere Monitoring Services
   - Eftir hádegi: Hands-on session exploring atmospheric datasets and tools for air quality assessment.

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

This repository is licensed under the [MIT License](LICENSE).

