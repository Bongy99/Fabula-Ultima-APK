# Fabula Ultima – Scheda & Clock

App Android (Capacitor) con scheda personaggio e clock di Fabula Ultima.

## Come ottenere l'APK
1. Crea un repository su GitHub e carica **tutto il contenuto** di questa cartella
   (compresa la cartella nascosta `.github`).
2. Vai nella scheda **Actions**. Il workflow "Build APK" parte da solo a ogni push
   (oppure avvialo con "Run workflow").
3. A build finita (3-6 minuti) apri l'esecuzione e scarica l'artefatto
   **fabula-ultima-apk** in fondo alla pagina: è uno zip con `app-debug.apk`.
4. Invia l'APK agli amici. Su Android devono consentire
   "Installa app da origini sconosciute" per il browser o il gestore file usato.

## Modificare l'app
Tutta l'app è in `www/index.html`. Modificalo, fai commit e l'APK si rigenera.

I dati sono salvati sul dispositivo di ciascun giocatore.

## WebApp per iPhone / iPad (GitHub Pages)
1. Nel repository: **Settings → Pages → Source → GitHub Actions**
   (con un account gratuito il repository deve essere **pubblico**).
2. Al prossimo push (o da Actions → "Deploy WebApp" → Run workflow) l'app viene
   pubblicata su `https://TUO-UTENTE.github.io/NOME-REPOSITORY/`.
3. Gli amici aprono il link **con Safari**, toccano **Condividi → Aggiungi alla schermata Home**:
   l'app si apre a schermo intero e funziona anche offline.

Nota: i dati sono salvati nel dispositivo, e l'app installata sulla Home ha un archivio
separato da quello di Safari. Conviene usare sempre e solo l'icona installata.
