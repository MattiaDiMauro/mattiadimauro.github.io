# Mattia Di Mauro - CV (GitHub Pages)

Una versione moderna del CV in HTML/CSS ospitata gratuitamente su GitHub Pages.

**URL finale:** `https://mattiadimauro.github.io`

---

## Setup Rapido (5 minuti)

### 1. Crea un nuovo repository su GitHub

Vai su [github.com/new](https://github.com/new) e crea un repository con questo nome **esatto**:

```
mattiadimauro.github.io
```

**Importante:** Il nome deve essere `[tuousername].github.io` per funzionare con GitHub Pages.

### 2. Clona il repository localmente

```bash
git clone https://github.com/MattiaDiMauro/mattiadimauro.github.io.git
cd mattiadimauro.github.io
```

### 3. Copia i file

Copia questi tre file nella cartella del repository:
- `index.html`
- `style.css`
- `README.md`

### 4. Carica su GitHub

```bash
git add .
git commit -m "Initial commit: CV website"
git push origin main
```

### 5. Attiva GitHub Pages

1. Vai a **Settings** del repository
2. Seleziona **Pages** dal menu laterale
3. Sotto "Build and deployment", assicurati che:
   - **Source** = "Deploy from a branch"
   - **Branch** = `main` (o `master`)
4. Salva

✅ **Fatto!** Tra 1-2 minuti il CV sarà online a `https://mattiadimauro.github.io`

---

## Come modificare il CV

### Opzione 1: Modificare su GitHub (più semplice)
1. Apri `index.html` nel repository su GitHub
2. Clicca l'icona della matita (Edit)
3. Apporta le modifiche
4. Clicca **Commit changes**
5. Il sito si aggiorna automaticamente in ~10 secondi

### Opzione 2: Modificare localmente (per esperti)
```bash
# Modifica i file localmente
# Poi:
git add .
git commit -m "Update CV: [descrizione modifiche]"
git push origin main
```

---

## Personalizzazione

### Cambiare i colori
Apri `style.css` e modifica le variabili CSS all'inizio:

```css
:root {
    --royal-blue: #0038a6;  /* Cambia questo */
    --dark-text: #2c3e50;
    --light-gray: #f5f5f5;
    --border-gray: #d0d0d0;
    --white: #ffffff;
}
```

### Aggiungere sezioni
Aggiungi una nuova sezione in `index.html`:

```html
<section class="cv-section">
    <h2 class="section-title">Nuova Sezione</h2>
    <!-- Contenuto qui -->
</section>
```

### Font
Il CV usa font di sistema per velocità. Se vuoi font custom:

```css
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap');
body {
    font-family: 'Lato', sans-serif;
}
```

---

## Features

✅ **Responsive** — Bello su mobile, tablet, desktop
✅ **Print-friendly** — Stampa perfetta da browser (Ctrl+P)
✅ **SEO-optimized** — Trovabile su Google
✅ **Fast** — Carica in millisecondi
✅ **No database** — Niente server, puro HTML/CSS
✅ **Gratis** — GitHub Pages è gratuito

---

## Condividere il CV

**Con reclutatori:**
- Semplicemente dai il link: `https://mattiadimauro.github.io`
- Loro vedranno una pagina moderna e professionale
- Possono stamparla o scaricarla come PDF (Ctrl+P → Salva come PDF)

**In email:**
```
Subject: CV - Mattia Di Mauro

Hi,

Puoi trovare il mio CV qui: https://mattiadimauro.github.io

Best,
Mattia
```

---

## Troubleshooting

**Il sito non appare dopo 5 minuti:**
- Verifica che il repository si chiami `mattiadimauro.github.io` (esatto)
- Controlla che **Pages** sia abilitato nelle Settings
- Prova a svuotare il cache del browser (Ctrl+Shift+Del)

**La pagina mostra errore 404:**
- Assicurati che `index.html` sia nella root del repository
- Controlla che `style.css` sia nello stesso livello di `index.html`

**Vuoi un dominio custom (es. `mattia.dev`):**
- Acquista il dominio (Namecheap, Google Domains, etc.)
- Nelle Settings > Pages, aggiungi il dominio custom
- Segui le istruzioni DNS

---

## Versione offline

Per visualizzare il CV offline:
1. Scarica `index.html` e `style.css`
2. Mettili nella stessa cartella
3. Apri `index.html` nel browser

Funziona perfettamente anche locale!

---

## Next Steps

Dopo aver creato il CV online:

1. **Aggiungi il link al CV nel tuo profilo LinkedIn**
   - Sezione "Website" del profilo
   - Inserisci: `https://mattiadimauro.github.io`

2. **Incluди il link nelle candidature**
   - Quando un reclutatore chiede "CV URL", dai questo link
   - È molto più impressionante di un PDF anonimo

3. **Mantienilo aggiornato**
   - Ogni 2-3 mesi, refresha progetti e skills
   - Aggiungi nuovi progetti interessanti

---

**Made with | HTML/CSS | 2026**
