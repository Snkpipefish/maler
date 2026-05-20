# Leif Sebastian – Sprøytemaler & sparkler

Nettside som promoterer tjenester innen sprøytemaling og sparkling/gips i Oslo og omegn.

## Filer

- `index.html` – hele nettsiden (én side)
- `styles.css` – design og layout

## Slik publiserer du gratis på GitHub Pages

1. **Lag GitHub-konto** på <https://github.com> hvis du ikke har en fra før.
2. **Opprett et nytt repository** og kall det `<brukernavn>.github.io` (bytt ut `<brukernavn>` med ditt eget brukernavn). Da blir adressen automatisk `https://<brukernavn>.github.io`.
3. **Last opp filene** `index.html` og `styles.css` i repoet (du kan dra dem inn på GitHubs nettside under "Add file → Upload files").
4. Gå til **Settings → Pages**. Under "Branch", velg `main` og mappe `/ (root)`. Trykk **Save**.
5. Etter et minutt eller to er siden live på `https://<brukernavn>.github.io`.

Hvis du heller vil bruke et eget domene (f.eks. `leifsebastian-maling.no`), kjøp domenet hos f.eks. Domeneshop og pek det mot GitHub Pages under Settings → Pages → Custom domain.

## Slik endrer du tekst eller priser

Alt innhold står i `index.html`. Åpne filen i en teksteditor (f.eks. Notepad, VS Code eller direkte på GitHub), søk opp teksten du vil endre, lagre og last opp på nytt. Prisene ligger i blokker som starter med `<div class="price-table">`.

## Endre kontaktinfo

Telefonnummer og e-post står på tre steder i `index.html`:
- I hero-knappen øverst (`tel:+4740754175`)
- I kontakt-seksjonen nederst (`tel:` og `mailto:`)
- I header på siden

Bytt ut `40754175` og `leifsebastian@gmail.com` med riktig verdi alle steder.
