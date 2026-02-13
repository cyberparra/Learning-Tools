# 📚 Learning Tools — Risorse Educative

Una pagina web **responsive e interattiva** che raccoglie oltre **420 link** a risorse educative per maker, coding, STEAM e intelligenza artificiale, organizzati in **44 categorie** navigabili.

---

## 🌐 Demo

Apri `learning-resources.html` direttamente nel browser — nessun server necessario, funziona offline.

---

## ✨ Funzionalità

- 🔍 **Ricerca in tempo reale** — filtra risorse per nome o URL mentre digiti
- 🏷️ **Filtro per categoria** — pill cliccabili per navigare rapidamente
- 📂 **Sottocategorie** — le sezioni più ricche (es. AI) sono organizzate in sottosezioni tematiche
- 🔗 **Tutti i link si aprono in una nuova finestra**
- 📱 **Design responsive** — ottimizzato per desktop, tablet e mobile
- ⚡ **Nessuna dipendenza esterna** — solo HTML, CSS e JavaScript vanilla (+ Google Fonts)

---

## 📁 Struttura del progetto

```
.
└── learning-resources.html   # File unico, tutto incluso
```

---

## 🗂️ Categorie

| # | Categoria | # | Categoria |
|---|-----------|---|-----------|
| 1 | 🧊 3D Asset | 2 | 💻 3D Coding |
| 3 | 🔷 3D Modeling | 4 | 🖨️ 3D Printing |
| 5 | 🌐 3D Resources | 6 | 🤖 AI *(14 sottocategorie)* |
| 7 | 🔗 Algoritmi | 8 | 🔌 API |
| 9 | ⚙️ Arduino | 10 | 🎨 Arte Generativa |
| 11 | ⚙️ Automata | 12 | 🔐 Blockchain |
| 13 | ⛓️ Chain Reaction | 14 | 🖥️ Coding |
| 15 | 🔑 Crittografia | 16 | 📋 Curriculum |
| 17 | 📊 Dataset | 18 | 📈 Data Visualization |
| 19 | 🤖 Drawing Robots | 20 | ⚡ Elettronica |
| 21 | 🔓 Escape Room | 22 | 🎭 Fake (educativo) |
| 23 | 🔭 Fisica | 24 | 🗺️ Geo / Geolocalizzazione |
| 25 | 🎲 Generatori | 26 | 🖼️ Grafica |
| 27 | 🖼️ Immagini | 28 | 📡 IoT |
| 29 | 🧱 LEGO | 30 | 🧠 Machine Learning |
| 31 | 🔧 Make / Maker | 32 | 📐 Matematica |
| 33 | ⚙️ Meccanica | 34 | 🌐 Metaverso |
| 35 | 🔬 Micro:bit | 36 | 🤖 LEGO Mindstorm |
| 37 | 🎵 Musica & Suoni | 38 | 🔴 Node-RED |
| 39 | 🎨 P5.js | 40 | 📜 Paper Circuits |
| 41 | 🟦 Pixel Art | 42 | 📁 Portfolio |
| 43 | 🐍 Python | 44 | 📱 QR Code |
| 45 | 🍓 Raspberry Pi | 46 | 🤖 Robotica |
| 47 | 🎮 Simulatori | 48 | 🚀 Spazio |
| 49 | 🔬 STEAM | 50 | ⚙️ Stepper Motor |
| 51 | 📖 Storytelling | 52 | 🔷 Tassellazione |
| 53 | 🎨 Texture | 54 | 🛠️ Tinkering |
| 55 | 🧰 Tools Generali | 56 | 🐢 Turtle Art |
| 57 | 🥽 VR / XR | 58 | 🌐 Web Coding |
| 59 | 📻 Web SDR / Radio | | |

### 🤖 Sottocategorie AI

La categoria AI è la più ricca e include:

`3D` · `Audio/Suono` · `Avatar` · `Curriculum` · `Edu` · `Fake & Deepfake` · `Font AI` · `Fumetti` · `Immagini Generative` · `LLM` · `Machine Learning` · `Math AI` · `P5.js & AI` · `Progetti AI` · `Robot` · `Scratch & AI` · `Tools AI` · `Video AI` · `Articoli & Documenti`

---

## 🚀 Setup

### 1. Clona il repository

```bash
git clone https://github.com/tuo-utente/learning-tools.git
cd learning-tools
```

### 2. Pubblica su GitHub Pages

Vai in **Settings → Pages**, seleziona il branch `main` e la cartella `/root`.  
GitHub ti fornirà un URL tipo `https://tuo-utente.github.io/learning-tools/`.

### 3. Crea un Personal Access Token

1. Vai su [github.com/settings/tokens](https://github.com/settings/tokens) → **Generate new token (classic)**
2. Seleziona lo scope **`repo`**
3. Copia il token generato (`ghp_…`)

> ⚠️ Il token non viene mai inviato a terze parti — viene usato **solo** per chiamare le GitHub API direttamente dal tuo browser.

### 4. Connetti l'interfaccia

Apri la pagina nel browser. Nella barra in cima inserisci:
- Il tuo **username GitHub**
- Il nome del **repository**
- Il tuo **Personal Access Token**

Clicca **Connetti** — i dati vengono caricati da `data.json` nel repo.

---

## ➕ Aggiungere risorse dall'interfaccia

Una volta connesso, clicca **＋ Aggiungi risorsa** in alto a destra:

1. Seleziona la **categoria** (o creane una nuova con nome, icona e colore)
2. Scegli eventuale **sottocategoria** (per categorie strutturate come AI)
3. Inserisci **descrizione** e **URL**
4. Clicca **Salva su GitHub**

Il file `data.json` viene aggiornato nel repository con un commit automatico. La pagina si aggiorna istantaneamente.

---

## 🗂️ Struttura file

```
.
├── learning-resources.html   # Interfaccia principale
├── data.json                 # Database risorse (aggiornato via GitHub API)
└── README.md
```

Il file `data.json` contiene un array di oggetti categoria:

```json
[
  {
    "id": "nome-categoria",
    "title": "Nome Categoria",
    "icon": "🔧",
    "color": "#f5eef8",
    "links": [
      { "note": "Descrizione risorsa", "url": "https://esempio.com" }
    ]
  }
]
```

---

## 🛠️ Tecnologie

- **HTML5 / CSS3 / JavaScript** vanilla — nessuna dipendenza
- **GitHub Contents API** — lettura e scrittura di `data.json`
- **Google Fonts** — Playfair Display + DM Sans
- **GitHub Pages** — hosting gratuito

Nessun framework, nessun build step, nessun server.

---

## 📄 Licenza

Questo progetto è distribuito sotto licenza **MIT**.  
Le risorse collegate appartengono ai rispettivi proprietari.

---

*Raccolta curata per docenti, educatori e maker — aggiornata continuamente.*
