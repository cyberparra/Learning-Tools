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

## 🚀 Come usare

1. **Clona o scarica** il repository
   ```bash
   git clone https://github.com/tuo-utente/learning-tools.git
   ```

2. **Apri il file** nel browser
   ```bash
   open learning-resources.html
   # oppure fai doppio click sul file
   ```

3. Usa la **barra di ricerca** in alto o clicca sulle **pill** per filtrare per categoria.

---

## 🛠️ Tecnologie

- **HTML5** — struttura semantica
- **CSS3** — custom properties, grid, flexbox, animazioni
- **JavaScript** (vanilla) — ricerca, filtri, rendering dinamico
- **Google Fonts** — Playfair Display + DM Sans

Nessun framework, nessuna dipendenza npm, nessun build step.

---

## 🤝 Contribuire

Hai una risorsa da aggiungere? Apri una **Issue** o una **Pull Request**!

Per aggiungere un link, modifica l'oggetto della categoria corrispondente nel blocco `DATA` all'interno di `learning-resources.html`:

```javascript
{
  note: "Nome descrittivo della risorsa",
  url: "https://esempio.com"
}
```

Per aggiungere una nuova categoria, aggiungi un nuovo oggetto all'array `DATA`:

```javascript
{
  id: "nome-categoria",        // identificatore unico (kebab-case)
  title: "Nome Categoria",     // titolo visualizzato
  icon: "🔧",                  // emoji icona
  color: "#f5eef8",            // colore di sfondo dell'header card
  links: [
    { note: "Descrizione", url: "https://..." }
  ]
}
```

---

## 📄 Licenza

Questo progetto è distribuito sotto licenza **MIT**.  
Le risorse collegate appartengono ai rispettivi proprietari.

---

*Raccolta curata per docenti, educatori e maker — aggiornata continuamente.*
