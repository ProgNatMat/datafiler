# Status på datafiler

Alle 34 identifiserte filreferanser (kapittel 1–15) har en fil i
`data/kapittel-XX/`. Kilder:

- **Ekte data**:
  periodesystemet.csv, dec.txt, bands.txt, pingviner.txt (identisk datasett),
  tinn.txt, titrering.txt, ioniseringsenergi.txt, antall-meldte-covid-19.txt, run1–5.csv
  (enzymkinetikk S40/S60/S120/S225/S900), smitte_virus.csv, vin.csv, iris.csv,
  titrering_eddiksyre_NaOH.txt, heistur.csv, planeter_data.dat (ekte astronomiske verdier for de åtte planetene).
- **Syntetisk, generert med realistiske verdier**: grunnstoffer.csv (ekte periodesystemdata, filtrert), oksygenkonsentrasjoner.csv, temperatur.txt, blindern_yr_1938_2023.csv, fiskedata.csv, kornfordeling.csv, nedbor_regioner.csv, aksel_tid.csv, infiltrasjon.csv, temp_dybde.csv, sediment_elv.csv, salt_mass.csv, ice_core_CO2.csv, co2_monthly.csv.

## Bør kvalitetssjekkes / vurderes erstattet med ekte data

1. **blindern_yr_1938_2023.csv** — syntetisk. Ekte data finnes hos
   [seklima.met.no](https://seklima.met.no) (stasjon Blindern) og bør hentes derfra hvis mulig.
2. **ice_core_CO2.csv** og **co2_monthly.csv** — syntetiske tilnærminger til kjente trender (Vostok-iskjernen / Mauna Loa). Fra NOAA. Kan hente ekte data:
   - https://www.ncei.noaa.gov/access/paleo-search/study/6091 (Vostok)
   - https://gml.noaa.gov/ccgg/trends/data.html (Mauna Loa)
3. **titrering_glykolsyre.csv** — dette er en generisk titrerkurve, ikke spesifikt glykolsyre.
