# Safe Dashboard - pacchetti dei moduli

Pacchetti firmati dei moduli di Safe Dashboard. Si installano da **Home > + Aggiungi modulo** (da file) o da **Impostazioni > Moduli e Aggiornamenti** (da internet, con l'indirizzo di questo repository).

Catalogo creato il `2026-10-30T18:50:43+00:00`. Ogni file è firmato: il server rifiuta quelli non firmati con una chiave autorizzata.

| Modulo | Versione | Nucleo minimo | File | Dimensione |
|---|---|---|---|---|
| **Predisposizioni di posa** (`predisposizioni_posa`) | 1.3.1 | 3.0.0 | `predisposizioni_posa-1.3.1.zip` | 21 KB |
| **Promemoria** (`promemoria`) | 1.0.0 | 3.0.0 | `promemoria-1.0.0.zip` | 3 KB |
| **Gestione RMA** (`rma`) | 3.0.0 | 3.1.0 | `rma-3.0.0.zip` | 61 KB |

## Dettagli

### Predisposizioni di posa 1.3.1

Preparazione e invio delle email di predisposizioni di posa con registro degli invii.

- Identificativo: `predisposizioni_posa` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `predisposizioni_posa-1.3.1.zip`
- SHA-256: `24b7ebbade9e279cd1781f81de4b45026d5c53cf28df9ce76cdb69993a3a4e24`

### Promemoria 1.0.0

Modulo di esempio: un elenco di promemoria condiviso. Serve da modello per i nuovi moduli.

- Identificativo: `promemoria` (modulo)
- Richiede il nucleo 3.0.0 o successivo
- File: `promemoria-1.0.0.zip`
- SHA-256: `e534ebdc35d31eaf71d66690229c052b8dfb00440fb7c467ce80a20262323da9`

### Gestione RMA 3.0.0

Prima versione come modulo: dati, interfaccia e API separati dal nucleo. Richiede il nucleo 3.1.0; i RMA gia presenti passano nel modulo al primo caricamento.

- Identificativo: `rma` (modulo)
- Richiede il nucleo 3.1.0 o successivo
- File: `rma-3.0.0.zip`
- SHA-256: `9fcd55f3ceb78241c326df197cb44d9cb65f13141d2f536fab17d231699a8999`

## Come installare

1. **Da file:** scarica il `.zip`, apri Safe Dashboard come amministratore, **Home > + Aggiungi modulo > Da un file**, poi **Riavvia ora**.
2. **Da internet:** in **Impostazioni > Moduli e Aggiornamenti** indica `https://github.com/<proprietario>/<repository>/releases/latest/download/`, premi **Controlla ora** e **Prepara**.

Prima dell'installazione il server esegue un backup completo e, se la nuova versione non parte, ripristina da solo la precedente.

## Per pubblicare

Crea una Release e allega **tutti** i `.zip`, `catalogo.json` e `catalogo.json.sig` di questa cartella (non serve allegare questo README).
