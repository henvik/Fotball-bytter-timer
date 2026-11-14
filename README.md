# Bytte-timer fotball

Enkel mobil-webapp som holder tiden på innbytter for et fotballag.

- Stor kampklokke med start/pause/nullstill
- Nedtelling til neste bytte og hvem som skal **inn** og **ut**
- Fullskjermvarsel med lyd og vibrasjon når det er tid for bytte (og et kort pip 10 sek før)
- Oversikt over hvem som er på banen og på benken, med spilletid
- Bytteplan for hele kampen og planlagt spilletid per spiller
- Skjermen holdes våken mens klokka går; klokka fortsetter riktig selv om siden lastes på nytt
- Virker uten nett etter første besøk, og kan legges til på hjemskjermen

## Innstillinger (⚙︎)

- Navn på eget lag og motstander
- Spillere og rekkefølge (de første i lista starter, samme rekkefølge brukes for alle bytter)
- Antall spillere på banen og hvor mange som byttes om gangen
- Kamplengde og tid mellom bytter (i minutter, f.eks. `9` og `1,5`)

Byttene går på rundgang: den som har vært lengst på banen går ut, den som har sittet lengst på benken går inn.

## Kjøre

Bare åpne `index.html`, eller legg ut mappa med GitHub Pages / en hvilken som helst statisk webserver.
