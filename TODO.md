# Gjenstående arbeid: datafiler

Alle filene under er identifisert fra bokteksten (kapittel 8–22, ekskl. løsningsforslag), men
ingen av dem er lagt inn i repoet ennå. Dette tas i en senere runde.

## Kapittel 15 – Visualisering og datahåndtering
- periodesystemet.csv, dec.txt, bands.txt — øvingsfiler, Test deg selv 8.4
- pingviner.txt — eksempel i brødtekst
- grunnstoffer.csv — Test deg selv 8.6
- run1.csv – run5.csv — Test deg selv 8.7 (absorbansmålinger)
- oksygenkonsentrasjoner.csv — Oppgave 8.13
- tinn.txt — isotopoppgave
- titrering.txt — Oppgave 8.18K (NaOH/eddiksyre)
- ioniseringsenergi.txt — Oppgave 8.19K
- blindern_yr_1938_2023.csv — Oppgave 8.26G (kilde: Norsk klimaservicesenter)

## Kapittel 16 – Statistikk
- smitte_virus.csv — logistisk modell
- vin.csv — Oppgave 9.9K
- penguins.txt — Oppgave 9.15B
- fiskedata.csv — Oppgave 9.16B (data delvis i oppgaveteksten)
- kornfordeling.csv — Oppgave 9.17G (data delvis i oppgaveteksten)
- nedbor_regioner.csv — Oppgave 9.18G (data delvis i oppgaveteksten)

## Kapittel 19 – Derivasjon og integrasjon
- titrering_eddiksyre_NaOH.txt — avsnitt 12.2
- heistur.csv (foreslått navn, boka gir ikke filnavn) — Test deg selv 12.4 (data delvis i teksten)
- titrering_glykolsyre.csv (foreslått navn) — Oppgave 12.11K
- aksel_tid.csv — Oppgave 12.17 (data delvis i teksten)
- infiltrasjon.csv — Oppgave 12.18G (data delvis i teksten)
- temp_dybde.csv — Oppgave 12.19 (data delvis i teksten)
- sediment_elv.csv — Oppgave 12.20G (data delvis i teksten)

## Kapittel 21 – Kontinuerlige modeller
- planeter_data.dat — planetbanesimulering
- salt_mass.csv — salttap-oppgave
- ice_core_CO2.csv — Oppgave 14.26G (kilde: NOAA, kan trolig hentes direkte)
- co2_monthly.csv — Oppgave 14.26G (kilde: NOAA, kan trolig hentes direkte)

## Kapittel 22 – Maskinlæring
- iris.csv — klassisk datasett
- vin.csv — Oppgave 15.6K (trolig samme fil som i kapittel 16)

## Ting som må avklares
1. **Navnekollisjon**: boka bruker `titrering.txt` for to ulike systemer — NaOH/eddiksyre
   (kapittel 15) og glykolsyre/NaOH (kapittel 19, omtalt som "titrering.txt" i teksten, men her
   foreslått kalt `titrering_glykolsyre.csv` for å unngå kollisjon).
2. **Mulig duplikat**: `pingviner.txt` (kapittel 15) og `penguins.txt` (kapittel 16) kan være
   samme datasett under to ulike navn — bør sjekkes mot bokas fasit/materiale.
3. **Manglende filnavn**: heisturdataene i kapittel 19 (Test deg selv 12.4) har ikke noe oppgitt
   filnavn i boka.
4. Flere oppgaver viser kun de første radene med data i selve oppgaveteksten (fiskedata,
   kornfordeling, nedbør, heistur, aksel_tid, infiltrasjon, temp_dybde, sediment_elv) — disse kan
   trolig rekonstrueres/utvides fra teksten kombinert med den matematiske sammenhengen oppgaven
   beskriver.
