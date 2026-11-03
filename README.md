# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-11-03T13:03:11+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Core minimo | File | Dimensione |
|---|---|---|---|---|
| **Assistenza** (`assistenza`) | 1.8.0 | 3.21.0 | `assistenza-1.8.0.zip` | 56 KB |
| **Safe Dashboard (core)** (`nucleo`) | 3.25.0 | 0.0.0 | `nucleo-3.25.0.zip` | 464 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 2.7.1 | 3.15.0 | `predisposizioni_posa-2.7.1.zip` | 37 KB |
| **Promemoria** (`promemoria`) | 2.5.1 | 3.15.0 | `promemoria-2.5.1.zip` | 13 KB |
| **Gestione RMA** (`rma`) | 3.10.0 | 3.19.0 | `rma-3.10.0.zip` | 73 KB |
| **Tools e documentazione** (`tools_documentazione`) | 1.2.0 | 3.5.0 | `tools_documentazione-1.2.0.zip` | 20 KB |

## Dettagli

### Assistenza 1.8.0

Legge la casella configurata in Impostazioni > Server di posta > Posta in arrivo (IMAP, solo lettura).

- Identificativo: `assistenza` (modulo)
- Richiede il core 3.21.0 o successivo
- File: `assistenza-1.8.0.zip`
- SHA-256: `2320a40c82f9ed3cb5d8c42353e6dbcbfb2d1e92ad172187b2e7019fc38dfffe`

### Safe Dashboard (core) 3.25.0

Aggiornamento del core.

- Identificativo: `nucleo` (nucleo)
- Richiede il core 0.0.0 o successivo
- File: `nucleo-3.25.0.zip`
- SHA-256: `c34a9679ffb5ed77b376e54c0354aa2801e93dd0b9f1ee97730d94e91661cc98`

### Predisposizioni di posa 2.7.1

Aspetto della email modificabile da Impostazioni > Modelli email (i testi restano in questo modulo). Richiede il core 3.15.0.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il core 3.15.0 o successivo
- File: `predisposizioni_posa-2.7.1.zip`
- SHA-256: `6dd1b808b5d42eb91ed0797a206b2fc86176db2ca63ab1d286bc7b483b064e85`

### Promemoria 2.5.1

L'e-mail dei promemoria è un modello modificabile da Impostazioni > Modelli email. Richiede il core 3.15.0.

- Identificativo: `promemoria` (modulo)
- Richiede il core 3.15.0 o successivo
- File: `promemoria-2.5.1.zip`
- SHA-256: `fd0a2d12fadce709d45c12a6d21ffa0c5ca0d10705dcf5104a90557419730328`

### Gestione RMA 3.10.0

Le email (scheda, stato al cliente, statistiche) sono modelli modificabili da Impostazioni > Modelli email. La verifica dell'integrità dello storico è in Impostazioni > Sicurezza. Richiede il core 3.16.0.

- Identificativo: `rma` (modulo)
- Richiede il core 3.19.0 o successivo
- File: `rma-3.10.0.zip`
- SHA-256: `7b7265eb4a6fde778bb92494e96815f32dfd119ee6d8f3b60518ad520ddbac8e`

### Tools e documentazione 1.2.0

Due sezioni nel menu (Tools e Documentazione). Nuova guida a pagine in Markdown con indice ad albero, ricerca e pagine di esempio; immagine facoltativa per ogni tool; i documenti caricati restano disponibili.

- Identificativo: `tools_documentazione` (modulo)
- Richiede il core 3.5.0 o successivo
- File: `tools_documentazione-1.2.0.zip`
- SHA-256: `6d90c2b230815675cafa23b9e04f2ff1a968b82c82e712b172994e5ae04a33df`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
