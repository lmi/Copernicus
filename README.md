# Vöktunarþjónusta Copernicus - vinnustofur

Þessi gagnageymsla inniheldur skriftur, kóða og heimildir úr verklegum vinnustofum þar sem fjallað var um vöktun á **Landi**, **Hafi**, and **Andrúmslofti**. Á vinnustofunum var notast var við gögn og þjónustur frá Copernicus.


## Yfirlit

Vinnustofurnar eru hannaðar með byrjendur í huga þar sem áhersla var lögð á að læra að nota Copernicusargögn á hagnýtan hátt. Hver vinnustofa skiptist upp í tvo hluta með fyrirlestrum fyrir hádegi og verklegum æfingum eftir hádegi. Þátttakendur fá að spreyta sig á fyrirfram undirbúnum skriftum og "vinnubókum" (e. notebooks), sem þeir geta svo aðlagað að eigin þörfum.

### Viðfangsefni vinnustofanna

1. **Vöktun lands**
   - Fyrir hádegi: Kynning á landvöktunarþjónustu Copernicusar og sýnd dæmi um notkun. 
   - Eftir hádegi: Verklegur hluti þar sem notaðar verða aðlagaðar skriftur úr gagnageymslu EEA til þess að skoða gagnasett úr landvöktunarþjónustunni og bæta verkferlið.
   
2. **Vöktun hafs** 
   - Fyrir hádegi: Kynning á hafvöktunarþjónustu Copernicusar
   - Eftir hádegi: Verklegur hluti þar sem gagnsett frá hafinu verða könnuð nánar.

3. **Vöktun andrúmslofts** 
   - Fyrir hádegi: Kynning á loftgæðaþjónustu Copernicusar
   - Eftir hádegi: Verklegur hluti þar sem gagnsett frá loftgæðaþjónustunni verða könnuð og tól til að meta gæði andrúmslofts skoðuð.
---

## Vinnustofa: Landvöktunarþjónustan

### Lýsing

Í þessari vinnustofu munum við notast sérsniðnar skriftur byggðar á skriftum frá **EEA Land Monitoring Repository** sem hafa verið aðlagaðar að okkar þörfum. Auk þess var bætt við eiginleikum til að bæta verkferlið. Þátttakendur munu læra um ARLIE gögn sem og gögn sem ætluð eru til að vakta snjó- og ísþekjur. Þau munu einnig læra að greina gögn með ólíkum gagnasettum frá landvöktunarþjónustu Copernicusar.

### Uppbygging

- `Land/`: Inniheldur vinnubækur fyrir verklega hlutann í Landvöktunarþjónustu Copernicusar.
- `/clms-hrsi-arlie_demo-iceland/`: Inniheldur dæmi og æfingar um hvernig á að niðurhala og vinna úr ARLIE gögnum.
- `/land_use/`: Inniheldur vinnubækur til niðurhals og gögn til úrvinnslu frá WEkEO, eins og Urban Atlas og Corine lulc (í náinni framtíð).

## Vinnustofa: Hafvöktunarþjónustan

### Lýsing

Í þessari vinnustofu notum við sérsniðnar skriftur byggðar á gögnum frá **Mercator Ocean International - Copernicus Marine**, sem hafa verið aðlagaðar að okkar þörfum. Auk þess var bætt við eiginleikum til að bæta verkferlið. Þátttakendur munu læra um lífefnafræðileg gögn, hitabylgjur sjávar og að greina gögn með ólíkum gagnasettum frá hafvöktunarþjónustu Copernicusar.

### Uppbygging

- `Marine/`: Inniheldur möppur fyrir veklega hlutann í vinnustofunni um vöktun hafsvæða hjá Copernicus.
- `/Biogeochemical/`: Inniheldur lífefnafræðilegar vinnubækur fyrir verklega hlutann í vinnustofunni um vöktun hafsvæða hjá Copernicus.
   - `/out/`: Inniheldur úttak frá niðurstöðum vinnubókarinnar.
- `/Marine_Heat_Wave/`: Inniheldur vinnubækur um hitabylgjur sjávar fyrir verklega hlutann í vinnustofunni um vöktun hafsvæða hjá Copernicus.
   - `/out/`: Inniheldur úttak frá niðurstöðum vinnubókarinnar.
   - `/img/`: Inniheldur myndir sem styðja við vinnubókina.

## Vinnustofa: Loftgæðaþjónustan

### Lýsing

Í þessari vinnustofu notum við sérsniðnar skriftur byggðar á gögnum frá ****, asem hafa verið aðlagaðar að okkar þörfum. Auk þess var bætt við eiginleikum til að bæta verkferlið. Þátttakendur munu læra ....

### Uppbygging

- `Atmosphere/`: Inniheldur vinnubók fyrir verklega hlutann í vinnustofunni um loftgæðavöktun Copernicusar.
   - `/img/`: Inniheldur myndir sem styðja við vinnubókina



---

## Getting Started

### Forsendur

- Grunnþekking í Python er gagnleg en ekki nauðsynleg.
- Vefvafri og internettenging til þess að komast inn í þjónustur Copernicusar.
- Nauðsynlegt að hafa [Jupyter Notebook](https://jupyter.org/install) uppsett eða nota netþjónustur (t.d WEkEO, Kaggle, Google Colab eða Copernicus )

### Uppsetning

1. Afritaðu gagnageymsluna (e. repository):
    ```bash
    git clone https://github.com/lmi/copernicus.git
    cd copernicus
    ```

2. Settu upp nauðsynlega pakka (ef það eru einhverjir):
    ```bash
    pip install -r requirements.txt
    ```

3. Ræstu Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Farðu í viðeigandi verkefnamöppu (t.d., `LAND` ) til að byrja að skoða og nota skriftur.

---
## Leyfi

Þessi gagnageymsla er gefinu út undir [CC BY 4.0 License](LICENSE).

