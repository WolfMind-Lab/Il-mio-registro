# Il Mio Registro — V13.0 Consolidata

Versione consolidata del progetto, costruita a partire dalla V12.4 e dalle migliorie V13 presenti nell’archivio storico.

## Stabilizzazione
- storage ufficiale V13 con migrazione controllata da `imr_v12` e versioni precedenti;
- cache PWA dedicata `il-mio-registro-v13`;
- un solo controller V13 per abbonamenti, tabaccheria, pianificazione e contesto pagamento;
- niente duplicazione automatica dei blocchi di pagamento già presenti nei form legacy;
- saldo dei crediti aggiornato anche quando un acquisto viene pagato direttamente con un credito;
- ricorrenze coerenti: le entrate una tantum non generano nuove occorrenze; gli abbonamenti rispettano il flag di rinnovo automatico;
- intervallo personalizzato degli abbonamenti espresso in giorni;
- sincronizzazione dei piani rateali/SFL dopo aggiornamento delle singole mensilità;
- interfaccia abbonamenti e ricerca ADM ottimizzata per mobile;
- database ADM integrato: 4.337 referenze.

## Dati e privacy
L’app è una PWA locale basata su `localStorage` e non utilizza un backend. Non vengono richiesti numero completo della carta, CVV, PIN o password.


## V13 — funzionalità consolidate aggiuntive
- duplicazione sicura delle registrazioni;
- indicazione dei giorni di anticipo/ritardo rispetto alla scadenza;
- azzeramento completo protetto con doppia conferma;
- tipo di contratto registrabile nelle voci pertinenti;
- distinzione tra acquisto in negozio fisico, online e marketplace;
- filtro ADM della tabaccheria correlato al prodotto selezionato (sigarette, sigari, sigaretti, trinciati, tabacchi da inalazione);
- blocco della selezione di un prodotto ADM incompatibile con la categoria scelta;
- modifica tabaccheria mantenendo lo stesso filtro di compatibilità.
