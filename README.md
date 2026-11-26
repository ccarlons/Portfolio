# Carla Quartieri - Portfolio

Sito portfolio minimal con i miei poster e le mie grafiche realizzati in Photoshop, fatti per passione nel tempo libero.

Pagina singola in HTML, CSS e JavaScript puro: nessun framework e nessuna dipendenza da installare.

## Funzionalità

- **Modalità chiaro/scuro**, che segue il tema del sistema e ricorda la scelta dell'utente
- **Doppia lingua** (italiano/inglese) con transizione animata tra i due testi
- **Galleria di 10 lavori**: 3 visibili subito e 7 dietro il pulsante "Mostra altro"
- **Responsive**: pensato per desktop, tablet e telefono
- **Accessibilità**: palette con contrasti verificati e pensata per chi ha difficoltà con i colori, focus visibile da tastiera, rispetto della preferenza "riduci movimento"
- Link allo shop su Ko-fi e ai contatti

## Struttura del progetto

```
.
├── index.html      # pagina (HTML, CSS e JS in un unico file)
├── favicon.png     # icona della scheda del browser
├── images/         # foto personale e immagini dei lavori
└── README.md
```

> Per pubblicare su GitHub Pages il file principale deve chiamarsi `index.html`.

## Avviare in locale

Non serve installare nulla: apri `index.html` con un browser.

## Pubblicare con GitHub Pages

1. Carica i file in un repository su GitHub.
2. Vai su **Settings → Pages**.
3. In **Source** scegli il branch `main` e la cartella `/ (root)`.
4. Dopo qualche minuto il sito sarà online all'indirizzo `https://<nome-utente>.github.io/<nome-repository>/`.

## Personalizzazione

- **Colori**: variabili CSS in `:root` (tema chiaro) e `:root[data-theme="dark"]` (tema scuro), all'inizio del file.
- **Testi in due lingue**: oggetto `testi` nello script, con le chiavi `it` e `en`. Ogni elemento traducibile ha un attributo `data-i18n` che corrisponde a una chiave.
- **Lavori**: ogni lavoro è un blocco `<div class="lavoro">` con immagine, titolo e categoria. Le immagini sono in formato A4 verticale (210×297).
- **Foto e logo**: foto in `images/`, logo a cerchio con le iniziali nella navbar.

## Note

- Alcune immagini dei lavori sono ospitate su Ko-fi: se vengono rimosse da lì, spariscono dal sito. Per maggiore sicurezza si possono scaricare nella cartella `images/`.
- Font: [DM Sans](https://fonts.google.com/specimen/DM+Sans) da Google Fonts.

## Licenza

I poster e le grafiche sono opere di Carla Quartieri, tutti i diritti riservati. Le opere raffigurano personaggi e universi di proprietà dei rispettivi titolari. Il codice della pagina può essere riutilizzato come base per un proprio portfolio.
