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
