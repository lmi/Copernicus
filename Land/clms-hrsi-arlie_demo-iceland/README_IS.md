
# Landvöktunarþjónusta Copernicusar (CLMS) - Dæmi um notkun á ARLIE gögnum

## Yfirlit

Í þessari gagnageymslu (e. repository) er að finna kynningar vinnubók (e. notebook) sem byggð er á vinnubók frá [European Environment Agency (EEA)](https://github.com/eea). Vinnubókinni hefur verið breytt lítillega frá upprunalegri útgáfu. Dæmin sem eru notuð sýna hvernig hægt er að greina gögn frá ARLIE eða Aggregated River and Lake Ice Extent gagnasettin. Gögnin eru hluti af vöktunargögnum sem búa til **sjó- og ís gögn í hárri upplausn (HR-S&I)** sem er hluti af landvöktunarþjónusta Copernicusar  (CLMS). ARLIE gögnin gefa möguleikann á því að gera nákvæma greiningu á ástandi íss í ám og vötnum í Evrópu.


<div style="display: flex; align-items: center;">
    <img src="https://www.copernicus.eu/sites/default/files/styles/image_img_fluid/public/images/media/low/295955-Copernicus_logo_node_full_image_2.jpg?itok=rxBru8V4" alt="Copernicus Logo" style="width: 150px; height: 80px; margin-right: 20px;"/>
    <img src="https://www.eea.europa.eu/en/newsroom/branding-materials/eea_logo_compact_en.png/@@images/image/preview" alt="EEA Logo" style="width: 200px; height: 80px"/>
</div>


## Um ARLIE

ARLIE stendur fyrir **Aggregated River and Lake Ice Extent** eða **Samantekið umfang íss á ám og stöðuvötunum** og veitir yfirgripsmikla yfirsýn yfir skilyrði íss í evrópskum ám og vötunum og hlutfall íssins í rýminu. Gagnasettið byggir á gögnum frá **Sentinel-2** and **Sentinel-1** gervihnöttum og gefur dýrmætar upplýsingar um ísþekju, vatnsyfirborð, skýjahulu, gróður og jarðveg án gróðurþekju.

ARLIE gögnin lýsa yfirborði áa og stöðuvatna og er miðað við 10 km langa árkafla eða mörk stöðuvatna sem skilgreind eru af **EU-Hydro database** eða **Vatnaskrá Evrópusambansins**. Landfræðilegi gagnagrunnurinn sem geymir ARLIE gögnin notast við **European ETRS89 LAEA** hnitakerfið (EPSG: 3035) og er uppfærður daglega.

Frekari upplýsingar um ARLIE er hægt að finna á [heimasíðu Copernicusar](https://land.copernicus.eu/), í [Notendahandbókinni](https://land.copernicus.eu/user-corner/technical-library/hrsi-pum) og í  [Tæknilýsingu](https://land.copernicus.eu/user-corner/technical-library/hrsi-tn) fyrir HR-S&I gögnin.



***

## Kynningar vinnubók: 
1. Hvar á að byrja (how-to-get-started.ipynb)
2. Óvænt bráðnun Öskuvatns (askja-use-case.ipynb)

Kynningar vinnubókin einblínir á greiningar á óvæntri bránun íss á **Öskjuvatni** á Íslandi þar sem notuð eru ARLIE gögn. Stöðuvatnið sem venjulega er frosið þar til í júní eða júlí byrjaði að bráðna mjög snemma í **febrúar 2023**. 

### Upprunanleg vinnubók:
Vinnubókin var klofin út frá gagnageymsli EEA og hægt er að sjá upprunanlegu vinnubókin hér: [EEA CLMS HR-SI ARLIE Use Case](https://github.com/eea/clms-hrsi-arlie-use-case).

### Breytingar:
Við höfum gert gert minniháttar breytingar á vinnubókinn til að aðlaga upprunanlegu vinnubókin að okkar þörfum. Þær breytingar sem gerðar voru eftirfarandi:
- Bætt tímaröð (e. time-series)
- AAUkin myndræn framsetning á árstíðabundnum mynstrum.

### Steps Covered in the Notebook:
1. **Ná í og skipuleggja ARLIE gögnin**: Hvernig á að nota ARLIE's REST API til þess að ná í gögn fyrir Öskjuvatn.
2. **Raunhæfniprófun gagna**: Hreinsa út ónákvæmar mælingar og truflanir.
3. **Greining á þróun ísþekjunnar**: Framkvæmdu greiningu á tímaröðinni til þess að sjá mynstur í þróun ísþekjunnar á árunum 2017-202. 
3. **Myndræn framsetning**: 


***

## Keyrsla vinnubókarinnar

Til þess að keyra vinnubókin getur þú annaðhvort notað Jupyter Notebooks á tölvunni þinni eða nýtt þér einn af fjölmörgum þjónustum á netinu eins og [WEkEO](https://www.wekeo.eu/), sem sérhæfir sig í að vinna með kóða og þjónustur frá Copernicus.

### Möguleikar

- **Jupyter Notebook** sett upp í tölvunni þinni eða notaðuinstalled locally or access to an online platform (e.g., WEkEO).
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
    git clone https://lmi/Copernicus/Land/clms-hrsi-arlie_demo-iceland.git
    cd yourfolder/clms-hrsi-arlie_demo-iceland/
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

