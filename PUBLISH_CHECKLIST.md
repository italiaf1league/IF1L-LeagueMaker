# GitHub Publish Checklist

## Repository

- Nome consigliato: `if1l-leaguemaker`
- Descrizione consigliata: `Desktop app Electron per creare e gestire campionati F1 offline`
- Visibilita consigliata: `Public` se vuoi condivisione semplice, `Private` se sei ancora in beta chiusa

## File da caricare nella release

- `dist/IF1L LeagueMaker-1.0.0-arm64.dmg`
- `dist/IF1L LeagueMaker-1.0.0.dmg`
- `dist/IF1L LeagueMaker Setup 1.0.0.exe`

## Release

- Tag: `v1.0.0`
- Titolo: `IF1L LeagueMaker v1.0.0`
- Testo: usa `RELEASE_NOTES_v1.0.0.md`

## Flusso rapido

1. Crea o apri il repository su GitHub.
2. Carica il progetto.
3. Vai in `Releases`.
4. Premi `Draft a new release`.
5. Inserisci tag `v1.0.0`.
6. Inserisci titolo `IF1L LeagueMaker v1.0.0`.
7. Incolla il contenuto di `RELEASE_NOTES_v1.0.0.md`.
8. Trascina dentro i 3 file della cartella `dist`.
9. Pubblica la release.

## Link da condividere dopo la pubblicazione

- Pagina ultima release:
  `https://github.com/TUO-USERNAME/if1l-leaguemaker/releases/latest`

## Nota pratica

- Senza firma digitale, alcuni utenti vedranno un avviso iniziale su macOS o Windows. E normale per questa fase.
