# Data-Analyse — projecten Yelena Hostens

Deze repository bundelt enkele programmeer- en data-analyseprojecten uit mijn
opleiding. Ze geven een beeld van mijn vaardigheden in Python, Jupyter Notebook
en data-analyse, met een focus op sport- en bewegingsdata.

**Achtergrond:** Bachelor zorgtechnologie, keuzetraject sporttechnologie
(VIVES Kortrijk). Grootste interesse: data-analyse in een sport- en
voetbalcontext.

---

## Overzicht

| Bestand | Onderwerp | Aanrader |
|---|---|---|
| `python.zip` | Simulatie van het zonnestelsel (Python) | |
| `Data analyse 1 taak 1.zip` | Analyse van sportprestatiedata | |
| `data analyse 1 taak 2.zip` | Data-analyse met visualisaties per speler | ✅ |
| `data analyse 2.zip` | Activiteitsherkenning op basis van sensordata | ✅ |

De twee aanraders geven het beste beeld van mijn vaardigheden op het vlak van
data-analyse.

> **Tip om te bekijken:** download de gewenste `.zip`, pak ze uit en open het
> notebook (`.ipynb`) met Jupyter Notebook, VS Code of Google Colab. De Jupyter-
> notebooks zijn op zichzelf leesbaar: code, uitleg en resultaten staan samen.

---

## Projecten in detail

### `python.zip` — Simulatie van het zonnestelsel

Een simulatie die ik in mijn eerste jaar aan de VUB in Python schreef. Ze
berekent de banen van de zon, de planeten en enkele manen op basis van
zwaartekracht, momentum en positie-updates per tijdstap.

**Inhoud**
- `solar_system.py` — de volledige simulatie
- `planeten.txt` — de gegevens van de hemellichamen (straal, baanafstand, massa,
  baansnelheid, kleur)

**Uitvoeren**
```
pip install vpython
python solar_system.py
```
De simulatie opent automatisch in een browsertabblad (vpython rendert niet in de
terminal zelf).

---

### `Data analyse 1 taak 1.zip` — Analyse van sportprestatiedata

Een Jupyter-notebook waarin een dataset met sportprestatiegegevens wordt
ingelezen en geanalyseerd.

**Inhoud**
- `06_les.ipynb` — het notebook met de analyse
- `sports_performance_data.csv` — de bijhorende dataset (aanwezig, dus volledig
  uitvoerbaar)

---

### `data analyse 1 taak 2.zip` — Data-analyse met visualisaties per speler ✅

Een uitgebreidere opdracht waarin per speler een visualisatie wordt opgebouwd.

**Inhoud**
- `les_12_Yelena.ipynb` — het notebook met de analyse en de code voor de
  visualisaties
- `player_*.png` — de gegenereerde visualisaties per speler
- `Les 12 screenshots.docx` — Word-document met screenshots van de resultaten
- `terrain.csv` — hulpbestand

**Let op:** de grote bron-CSV ontbreekt omdat die te groot was om mee te delen.
De notebook is daardoor niet volledig opnieuw uitvoerbaar, maar de resultaten
zijn goed te volgen via het Word-document met screenshots en via de
gegenereerde `player_*.png`-bestanden.

---

### `data analyse 2.zip` — Activiteitsherkenning op basis van sensordata ✅

Het project waarin ruwe sensordata wordt verwerkt om verschillende bewegingen te
herkennen. De data is opgenomen voor vijf activiteiten: keepen, lopen, trappen,
wandelen en zitten, telkens met accelerometer- (Acc), gyroscoop- (Gyr) en
oriëntatiemetingen (Ori).

In het notebook worden deze metingen samengevoegd en omgezet naar features
(berekend per venster van 2 seconden) om de verschillende bewegingen van elkaar
te kunnen onderscheiden.

**Inhoud**
- `taak2.ipynb` — het notebook met de volledige verwerking en analyse
- `Acc*.csv`, `Gyr*.csv`, `Ori*.csv` — de ruwe sensordata per activiteit
- `alles_samengevoegd.csv`, `Gecombineerd.csv` — de samengevoegde datasets
- `features_2s.csv` — de berekende features per venster van 2 seconden

Alle data is aanwezig, dus dit notebook is volledig uitvoerbaar.

---

## Gebruikte tools

- **Python** in **Jupyter Notebook** (`.ipynb`) met de gebruikelijke
  data-analysebibliotheken voor het inlezen, verwerken en visualiseren van data
- **vpython** voor de 3D-simulatie van het zonnestelsel
- **CSV-bestanden** als databron
