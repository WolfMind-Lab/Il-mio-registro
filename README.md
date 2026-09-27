# Il Mio Registro V2 — PWA

Registro personale per spese, rate, scadenze, pagamenti ed entrate.

## Funzioni
- dashboard e saldo previsto
- scadenza ufficiale, pagamento programmato e pagamento effettivo
- rate e piano rateale
- stato da pagare / programmato / pagato
- calendario finanziario
- ricerca avanzata
- categorie separate da metodo di pagamento
- modifica, duplicazione ed eliminazione
- backup JSON import/export
- PWA installabile quando pubblicata su HTTPS
- cache offline tramite Service Worker

## Pubblicazione
Per installarla come app su iPhone, pubblicare l'intera cartella su un hosting HTTPS (ad esempio GitHub Pages). Non basta aprire `index.html` direttamente dall'app File: il Service Worker e l'installazione PWA richiedono un contesto sicuro.

## Dati
I dati vengono salvati nel localStorage del browser. Usare periodicamente "Esporta JSON" per avere un backup.
