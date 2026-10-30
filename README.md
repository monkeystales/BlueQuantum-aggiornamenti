# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-30T20:33:17+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Nucleo minimo | File | Dimensione |
|---|---|---|---|---|
| **Safe Dashboard (nucleo)** (`nucleo`) | 3.4.0 | 0.0.0 | `nucleo-3.4.0.zip` | 381 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 1.4.0 | 3.4.0 | `predisposizioni_posa-1.4.0.zip` | 18 KB |
| **Promemoria** (`promemoria`) | 1.0.0 | 3.0.0 | `promemoria-1.0.0.zip` | 3 KB |
| **Gestione RMA** (`rma`) | 3.1.0 | 3.2.0 | `rma-3.1.0.zip` | 61 KB |

## Dettagli

### Safe Dashboard (nucleo) 3.4.0

Aggiornamento del nucleo.

- Identificativo: `nucleo` (nucleo)
- Richiede il nucleo 0.0.0 o successivo
- File: `nucleo-3.4.0.zip`
- SHA-256: `7a4157014832abbcb0272c69e76252fdd6f0bb2849e83375c99486b4239781ae`

### Predisposizioni di posa 1.4.0

Usa il server di posta del nucleo (Impostazioni > Server di posta). Richiede il nucleo 3.4.0.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il nucleo 3.4.0 o successivo
- File: `predisposizioni_posa-1.4.0.zip`
- SHA-256: `8ccba6d652b10760a4a568504036bb3ecf3f147dbbbe7a926062ec52d67d4d91`

### Promemoria 1.0.0

Modulo di esempio: un elenco di promemoria condiviso. Serve da modello per i nuovi moduli.

- Identificativo: `promemoria` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `promemoria-1.0.0.zip`
- SHA-256: `72966fcb134c640a562e0ba041a4c28db01b700a2d0603d5863b5456f137700d`

### Gestione RMA 3.1.0

Statistiche nel sottomenu di Resi. Richiede il nucleo 3.2.0.

- Identificativo: `rma` (modulo)
- Richiede il nucleo 3.2.0 o successivo
- File: `rma-3.1.0.zip`
- SHA-256: `d6ff3c8ee856bcaebb9963facb3c58ebed484a7cbbf6a6b613116ca0660b0949`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
