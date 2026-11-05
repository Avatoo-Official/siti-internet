# Studio legale Marcellini — istruzioni per Claude

Lavora **solo** dentro la cartella `marcellini/`. Non modificare altri siti della repository.

**Fase attuale: analisi.** Non scrivere codice del sito finché la fase non cambia.

## Fonte dei materiali
Progetto claude.ai: **Marcellini - Sito Internet**
- `brief-sito-marcellini.md` — brief e decisioni (fonte principale)
- `analisi-sito-marcellini.md` — analisi del sito attuale, requisiti SEO/AI/accessibilità, domande aperte

Se un'informazione manca qui, cercala nel Progetto prima di inventarla.

## Cliente
- Studio legale Marcellini — avv. Mario Marcellini, cassazionista, civilista
- Sito attuale: https://www.studiomarcellini.net/ (da sostituire; il blog non viene riportato)
- Sedi: Nettuno (RM), via Ennio Visca 43 — tel. 06 56546859; Pergola (PU), via Nicoletti 13 — tel. 347 5939640
- PEC mario.marcellini@oav.legalmail.it · email anziolex@studiomarcellini.net · P.IVA 06506031001

## Struttura del sito
- Home (con recensioni Google)
- Lo studio: Mario Marcellini, avvocato 2, consulente 1, consulente 2 (una pagina ciascuno) — nomi [DA COMPLETARE]
- Servizi: Diritto civile, Diritto amministrativo
- Articoli (forniti dallo studio)
- Contatti
- Consulenza online: form + link di pagamento PayPal
- Condizioni d'uso, Privacy, Cookie policy

## Requisiti
- SEO di nuova generazione e leggibilità da parte delle AI: HTML leggibile senza JavaScript, JSON-LD schema.org (LegalService, Person, Service, Article, FAQPage, BreadcrumbList), `robots.txt` aperto ai crawler AI, `llms.txt`, sitemap, redirect 301 dai vecchi URL (anche `/index.php/...`)
- Ogni pagina servizio apre con una risposta diretta: cosa, per chi, dove
- Mobile-first, desktop e mobile
- Accessibilità WCAG 2.2 AA

## Tecnica
- Tecnologia: [DA DECIDERE — proposta: sito statico, es. Astro]
- Hosting: [DA DECIDERE]

## Regole
- Testi in italiano.
- Nessun dato inventato (nomi, indirizzi, telefoni, recensioni, casi vinti): usa `[DA COMPLETARE]`.
- Codice deontologico forense (art. 35): informazioni veritiere, non suggestive, non comparative, niente promesse di risultato.
- Commit con prefisso `marcellini: ...`.
