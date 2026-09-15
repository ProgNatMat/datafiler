# Datafiler til Programmering for naturvitenskap og matematikk

Nettside med datafiler (`.csv`, `.txt` m.m.) til boka *Programmering for naturvitenskap og
matematikk* av Andreas Haraldsrud og Joakim Sundnes.

Siden er en [Jupyter Book](https://jupyterbook.org) som bygges automatisk av GitHub Actions
(`.github/workflows/main.yml`, samme mønster som `bifrost`/`programmering-i-kjemi`) og publiseres
til `gh-pages`-branchen ved hver push til `main`.

**Førstegangsoppsett:** etter at Action har kjørt én gang (og opprettet `gh-pages`-branchen), gå
til **Settings → Pages → Source: Deploy from branch → `gh-pages` → `/ (root)`** for å aktivere
siden på `https://andreasdh.github.io/programmering-for-naturvitenskap-og-matematikk/`.

## Struktur

- `intro.md` – forside
- `kapittel-XX.md` – én side per kapittel, med tabell over filer, hva de brukes til, og status
- `_toc.yml` / `_config.yml` – Jupyter Book-oppsett
- `data/kapittel-XX/` – selve datafilene, lenket til fra kapittelsidene

## Status

Kapittel 15, 16, 19, 21 og 22 har datafiler (kapittel 8–14, 17, 18 og 20 har ingen). Alle filene
er lagt inn — de fleste er ekte datasett gjenbrukt fra forfatterens andre bøker/kurs
(`programmering-i-kjemi`, `realprog`), noen er syntetiske datasett generert med realistiske
verdier der ingen ekte fil fantes. Se `TODO.md` for detaljer, kilder og noen punkter som bør
kvalitetssjekkes.
