# Oppgaver

## Innhold:

### [Oppsett av konfigurasjonsvariabler og hemmeligheter i Github actions](#konfigurasjonsvariabler-og-hemmeligheter-i-github-actions)

### Opggave 1 Kjells python kode
#### [Kjells python oppsett](#kjells-python-oppsett)

### Konfigurasjonsvariabler og hemmeligheter i Github actions

#### Github actions setter automatisk opp mye av softwaren brukt i oppgavene fra denne eksamnen. Enkelte deler av det github action brukes på krever et høyere nivå med sikkerhet enn det hardkoding kan gi, slik at nøkler som gir tilgang til resurser ikke blir tilgjengelig for folk som ikke burde ha tilgang til de ressursene, men som kan se et prosjekt. Det er også navn/ verdier som kan måtte være unike for å kunne tas i bruk med software gjennom f.eks. AWS, og disse bør derfor ikke være hardkodet inn i prosjektet, men heller kunne bli hentet inn fra andre steder, som f.eks Github. Github har slike midler tilgjengelige, og jeg har valgt å bruke hemmeligheter og konfigurasjonsvariabler på denne eksamnen for å møte de praktiske kravene av sikkerhet og unike verdier.

#### For å finne frem til hemmeligheter (`Secrets`) og konfigurasjonsvariabler (`Variables`) inne i Github repositoriet (stede der koden og denne .md filen er lagret), må du først til instillinger (`Settings`)

#### Som vist i bilde under, er det teksten der det står `settings` med tanhjulet ved siden av som tar deg til menyen for instillinger i repositoriet. Teksten er helt til høyre i en vannrett meny over repositoriets navn (`DevOps-Exam`).

![Screenshot 2023-11-20 152250](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/e10e1cc5-c76e-41f0-847a-3fcb8a1ae49e)

#### Når du har kommet inn på siden for instillinger, kan du se til venstre. Det skal være en lodrett meny der med den opplyste teksten `General` i toppen. Under finner du underoverskrifter, og du vil se etter underoverskriften `Security`. Under `Security` skal det være en tittel `Secrets and variables` med en pil ved siden av. Trykk på pilen for å ekspandere en ny meny med tre nye elementer. Blant de tre elementene skal være et element `Actions`, dette elementet tar deg til en side der du kan lage Hemeligheter og variabler for repositoriet som Gtihub actions vil ha tilgang til.

![Screenshot 2023-11-20 152523](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/2a3b55cd-b40b-4cfc-97fe-2bc2ad02c005)

#### Som vist på bildet under vil du se de to titlene `Secrets` og `Variables` til venstre for en knapp med teksten `New repository secret`. Ved og trykke på titlene kan du velge mellom hemmeligheter `Sectrets` og konfigurasjonsvariabler `Variables`. Den grønne knappen vil oppdatere seg med tittelen du velger og vil la deg lage et nytt element som svarer til tittelen.

![Screenshot 2023-11-20 152850](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/bc51714b-ae82-420e-b944-b31e1e9deaad)

#### Konfigurasjonsvariabler og hemmeligheter har to felter, et for navn og et for verdi. Navnet brukes for å refferere til konfigurasjonsvariabler og hemmeligheter, og verdien er inneholde i konfigurasjonsvariabel eller hemmelighet.

![Screenshot 2023-11-20 153122](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/c6c79b21-bf7a-4f48-b510-056f231e5be0)

### Kjells python oppsett
#### Github actions status:
[![kjell&cope](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/actions/workflows/kjell&cope.yml/badge.svg)](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/actions/workflows/kjell&cope.yml)

