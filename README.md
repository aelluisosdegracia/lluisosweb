# ⚜️ AE Lluïsos de Gràcia - Portal Web

Aplicació web oficial per a l'**Agrupament Escolta Lluïsos de Gràcia**. Aquest lloc web proporciona informació sobre l'agrupament, novetats, el calendari del curs, l'equip de caps per branca, el mapa interactiu "El Foulard pel Món", la botiga de marxandatge i la Quiniela de caps.

---

## 🚀 Característiques

- **Pàgina d'Inici (`/`)**: Secció *Hero*, presentació "Qui som", darreres novetats i carrusel de l'equip de caps.
- **Novetats (`/novetats`)**: Tauler amb avisos, notícies i activitats recents.
- **Calendari (`/calendari`)**: Visualitzador interactiu d'esdeveniments, sortides, campaments i reunions.
- **Equip de Caps (`/equips`)**: Fitxes dels caps organitzats per branques (Castors i Llúdrigues, Llops i Daines, Ràngers i Noies Guia, Pioners i Caravel·les, Ròvers i Caps de Grup).
- **El Foulard pel Món (`/foulard`)**: Mapa interactiu amb xinxetes dels viatges i llocs on ha viatjat el foulard de l'agrupament.
- **Botiga (`/botiga`)**: Catàleg de productes i marxandatge de l'agrupament.
- **Quiniela (`/kiniela`)**: Joc interactiu per endevinar quins caps aniran a cada branca el curs vinent.
- **Integració amb Google Sheets**: Lectura de dades en temps real des de fulls de càlcul de Google i sincronització de les respostes de la Quiniela (amb mode offline de suport integrat si no hi ha connexió o credencials).

---

## 📁 Estructura del Projecte

```text
LLuisosWeb/
├── app.py                   # Servidor Flask principal i rutes HTTP/API
├── gsheets_db.py            # Adaptador de base de dades (Google Sheets + dades locals)
├── requirements.txt         # Dependències de Python
├── run.bat                  # Script per iniciar l'aplicació a Windows
├── .gitignore               # Exclusions per a Git
├── README.md                # Documentació del projecte
├── templates/               # Plantilles HTML (Jinja2)
│   ├── base.html            # Plantilla base amb capçalera i peu
│   ├── index.html           # Pàgina d'inici
│   ├── novetats.html        # Pàgina de notícies
│   ├── calendari.html       # Pàgina de calendari
│   ├── equips.html          # Pàgina de l'equip de caps
│   ├── foulard.html         # Mapa del foulard
│   ├── shop.html            # Botiga de marxandatge
│   └── kiniela.html         # Joc de la quiniela
└── static/                  # Fitxers estàtics
    ├── css/                 # Fulls d'estil CSS
    ├── js/                  # Scripts JavaScript
    ├── images/              # Imatges i icones
    ├── fonts/               # Tipografies
    └── data/                # Dades auxiliars
```

## 📝 Llicència

Projecte desenvolupat per a l'**AE Lluïsos de Gràcia**.
