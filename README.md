# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-30T19:25:34+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Nucleo minimo | File | Dimensione |
|---|---|---|---|---|
| **Safe Dashboard (nucleo)** (`nucleo`) | 3.2.0 | 0.0.0 | `nucleo-3.2.0.zip` | 370 KB |
| **Predisposizioni di posa** (`predisposizioni_posa`) | 1.3.1 | 3.0.0 | `predisposizioni_posa-1.3.1.zip` | 21 KB |
| **Promemoria** (`promemoria`) | 1.0.0 | 3.0.0 | `promemoria-1.0.0.zip` | 3 KB |
| **Gestione RMA** (`rma`) | 3.0.0 | 3.1.0 | `rma-3.0.0.zip` | 61 KB |
| **Gestione RMA** (`rma`) | 3.1.0 | 3.2.0 | `rma-3.1.0.zip` | 61 KB |

## Dettagli

### Safe Dashboard (nucleo) 3.2.0

Aggiornamento del nucleo.

- Identificativo: `nucleo` (nucleo)
- Richiede il nucleo 0.0.0 o successivo
- File: `nucleo-3.2.0.zip`
- SHA-256: `3e0e22f2cf888d97e023a235558b5ccab0704d43a36bb7e33049bf56fe9da628`

### Predisposizioni di posa 1.3.1

Preparazione e invio delle email di predisposizioni di posa con registro degli invii.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `predisposizioni_posa-1.3.1.zip`
- SHA-256: `a031262648d2188a7a3dfa4f2843afd0a39974ff3adf66718a2bdf9056df16b8`

### Promemoria 1.0.0

Modulo di esempio: un elenco di promemoria condiviso. Serve da modello per i nuovi moduli.

- Identificativo: `promemoria` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `promemoria-1.0.0.zip`
- SHA-256: `894212a0d48d76737466bab419d4bbd4e858ee34f90323ca7434883622e18301`

### Gestione RMA 3.0.0

Prima versione come modulo: dati, interfaccia e API separati dal nucleo. Richiede il nucleo 3.1.0; i RMA gia presenti passano nel modulo al primo caricamento.

- Identificativo: `rma` (modulo)
- Richiede il nucleo 3.1.0 o successivo
- File: `rma-3.0.0.zip`
- SHA-256: `9fcd55f3ceb78241c326df197cb44d9cb65f13141d2f536fab17d231699a8999`

### Gestione RMA 3.1.0

Statistiche nel sottomenu di Resi. Richiede il nucleo 3.2.0.

- Identificativo: `rma` (modulo)
- Richiede il nucleo 3.2.0 o successivo
- File: `rma-3.1.0.zip`
- SHA-256: `62a68c38a9f63f7a62cf5d820a363e4850655ec8b58df3ff3c3d144d64506350`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
