# Oppgaver

## Innhold:

### [Oppsett av konfigurasjonsvariabler og hemmeligheter i Github actions](#konfigurasjonsvariabler-og-hemmeligheter-i-github-actions)

### [Oppgave 1 til 3](#oppgave-en-til-tre)

### Oppgave 5/ 4 2.0
### [A. Flyt](#flyt)


### Konfigurasjonsvariabler og hemmeligheter i Github actions

#### Dette repositoriet inneholder config variabler og hemmeligheter. Du vil trenge og definere noen av disse dersom du ønsker å kjøre github actions og se at det fungerer slik det skal. For å finne frem til stedet der disse kan defineres, følg denne teksten og bilde eksemplene.
#### I repositoriet du har forket, gå til menyen for repositoriets instillinger (`settings`)

![Screenshot 2023-11-20 152250](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/e10e1cc5-c76e-41f0-847a-3fcb8a1ae49e)

#### Videre, se til menyen til venstre og klikk på `secrets and variables`. Dette skal gi deg en undermeny, der du kan trykke `actions`.

![Screenshot 2023-11-20 152523](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/2a3b55cd-b40b-4cfc-97fe-2bc2ad02c005)

#### Du skal nå ha nådd en side, med titlene `Secrets` og `Variables` oppe til venstre, og en grønn knapp for å lage ny hemmeligheter. Dersom du trykker på `Variables` tittelen vil den grønne knappen la deg lage variabler. Den oppdaterer seg med tittelen som er valgt.

![Screenshot 2023-11-20 152850](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/bc51714b-ae82-420e-b944-b31e1e9deaad)

#### Konfigurasjonsvariabler og hemmeligheter har to felter, et for navn og et for verdi. Navnet brukes for å refferere til konfigurasjonsvariabler og hemmeligheter, og verdien er inneholde i konfigurasjonsvariabel eller hemmelighet.

![Screenshot 2023-11-20 153122](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/assets/56083504/c6c79b21-bf7a-4f48-b510-056f231e5be0)



### Oppgave en til tre

#### Kjells python oppsett
##### husk og gå til `hello_world` mappen for å teste med docker
##### Github actions status: [![kjell&cope](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/actions/workflows/kjell&cope.yml/badge.svg)](https://github.com/Personal-Hoyskolen-Kristiania-Work/DevOps-Exam/actions/workflows/kjell&cope.yml)

#### Oppgave 2 og 3 Java, spring boot docker og terraform
##### Github actions status: 

### Oppgave 5/ 4 2.0

#### Flyt:

##### Continuous Integration (`CI`) er en praktisert måte for utviklere å samle nye endringer i kode ofte og bygge og kjøre et første set med tester for å kjapt se om koden fungerer.
##### Continues Integration hjelper utviklere med å finne feil og konflikter tidlig i utviklingsprosessen. Dette kan spare utviklere mye tid, fordi feil og konflikter kan bli rettet før de blir større problemer som tar lengere tid og rette.
##### En måte utviklere ofte utvikler med `CI` og andre DevOps konsepter er i det som kalles trunk based development. I trunk based development har man en hovedgren, og mange mindre grener for nye implementasjoner i koden. Implementasjonene skal holdes små, og går ofte ganske kjapt. Noen av fordelene med dette er mindre mengde kode som slås sammen av gangen, som leder til mindre feil, effektiv utvikling, med oftere oppdateringer av en branch som alle deler.