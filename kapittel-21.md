# Kapittel 21 — Kontinuerlige modeller

| Fil | Brukes i | Status | Last ned |
|---|---|---|---|
| `planeter_data.dat` | Oppgave – simulering av planetbaner (masse, posisjon, hastighet) | Ekte data | [Last ned](data/kapittel-21/planeter_data.dat) |
| `salt_mass.csv` | Oppgave – salttap via geologiske sedimenter over 700 Ma | Syntetisk | [Last ned](data/kapittel-21/salt_mass.csv) |
| `ice_core_CO2.csv` | Oppgave 14.26G – CO2 fra Vostok-iskjernen, Antarktis (kilde: NOAA) | Syntetisk (tilnærmet) | [Last ned](data/kapittel-21/ice_core_CO2.csv) |
| `co2_monthly.csv` | Oppgave 14.26G – CO2-målinger fra Mauna Loa siden 1958 (kilde: NOAA) | Syntetisk (tilnærmet) | [Last ned](data/kapittel-21/co2_monthly.csv) |

```{note}
`planeter_data.dat` bruker ekte astronomiske verdier (masse og baneradius) for de åtte planetene,
med sirkulær bane beregnet fra $v = 2\pi/\sqrt{a}$ (stemmer med jord-eksempelet i selve teksten).
`ice_core_CO2.csv` og `co2_monthly.csv` er tilnærminger som følger de kjente langsiktige trendene
fra Vostok-iskjernen og Mauna Loa (Keeling-kurven), men er ikke hentet direkte fra NOAA
(nettverkstilgangen i denne økten tillot ikke det). Vurder å erstatte disse med ekte data fra
[NOAA (Vostok)](https://www.ncei.noaa.gov/access/paleo-search/study/6091) og
[NOAA (Mauna Loa)](https://gml.noaa.gov/ccgg/trends/data.html) ved anledning.
```
