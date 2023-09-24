# Plan

- hvordan sette opp et python enviroment
- Lære å hente data fra ssb
- Lære å skrive en analysetext
- lære plotting

# Hvordan sette opp et python enviroment

Biblioteker man trenger:

- numpy
- pandas
- pyjstat
- requests
- sklearn
- statsmodels (ikke nødvendig, men fint for dem som er kjent med R og stata)
- matplotlib
- seaborn
- plotly (til interaktive plots. Nice til EDA)
- jupyter notebook

### Installer miniconda og VScode

Miniconda kan lastes ned [her](https://docs.conda.io/en/latest/miniconda.html). \
VScode kan lastes ned [her](https://code.visualstudio.com/download).

Du kan bruke anaconda isteden for miniconda. Det er det samme systemet, men med et grafisk brukegrensesnitt. Jeg synes det blir stress og foretrekker bare gjøre alt i terminalen.

Det er også fritt frem å bruke den IDE-en man selv måtte ønske, men VScode støtter det meste og er mye brukt. Anbefaler derfor denne.

Dersom du velger VScode som din IDE så må du laste ned python og jupyter extentionene. Disse finner du i menyen til venste ved å trykke på ikonet med de fire boksene. Du har funnet de riktige når du finner dem med et vanvittig antall nedlastninger.

### Opprett nytt området

```console
conda create --name pareto_invest_makro python=3.11.5
```

### aktiver området

```console
conda activate pareto_invest_makro
```

### installer foreslåtte biblioteker

```console
pip install numpy pandas pyjstat requests scikit-learn statsmodels matplotlib seaborn plotly notebook
```
