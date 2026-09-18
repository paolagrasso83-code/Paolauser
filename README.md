# ÁTTI — Sito web makeup artist (Catania)

Sito statico (HTML/CSS/JS puro, nessuna installazione richiesta) pronto per essere pubblicato online.

## Struttura del progetto

```
index.html          → la pagina del sito
css/style.css        → stile grafico (editoriale, bianco/nero)
js/main.js            → menu mobile + piccoli comportamenti
assets/gallery/       → metti qui le foto reali (poi collegale nell'HTML, vedi sotto)
```

## Cosa devi ancora personalizzare

Nel file `index.html` cerca il testo `✎` (o la classe `edit-note`) per trovare tutti i punti da completare:

1. **Foto** — sostituisci i riquadri grigi in "Chi sono" e "Galleria" con foto vere.
   - Metti i file in `assets/gallery/` (es. `assets/gallery/foto1.jpg`)
   - Nell'HTML, sostituisci `<div class="gallery-item">...</div>` con `<div class="gallery-item"><img src="assets/gallery/foto1.jpg" alt="Trucco sposa, dettaglio occhi"></div>`
   - Scegli le 6-9 foto migliori e più recenti dal profilo Instagram (@maryling80_makeup) — dettagli ravvicinati, buona luce, prima/dopo se disponibili.
2. **Bio** — nella sezione "Chi sono", scrivi 2-3 frasi vere in prima persona (anni di esperienza, formazione, collaborazioni, cosa rende il tuo stile riconoscibile).
3. **Recensioni** — sostituisci i placeholder `[Inserisci qui una recensione reale]` con frasi vere di clienti soddisfatte (chiedi il permesso prima di pubblicare nome/cognome).
4. **Email** — quando avrai un'email professionale, aggiungi un link `mailto:` nella sezione "Contatti".
5. **WhatsApp** — il numero è già impostato (+39 340 320 5835). Se cambia, aggiornalo in `index.html` (cerca `393403205835`, compare 3 volte).
6. **Nome brand** — se in futuro vuoi cambiare "ÁTTI", cerca/sostituisci la stringa in tutto `index.html` e nel `<title>`.

---

## Come mettere online il sito (gratis)

Il sito è statico: basta "appoggiarlo" su un hosting gratuito, nessun server da gestire.

**Opzione consigliata: Netlify**
1. Vai su [netlify.com](https://netlify.com) e crea un account gratuito.
2. Trascina la cartella del progetto nella dashboard ("Deploy manually") — oppure collega il repository GitHub per aggiornamenti automatici ad ogni modifica.
3. In pochi secondi ottieni un link tipo `atti-makeup.netlify.app`.
4. Da "Domain settings" potrai collegare il dominio vero una volta acquistato (vedi sotto).

Alternative equivalenti e altrettanto valide: **Vercel** (vercel.com) o **GitHub Pages** (gratis se il codice è su GitHub).

---

## Dominio (es. attimakeup.it)

1. **Scegli il nome a dominio.** Suggerimenti da verificare:
   - `attimakeup.it`
   - `atti-makeup.it`
   - `attimakeup.com` (se vuoi puntare anche a clienti internazionali/turisti)
2. **Verifica disponibilità e registralo** tramite un registrar accreditato. Per `.it` serve un codice fiscale italiano (tua sorella lo ha di sicuro), quindi è una procedura semplice. Alcune opzioni affidabili:
   - **Aruba.it** — italiano, economico, assistenza in italiano, molto usato dai freelance IT.
   - **Register.it** — italiano, semplice da usare.
   - **Cloudflare Registrar** — prezzi "at cost" (senza margine), ottimo se vuoi anche gestire il DNS lì, ma disponibile solo per alcuni domini già registrati altrove (serve trasferirlo dopo il primo anno).
   - **Namecheap** — internazionale, economico, buona per `.com`.
   Costo indicativo: 8–15 €/anno per un `.it`, 10–15 €/anno per un `.com`.
3. **Collega il dominio all'hosting** (Netlify/Vercel/GitHub Pages ti daranno 2-3 record DNS da inserire nel pannello del registrar — è una procedura guidata, ci vogliono 10 minuti + qualche ora di propagazione).

---

## Email professionale (es. info@attimakeup.it)

Un'email con il dominio proprio (invece di una Gmail generica) è ciò che fa sembrare un'attività seria fin dal primo contatto. Opzioni:

- **Google Workspace** — ~6-7 €/mese per utente, ottiene Gmail con il dominio proprio + Calendar/Drive. Il più semplice da usare.
- **Zoho Mail** — piano gratuito disponibile per un dominio singolo (con limiti), oppure piani a pagamento molto economici (~1 €/mese). Ottimo se il budget è ridotto all'inizio.
- **Aruba / Register.it** — spesso includono caselle email nel pacchetto dominio+hosting, comodo se si registra il dominio lì.

Suggerimento: puoi iniziare **senza** email dedicata (usando WhatsApp/Instagram come canali principali, come già impostato nel sito) e aggiungerla appena il dominio è attivo — non è bloccante per partire.

---

## Altri passi per essere "trovabile" e professionale

1. **Google Business Profile** (gratuito, essenziale per un'attività locale)
   Crea il profilo su [google.com/business](https://www.google.com/business/) come "Truccatrice / Makeup artist" a Catania. Fa apparire l'attività su Google Maps e nelle ricerche locali ("truccatrice Catania"), con recensioni, orari, foto e link al sito/WhatsApp.
2. **Partita IVA** — se l'attività supera 5.000 €/anno o diventa continuativa, va aperta. Regime forfettario consigliato per la maggior parte delle make-up artist (imposta al 5% i primi 5 anni). Codice ATECO tipico: `96.02.02` (istituti di bellezza) o `96.09.09`. Si apre gratis online con SPID tramite l'Agenzia delle Entrate, oppure con un commercialista (100-200 €).
3. **WhatsApp Business** (gratuito) — invece del WhatsApp personale, permette catalogo servizi, risposte automatiche, orari e statistiche.
4. **Coerenza tra i canali** — usa lo stesso nome "ÁTTI", stessa palette bianco/nero e stesso logo/font su Instagram, WhatsApp Business e sito, per essere riconoscibile ovunque.

---

## Checklist rapida per partire

- [ ] Caricare 6-9 foto vere in `assets/gallery/` e collegarle nell'HTML
- [ ] Scrivere la bio reale in "Chi sono"
- [ ] Raccogliere 2-3 recensioni vere
- [ ] Pubblicare il sito su Netlify (gratis, 10 minuti)
- [ ] Registrare il dominio scelto
- [ ] Collegare il dominio a Netlify
- [ ] Creare il Google Business Profile
- [ ] (quando pronta) Attivare email professionale e aggiungerla al sito
