# Studio Legale Mazzotta — Sito istituzionale

Sito web ufficiale dello **Studio Legale Mazzotta** — boutique legale con sede a Cologno Monzese (MI).

🌐 **[www.studiolegalemazzotta.it](https://www.studiolegalemazzotta.it)**

## Stack

- HTML statico multipagina — nessun framework, nessun build step
- [Tailwind CSS](https://tailwindcss.com) via CDN
- Font auto-ospitati (Cormorant Garamond, Instrument Sans)
- Form di contatto: [Formspark](https://formspark.io) + [Botpoison](https://botpoison.com)
- Hosting: GitHub Pages

## Struttura

```
├── index.html                  # Home
├── metodo-forense.html         # La Struttura / Modello Operativo
├── Aree-di-tutela.html         # Funzioni Strategiche
├── casi-studio.html            # Casi Studio
├── contatti.html               # Contatti e form riservato
├── privacy-policy.html
├── cookie-policy.html
├── termini-e-condizioni.html
├── 404.html                    # Pagina non trovata
├── fonts.css / fonts/          # Font self-hosted
├── sitemap.xml / robots.txt
└── CNAME                       # Dominio custom GitHub Pages
```

## Architettura privacy

Il sito non installa cookie e non effettua tracciamento. La mappa Google Maps
è caricata solo su azione esplicita dell'utente (click-to-load facade):
nessuna connessione a terze parti prima del consenso.

## Deploy

Push su `main` → pubblicazione automatica via GitHub Pages. Nessuna pipeline.

## Licenza

© Studio Legale Mazzotta — Tutti i diritti riservati.
Contenuti, testi e materiali grafici non sono riutilizzabili senza autorizzazione scritta.
Per segnalazioni di sicurezza: vedi [SECURITY.md](SECURITY.md).
