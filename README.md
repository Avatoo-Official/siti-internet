# Siti internet — Avatoo

Raccolta dei siti web realizzati da Avatoo con Claude. Ogni sito vive nella propria cartella ed è indipendente dagli altri.

## Siti

| Cartella | Cliente | Stato | Progetto claude.ai |
|---|---|---|---|
| [`marcellini/`](marcellini/) | Studio legale Marcellini | In avvio | Marcellini - Sito Internet |

## Come funziona

- **Materiali e decisioni** (brief, testi, logo, colori, scelte prese) stanno nel Progetto claude.ai del cliente.
- **Codice** sta qui, nella cartella del sito, ed è sviluppato con Claude Code.
- Ogni cartella ha un `CLAUDE.md` con il riassunto di brief e regole: è il ponte tra il Progetto e il codice.

## Regole della repository

- Una cartella per sito, in minuscolo con trattini (es. `studio-rossi`).
- Nessun file condiviso tra siti: ogni sito ha le sue dipendenze e la sua configurazione.
- Messaggi di commit con il prefisso del sito: `marcellini: aggiunta pagina contatti`.
- Branch con il prefisso del sito: `marcellini/pagina-contatti`.
- Mai committare password, chiavi API o dati FTP: vanno in file `.env` (esclusi da git).

## Aggiungere un nuovo sito

1. Crea la cartella `nome-cliente/`.
2. Copia `_template/CLAUDE.md` dentro la cartella e compilalo.
3. Crea il Progetto su claude.ai per i materiali del cliente.
4. Aggiungi la riga nella tabella qui sopra.
