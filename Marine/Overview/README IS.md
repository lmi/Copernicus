# 🌊 Hafgögn Copernicusar rannsökuð í Google Colab

**Gagnvirk vinnubók (e. notebook) búin til af Náttúrufræðistofnun, notuð til þess að ná í og skoða hafgagnasett Copernicusar.**

---

### Yfirlit
Þessi vinnubók tengist **Hafvöktunarþjónustu Copernicusar** þar sem hægt er að birta og sækja öll tiltæk gagnasett.
Hún notar Python til að sækja sjálfvirkt lýsingar um gangasettin og búa til markdown skjöl.

Skriftan skráir sig inn með auðkenni sem er geymt í `login.json` og sækir lýsigögn í gegnum Copernicus Marine API.

### Leiðbeiningar
1. Opnaðu vinnubókina í Google Colab eða annarri skýjaþjónustu.
2. Gakktu úr skugga um að þú sért með rétta `login.json` skrá með gildum aðgangsupplýsingum.
3. Keyrðu meðfylgjandi kóða til þess að lýsingar á tiltækum þjónustum.

| Prófaðu kóðann í ókeypis skýjaþjónustum: | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lmi/Copernicus/blob/master/Marine/Overview/ConnectMarine.ipynb)

---

### Gagnlegt lesefni
- **Verkfærakista Copernicus Haf**: [Uppsetning verkfærakistunnar](https://help.marine.copernicus.eu/en/articles/7970514-copernicus-marine-toolbox-installation)
- **Sjónræn framsetning ganga með hjálp Python**: [Data Marine Visualization](https://help.marine.copernicus.eu/en/articles/4854800-how-to-open-and-visualize-copernicus-marine-data-using-python)

---

### Heimildir
- **Leyfi**: Þessi vinnubók er getin út undir **CC BY 4.0** leyfi.
- **Tilvitnun**: "*Höfundaréttur: Náttúrufræðistofnun*"
- **Höfundur**: Marco Pizzolato
- **Gagnaveitur**: [Copernicus Marine Service](https://marine.copernicus.eu/)
- **Unnið í**: Python með `requests` , `json` , og `pandas` fyrir gagnaöflun og úrvinnslu.

---

**Í þessari vinnubók er hægt að rannsaka  öll gagnasett Copernicusar um hafið á sjálvirkan hátt. Þetta gerir það að verkum að hafgögn eru enn sem gerir gögn um hafið aðgengilegri en áður.**