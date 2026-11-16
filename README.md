# ROTTA Secure — Travel Dashboard

Dashboard statica e offline per pianificare viaggi. Codice pubblico, **dati utente locali e cifrati**.

## Pubblicazione GitHub Pages

1. Copiare nella radice del repository i file di questo pacchetto (non caricare il file ZIP).
2. In **Settings > Pages**, selezionare **Deploy from a branch**, branch `main`, cartella `/(root)`.
3. Attivare **Enforce HTTPS** quando disponibile.
4. Verificare il sito dal browser prima di creare viaggi reali.

## Sicurezza e privacy

- Non pubblicare backup JSON, file ICS, passphrase, screenshot di prenotazioni, biglietti o dati personali.
- I dati di ogni installazione sono salvati nel browser su **quell'origine e dispositivo**; non si sincronizzano.
- L'archivio cifrato si sblocca sul dispositivo con la passphrase scelta. Conservare backup cifrati altrove.
- Chi controlla il codice della pagina web pubblicata può distribuire aggiornamenti malevoli: proteggere l'account GitHub e verificare le modifiche prima della pubblicazione.
- Evitare di memorizzare password, documenti d'identità, numeri di carte e codici prenotazione sensibili nelle note.
- L'esportazione calendario ICS e il copia-prompt AI possono esporre dati in chiaro se condivisi.
- La verifica del codice non rappresenta un penetration test indipendente.

## Attenzione ai repository pubblici

Il codice e i file pubblicati con GitHub Pages sono accessibili pubblicamente. **Non caricare mai i dati personali nella repository**. Il file `.gitignore` è solo un promemoria di sicurezza per Git: non garantisce che un upload manuale venga bloccato.
