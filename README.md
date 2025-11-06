# ⚡ Vite + React + Electron Setup

Et enkelt og moderne prosjektoppsett som kombinerer **Vite**, **React**, og **Electron** for å bygge raske og responsive skrivebordsapplikasjoner med webteknologi.

---

## 🚀 Funksjoner

- ⚡ **Vite** – Lynrask utviklingsserver og byggsystem  
- ⚛️ **React** – Komponentbasert UI-rammeverk  
- 💻 **Electron** – Kjør React-appen som en skrivebordsapplikasjon  
- 🔁 **Hot Reload** – Automatisk oppdatering ved endringer  
- 📦 Klar for bygging til Windows, macOS og Linux  

---

## 🧩 Struktur

```
vite+react+electron/
├── electron/          # Hovedprosessen (Electron)
│   ├── main.js
│   └── preload.js
├── src/               # React frontend (Renderer)
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── vite.config.js
└── README.md
```

---

## 🛠️ Installasjon

### 1️⃣ Klon repoet
```bash
git clone https://github.com/<ditt-brukernavn>/<repo-navn>.git
cd <repo-navn>
```

### 2️⃣ Installer avhengigheter
```bash
npm install
```

### 3️⃣ Start utviklingsmodus
```bash
npm start
```
Dette bygger Vite og Electron og starter Vite-serveren og Electron-appen samtidig.

---



## 🧠 Tips

- Endre `main.js` for å konfigurere vindustørrelse, meny, og app-logikk.
- `preload.js` brukes for å sende data mellom Electron (main) og React (renderer).
- Legg til flere npm-pakker etter behov, som f.eks. `axios`, `react-router`, eller `electron-store`.

---
