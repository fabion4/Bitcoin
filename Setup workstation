# Una Workstation per Bitcoin

## 1. Introduzione
La configurazione di una **workstation Bitcoin** prevede l'utilizzo di un computer dedicato alla gestione sicura delle proprie transazioni e holdings in Bitcoin. L'obiettivo è garantire **sicurezza fisica e crittografica**, ordine e controllo centralizzati su tutte le operazioni relative ai Bitcoin.

### 1.1 Perché usare una Workstation dedicata?
- **Sicurezza**: Protezione contro accessi fisici non autorizzati attraverso la crittografia.
- **Organizzazione**: Gestione ordinata di tutte le informazioni Bitcoin, separate dagli altri dispositivi usati per lavoro o svago.
- **Controllo locale**: Un unico punto di accesso sicuro, come uno "sportello bancario personale", per tutte le operazioni Bitcoin.

## 2. Sicurezza fisica e crittografia
L'obiettivo principale è proteggere la workstation da accessi fisici, come furti o intrusioni domestiche. Anche se il dispositivo venisse rubato, i dati devono rimanere inaccessibili senza la chiave di decifrazione.

### 2.1 Crittografia del File System con LUKS
- Durante l'installazione del sistema operativo (Debian), è fondamentale utilizzare il **file system LUKS**.
- **Passphrase**: Durante il boot del sistema, verrà richiesta una passphrase per decifrare i dati. Senza questa, tutto il contenuto del disco rimane cifrato.

## 3. Hardware e sistema operativo consigliati
### 3.1 Scelta dell'hardware
- **Computer fisso** dedicato alla gestione dei Bitcoin, di potenza media.
- Separato da altri dispositivi usati per attività quotidiane o professionali.

### 3.2 Sistema Operativo: Debian Linux
- **Debian** è consigliato per la sua stabilità e sicurezza.
- Scarica la distribuzione dal sito ufficiale [debian.org](https://www.debian.org).
- Verifica le firme dell'immagine scaricata per garantirne l'integrità.

### 3.3 Installazione di Debian con LUKS
1. Scarica l’immagine di Debian.
2. Verifica le firme e crea una chiavetta USB per l'installazione.
3. Durante l'installazione, abilita la **crittografia LUKS** per il file system.
4. Configura una **passphrase** per la decifratura durante il boot.

## 4. Software essenziali
### 4.1 Software di base
Dopo l’installazione di Debian, aggiungi i seguenti strumenti:
- **Git**: Per gestire il codice.
- **GPG**: Per cifrare messaggi e verificare le firme.
- **Wget**: Per scaricare file da internet.

### 4.2 Strumenti per la gestione dei Bitcoin
- **Electrum**: Per gestire il wallet Bitcoin. Scaricalo da [electrum.org](https://electrum.org).
  - Usa la versione **AppImage** e verifica sempre le firme.
- **Blockstream Green**: Wallet per gestire Bitcoin e Liquid.
  - Disponibile su [blockstream.com](https://blockstream.com).

### 4.3 Importare chiavi GPG
- Dopo l'installazione, **importa la tua chiave privata GPG** per cifrare dati sensibili.
- GPG sarà usato anche per verificare le firme di altri software.

## 5. Dispositivi hardware di sicurezza
### 5.1 Dispositivi consigliati
- **Bitbox 2 (Bitcoin only)**: Per la gestione sicura dei fondi Bitcoin principali.
- **Jade di Blockstream**: Per gestire Bitcoin e Liquid, adatto per importi minori.

### 5.2 Connessione e verifica dei dispositivi
- Collega i dispositivi via USB e assicurati che il sistema li rilevi correttamente.
- Consulta i siti dei produttori per risolvere eventuali problemi di riconoscimento.

## 6. Verifica del sistema e delle transazioni
### 6.1 Test di sicurezza
- **Reboot multipli**: Esegui più riavvii per assicurarti che il sistema funzioni correttamente con la passphrase.
- **Prova di firma**: Firma un messaggio con Electrum e il dispositivo hardware per verificare che tutto funzioni correttamente.

### 6.2 Backup e gestione delle chiavi
- Usa un **password manager** come KeePass per gestire password critiche (es. PIN dei dispositivi hardware e passphrase GPG).
- Conserva le **etichette** di ogni transazione per facilitare la gestione a lungo termine.

## 7. Privacy e connessioni sicure
### 7.1 Utilizzo di Tor e VPN
- Installa e configura **Tor** per navigare sotto rete **Onion** durante l'uso di Bitcoin.
- Configura una VPN sicura, come **Mullvad**, acquistabile tramite la Lightning Network in modalità anonima.

### 7.2 Connessione a un nodo Bitcoin Core
- Se possibile, collega la workstation a un **nodo Bitcoin Core** per verificare le transazioni senza intermediari.
- In alternativa, usa sempre **Tor** per connetterti ai wallet esterni.

## 8. Organizzazione e gestione a lungo termine
### 8.1 Importanza dell'ordine
- Mantenere un **ordine rigoroso** nelle operazioni Bitcoin è essenziale per la sicurezza e la trasparenza a lungo termine.
- Se gestisci i fondi per lungo tempo o desideri che altri membri della famiglia possano accedere ai tuoi fondi, assicurati di organizzare chiaramente le informazioni necessarie.

### 8.2 Accesso sicuro per i familiari
- Prepara un sistema che permetta ai tuoi familiari di accedere ai fondi in caso di emergenza, garantendo chiarezza e accessibilità.

## 9. Conclusione
Configurare una workstation Bitcoin sicura e dedicata è essenziale per proteggere i tuoi fondi e avere il pieno controllo sulle tue transazioni. Usando strumenti come Debian, Electrum, dispositivi hardware sicuri e Tor, è possibile raggiungere un alto livello di sicurezza, privacy e organizzazione.

## 10. Risorse aggiuntive
- [Debian.org](https://www.debian.org)
- [Electrum.org](https://electrum.org)
- [Blockstream.com](https://blockstream.com)
- [KeePass](https://keepass.info)
