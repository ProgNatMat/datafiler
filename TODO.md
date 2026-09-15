# Status på datafiler

Alle 34 identifiserte filreferanser (kapittel 8–22, ekskl. løsningsforslag) har nå en fil i
`data/kapittel-XX/`. Kilder:

- **Ekte data, gjenbrukt** fra `andreasdh/programmering-i-kjemi` og `andreasdh/realprog`:
  periodesystemet.csv, dec.txt, bands.txt, pingviner.txt/penguins.txt (identisk datasett),
  tinn.txt, titrering.txt, ioniseringsenergi.txt, antall-meldte-covid-19.txt, run1–5.csv
  (enzymkinetikk S40/S60/S120/S225/S900), smitte_virus.csv, vin.csv, iris.csv,
  titrering_eddiksyre_NaOH.txt, heistur.csv (fra `heistur_kjemi_fysikk.txt`, verdiene stemmer
  eksakt med utdraget i boka), planeter_data.dat (ekte astronomiske verdier for de åtte planetene).
- **Gjenbrukt/repurposert**: titrering_glykolsyre.csv (generisk titrerkurve fra
  `titreringsdata.txt` — boka har ikke noe eget datasett for glykolsyre-forsøket).
- **Syntetisk, generert med realistiske verdier** (matcher tallene vist i bokutdraget der de
  finnes, resten generert): grunnstoffer.csv (ekte periodesystemdata, filtrert),
  oksygenkonsentrasjoner.csv, temperatur.txt, blindern_yr_1938_2023.csv, fiskedata.csv,
  kornfordeling.csv, nedbor_regioner.csv, aksel_tid.csv, infiltrasjon.csv, temp_dybde.csv,
  sediment_elv.csv, salt_mass.csv, ice_core_CO2.csv, co2_monthly.csv.

## Bør kvalitetssjekkes / vurderes erstattet med ekte data

1. **blindern_yr_1938_2023.csv** — syntetisk. Ekte data finnes hos
   [seklima.met.no](https://seklima.met.no) (stasjon Blindern) og bør hentes derfra hvis mulig.
2. **ice_core_CO2.csv** og **co2_monthly.csv** — syntetiske tilnærminger til kjente trender
   (Vostok-iskjernen / Mauna Loa). Nettverkstilgangen i denne økten tillot ikke direkte henting
   fra NOAA. Ekte data:
   - https://www.ncei.noaa.gov/access/paleo-search/study/6091 (Vostok)
   - https://gml.noaa.gov/ccgg/trends/data.html (Mauna Loa)
3. **titrering_glykolsyre.csv** — dette er en generisk titrerkurve, ikke spesifikt glykolsyre.
   Fungerer fint pedagogisk, men er ikke kjemisk presis for akkurat den syra.
4. Filene merket "Syntetisk" i kapittel 16 og 19 (fiskedata, kornfordeling, nedbør, aksel_tid,
   infiltrasjon, temp_dybde, sediment_elv) er generert til å matche de første radene som vises i
   selve oppgaveteksten i boka, med resten generert etter en realistisk/fysisk plausibel modell.
   De støtter oppgavene fint, men tallene vil ikke nødvendigvis stemme overens med en eventuell
   fasit fra forlaget.

## Avklart fra forrige runde

- `titrering.txt` (kap. 15, NaOH/eddiksyre) og den nye `titrering_glykolsyre.csv` (kap. 19) er nå
  atskilt med egne filnavn for å unngå navnekollisjonen som fantes i boka.
- `pingviner.txt` (kap. 15) og `penguins.txt` (kap. 16) er bekreftet å være samme datasett
  (funnet identisk i `realprog`-repoet), ikke to ulike filer.
- Heisturdataene i kap. 19 er identifisert som `heistur_kjemi_fysikk.txt` fra
  `programmering-i-kjemi` — tallene stemmer eksakt med utdraget i boka.
