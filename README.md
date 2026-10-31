# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-31T17:28:59+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Core minimo | File | Dimensione |
|---|---|---|---|---|
| **Safe Dashboard (core)** (`nucleo`) | 3.16.0 | 0.0.0 | `nucleo-3.16.0.zip` | 444 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 2.5.1 | 3.15.0 | `predisposizioni_posa-2.5.1.zip` | 31 KB |
| **Promemoria** (`promemoria`) | 2.3.1 | 3.15.0 | `promemoria-2.3.1.zip` | 12 KB |
| **Gestione RMA** (`rma`) | 3.8.0 | 3.16.0 | `rma-3.8.0.zip` | 72 KB |
| **Tools e documentazione** (`tools_documentazione`) | 1.2.0 | 3.5.0 | `tools_documentazione-1.2.0.zip` | 20 KB |

## Dettagli

### Safe Dashboard (core) 3.16.0

Aggiornamento del core.

- Identificativo: `nucleo` (nucleo)
- Richiede il core 0.0.0 o successivo
- File: `nucleo-3.16.0.zip`
- SHA-256: `e648c1c0fe7d19dc0b8334fb1c568d8a09ab835761fc18433f5c36848ae9a723`

### Predisposizioni di posa 2.5.1

Aspetto della email modificabile da Impostazioni > Modelli email (i testi restano in questo modulo). Richiede il core 3.15.0.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il core 3.15.0 o successivo
- File: `predisposizioni_posa-2.5.1.zip`
- SHA-256: `e4f302d60f4fe215e2ed1364df5630085fcbbb9e532e9165ec385e99b81e7024`

### Promemoria 2.3.1

L'e-mail dei promemoria è un modello modificabile da Impostazioni > Modelli email. Richiede il core 3.15.0.

- Identificativo: `promemoria` (modulo)
- Richiede il core 3.15.0 o successivo
- File: `promemoria-2.3.1.zip`
- SHA-256: `0c82fae61c98f2a86b045827e1be47b6fb98f998fd6507b52f894c29c7aa5761`

### Gestione RMA 3.8.0

Le email (scheda, stato al cliente, statistiche) sono modelli modificabili da Impostazioni > Modelli email. La verifica dell'integrità dello storico è in Impostazioni > Sicurezza. Richiede il core 3.16.0.

- Identificativo: `rma` (modulo)
- Richiede il core 3.16.0 o successivo
- File: `rma-3.8.0.zip`
- SHA-256: `796b98a584147ff7865ca019c36504ff33eab13a53f947b6325028458c20e08d`

### Tools e documentazione 1.2.0

Due sezioni nel menu (Tools e Documentazione). Nuova guida a pagine in Markdown con indice ad albero, ricerca e pagine di esempio; immagine facoltativa per ogni tool; i documenti caricati restano disponibili.

- Identificativo: `tools_documentazione` (modulo)
- Richiede il core 3.5.0 o successivo
- File: `tools_documentazione-1.2.0.zip`
- SHA-256: `51481ff9a7a1981801cf12e8838155ef19880f43d1598a1c6114766f258441ae`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
