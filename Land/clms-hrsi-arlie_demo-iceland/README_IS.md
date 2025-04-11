
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

### Forsendur

- **Jupyter Notebook** settu upp í tölvunni þinni eða notaðu einn af fjölmörgum þjónustum á netinu (t.d., WEkEO).
- BGrunnþekking í Python er gagnleg en ekki.
- Nettenging til að fá aðgang að ARLIE API.

### Keyrsla kynningardæmisins í WEkEO

Kynningardæmið er hannað til þess að vera keyrt í **WEkEO** þjónustunni. Fylgdu skrefunum hér á eftir til þess að setja upp Jupyter vinnubókina á WEkEO.

1. **Skráðu þig inn á WEkEO JupyterLab**:
   - Skráðu þig inn á WEkEO aðganginn þinn og finndu **JupyterLab** umhverfið.
   - Gakktu úr skugga um að þú hafir viðeigandi aðgang að gagnasettinu til úrvinnslu.

2. **Taktu afrit af gagnageymslunni (e. repository)**:
   Inni í WEkEO JupyterLab terminal, skaltu taka afrit af gagnageymslunni:
    ```bash
    git clone https://lmi/Copernicus/Land/clms-hrsi-arlie_demo-iceland.git
    cd yourfolder/clms-hrsi-arlie_demo-iceland/
    ```

3. **Opnaðu og keyrðu vinnubókina**:
   - Farðu í `use_case_Oskjuvatn.ipynb` vinnubókina.
   - Fylgdu skrefunum í vinnubókinni til þess að byrja að gera greiningar á þeim breytingum sem hafa orðið á ísþekjunni **Öskjuvatni** á Íslandi og notaðu **ARLIE** gögnin.
4. **Settu upp þá pakka sem þarf og taktu út línur sem hafa verið settar sem "athugasemdir"** (ef þörf er á):
   - Opnaðu Jupyter vinnubókina `use_case_Oskjuvatn.ipynb`.
   - Sumar línur hafa viljani verið teknar út sem athugasemd. Þú þarft að laga þessar línur til þess að virkja hluta af kóðanum svo hægt sé að keyra hann.
   
   Hér er dæmi um hvað þú sérð í vinnubókinni:

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

   **Til þess að taka út athugasemd**, fjarlægðu `#` táknið til þess að virkja kóðann:

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

### Leiðbeiningar fyrir staðbundna uppsetningu (verður bætt við seinna)
Við munum bæta við leiðbeininugum í náinni framtíð um hvernig hægt er að keyra þessa kynningar vinnubók á staðbundið eða í annarri þjónustu eins og í **local Jupyter** uppsetningu eða á öðrum skýjavettvangi. Fylgist með!


***

## Lagayfirlýsing

Aðgangur að gögnum frá Copernicus er opinn, ókeypis og öllum frjáls samkvæmt **Gagna- og upplýsingastefnu Copernicusar** (Regulation (EU) No 1159/2013).Hægt er að sinna frekar upplýsingar [hér](http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159).

***

## Leyfi

Þessi gagnageymsla og innihald hennar er gefið út undir **MIT License**. sjá [LEYFI](LICENSE) fyrir frekari upplýsingar.

