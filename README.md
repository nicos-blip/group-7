# 🚢 Ro-Ro Cargo Vision — Recruitment Landing Page

Landing page interattiva a scorrimento (formato carosello a 6 slide) per il reclutamento di talenti tecnici (Computer Vision, Edge AI, Backend, Hardware) per un progetto di ispezione automatica dei danni cargo nel settore marittimo Ro-Ro.

## 🚀 Caratteristiche
- **Hero con Video 1080p Integrato**: Video di sfondo ad alta definizione incorporato direttamente in Base64 (zero dipendenze da server esterni).
- **Design a 6 Slide**:
  1. *Hero*: Introduzione, video e call-to-action con accenti in azzurro/blu.
  2. *Il Problema*: Presunzione legale, ispezioni insufficienti e costi dei risarcimenti.
  3. *La Soluzione*: Telecamere AI multi-angolo e archivio digitale certificato.
  4. *Chi Cerchiamo*: AI/CV, Edge AI, Backend/Cloud, Hardware.
  5. *Cosa Offriamo*: Tesi/tirocini, esperienza hands-on, network industriale.
  6. *Candidatura*: Processo snello in 3 passi e form compatto.
- **Iconografia SVG Vettoriale**: 100% icone SVG native senza dipendenze esterne.
- **Multi-Input**: Navigazione via touch/swipe su mobile, frecce da tastiera, indicatori a punti e frecce a schermo.
- **Single-File Zero-Dependency**: Funziona istantaneamente aprendo `index.html` in qualsiasi browser.

## 🛠️ Stack Tecnologico
- **HTML5 & CSS3** (Custom transitions GPU-accelerate, responsive `clamp()`, CSS Grid & Flexbox)
- **Tailwind CSS** (per utility di base)
- **Vanilla JavaScript (ES6+)** (zero framework pesanti, 60fps costanti)
- **SVG Vettoriali Inline**

## 📬 Attivazione e Ricezione Candidature (Formspree)
Il form è già configurato per inviare i dati in modo asincrono (AJAX) senza ricaricare la pagina, mostrando la schermata di conferma con spunta animata. Per ricevere le candidature nella tua casella email e nella dashboard web:

1. Vai su [Formspree.io](https://formspree.io) e registrati gratuitamente con la tua email.
2. Clicca su **"+ New Form"**, dagli un nome (es. `Candidature Ro-Ro Vision`) e crea il form.
3. Copia l'ID del form o l'endpoint generato (ad esempio `https://formspree.io/f/mqkenwba`).
4. Apri [index.html](file:///c:/Users/lenovo/Desktop/Uni/Startup/landing/gruppo_7/index.html), trova il tag `<form id="contactForm"` (Slide 6) e sostituisci `YOUR_FORMSPREE_ID` con il tuo ID reale:
   ```html
   <form id="contactForm" action="https://formspree.io/f/mqkenwba" method="POST" onsubmit="handleSubmit(event)">
   ```
5. **Fatto!** Ogni volta che qualcuno invia una candidatura:
   - Riceverai immediatamente un'**email di notifica** con Nome, Cognome, Email, Ambito di competenza e Note.
   - Troverai tutte le candidature salvate e consultabili nella **dashboard di Formspree**, esportabili anche in Excel/CSV.

## 🌐 Pubblicazione Gratuita su GitHub Pages
Per rendere la landing page visibile online a chiunque:
1. Crea un repository su [GitHub](https://github.com/new).
2. Carica questo progetto sul repository.
3. Vai su **Settings** > **Pages** del repository.
4. Sotto **Build and deployment** seleziona il branch `main` (cartella `/root`) e clicca su **Save**.
5. In circa 1 minuto il tuo sito sarà online all'indirizzo:
   `https://<tuo-username>.github.io/<nome-repo>/`

