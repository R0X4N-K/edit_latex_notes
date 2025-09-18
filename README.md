# Elementi di Informatica Teorica — Appunti

📚 Raccolta di appunti per il corso di **Elementi di Informatica Teorica (EDIT)**, scritti in LaTeX e basati sul [latex-notes-template](https://github.com/R0X4N-K/latex-notes-template).

---

## 📌 Caratteristiche

* Struttura modulare per capitoli (`chapters/`)
* Notazioni matematiche tipograficamente curate
* Blocchi per definizioni, teoremi, lemmi e dimostrazioni
* File di configurazione separati (`preamble.tex`, `blocks.tex`)
* Compilazione semplificata tramite `make`

---

## 🚀 Come usare

1. Clona questa repository:

   ```bash
   https://github.com/R0X4N-K/edit_latex_notes
   cd edit-latex-notes
   ```

2. Assicurati di avere installato:

   * **LuaLaTeX**
   * **Make**

3. Compila gli appunti con:

   ```bash
   make
   ```

Otterrai un file `main.pdf` nella cartella build/.

---

## 📂 Struttura della repo

```
edit-latex-notes/
│── chapters/        # Capitoli degli appunti
│── sources/         # File di struttura e blocchi prefabbricati
│   │── preamble.tex # Impostazioni e pacchetti
│   └── blocks.tex   # Definizione di blocchi (Teoremi, Lemmi, ecc.)
│── res/             # Risorse aggiuntive (immagini, figure, ecc.)
│── main.tex         # File principale
│── Makefile         # Compilazione
└── README.md
```

---

## 🔗 Template di riferimento

Questi appunti si basano sul progetto [latex-notes-template](https://github.com/R0X4N-K/latex-notes-template).
Se vuoi creare i tuoi appunti personalizzati, puoi partire direttamente dal template.

---

## 📖 Licenza

Distribuito sotto licenza MIT. Puoi usare, modificare e condividere liberamente, citando la fonte.

