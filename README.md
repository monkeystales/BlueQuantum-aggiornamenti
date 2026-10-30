# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-30T19:35:54+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Nucleo minimo | File | Dimensione |
|---|---|---|---|---|
| **Safe Dashboard (nucleo)** (`nucleo`) | 3.2.0 | 0.0.0 | `nucleo-3.2.0.zip` | 370 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 1.3.1 | 3.0.0 | `predisposizioni_posa-1.3.1.zip` | 21 KB |
| **Promemoria** (`promemoria`) | 1.0.0 | 3.0.0 | `promemoria-1.0.0.zip` | 3 KB |
| **Gestione RMA** (`rma`) | 3.1.0 | 3.2.0 | `rma-3.1.0.zip` | 61 KB |

## Dettagli

### Safe Dashboard (nucleo) 3.2.0

Aggiornamento del nucleo.

- Identificativo: `nucleo` (nucleo)
- Richiede il nucleo 0.0.0 o successivo
- File: `nucleo-3.2.0.zip`
- SHA-256: `5b108d1fcdab311a3897792ef0334d10141a50f0a6b4f6d0ae8b097f61a9bd45`

### Predisposizioni di posa 1.3.1

Preparazione e invio delle email di predisposizioni di posa con registro degli invii.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `predisposizioni_posa-1.3.1.zip`
- SHA-256: `589e60b8a776c0b191e24dea1d233c9fcf00de026fea7b01d93730543e60af46`

### Promemoria 1.0.0

Modulo di esempio: un elenco di promemoria condiviso. Serve da modello per i nuovi moduli.

- Identificativo: `promemoria` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `promemoria-1.0.0.zip`
- SHA-256: `bbf53c91768f8b05fd7757aca0f1d3cfffd005ddfd12b102fb5ee99258f514f8`

### Gestione RMA 3.1.0

Statistiche nel sottomenu di Resi. Richiede il nucleo 3.2.0.

- Identificativo: `rma` (modulo)
- Richiede il nucleo 3.2.0 o successivo
- File: `rma-3.1.0.zip`
- SHA-256: `c98b2a1ef3c924515716dbe89c7112585a1ff4f2f6920b6cc9a7981189678c57`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
