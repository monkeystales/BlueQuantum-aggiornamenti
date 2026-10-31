# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-31T01:07:52+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Core minimo | File | Dimensione |
|---|---|---|---|---|
| **Safe Dashboard (core)** (`nucleo`) | 3.11.1 | 0.0.0 | `nucleo-3.11.1.zip` | 413 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 2.4.0 | 3.11.0 | `predisposizioni_posa-2.4.0.zip` | 30 KB |
| **Promemoria** (`promemoria`) | 2.2.0 | 3.11.0 | `promemoria-2.2.0.zip` | 10 KB |
| **Gestione RMA** (`rma`) | 3.6.0 | 3.11.0 | `rma-3.6.0.zip` | 68 KB |

## Dettagli

### Safe Dashboard (core) 3.11.1

Aggiornamento del core.

- Identificativo: `nucleo` (nucleo)
- Richiede il core 0.0.0 o successivo
- File: `nucleo-3.11.1.zip`
- SHA-256: `f9d2145d786bce5f207caf85de65199266606c0b1dcdf9ba20d36bce67528490`

### Predisposizioni di posa 2.4.0

Codice articolo e uso (presenze/accessi) nella email; destinatari allineati. Richiede il core 3.11.0.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il core 3.11.0 o successivo
- File: `predisposizioni_posa-2.4.0.zip`
- SHA-256: `97eb13c425f295051ee5644db9288eb34345e84485771fbc540b3ddd39b5d7b0`

### Promemoria 2.2.0

E-mail dei promemoria con il nuovo modello grafico. Richiede il core 3.11.0.

- Identificativo: `promemoria` (modulo)
- Richiede il core 3.11.0 o successivo
- File: `promemoria-2.2.0.zip`
- SHA-256: `f11f26bdcbf8fcc23fccb9fabed88a8168cfb774b6a3181ab0846aedb86363fc`

### Gestione RMA 3.6.0

Nuovi modelli grafici delle email (scheda, stato al cliente, statistiche). Richiede il core 3.11.0.

- Identificativo: `rma` (modulo)
- Richiede il core 3.11.0 o successivo
- File: `rma-3.6.0.zip`
- SHA-256: `8bedba5570fbf120e7dae1bd794006f702d4d1a9bf860861c9999f38dbe90e3d`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
