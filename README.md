# Artemis Khronos

Dette prosjektet kombinerer historie og kunstig intelligens ved å skape kunstverk basert på historiske hendelser. Systemet henter informasjon om en hendelse på dagens dato og transformerer denne til en visuell fremstilling ved hjelp av AI.

### **Viktige tekniske funksjoner:**
* **API-Integrasjon:** Bruker REST API-forespørsler (HTTP) for å kommunisere med både ChatGPT-4 (for tekstgenerering) og DALL-E 3 (for bildegenerering).
* **Sikkerhet:** Implementerer Microsoft.Extension.Configuration.UserSecrets for trygg oppbevaring av API-nøkler lokalt, slik at sensitive data ikke lastes opp til versjonskontroll.
* **Logikk for Prompting:** En egen klasse administrerer dynamisk generering av "prompts" ved å kombinere historiske data med tilfeldige variabler som kunststil, kontinent og epoke.
* **Datahåndtering:** Systemet lagrer generert tekst og bildereferanser i JSON-format ved hjelp av Newtonsoft.Json, og bildene lagres organisert i lokale undermapper.
* **Arkitektur:** Applikasjonen er bygget etter en modulær struktur med egne klasser for filhåndtering, API-kommunikasjon og prompt-generering.


### **Potensielle forretningsmessige anvendelser:** 

Utover kunstgenerering viser prosjektet hvordan teknologien kan benyttes til:

* **Markedsføring og E-handel:** Automatisert generering av produktbeskrivelser og visuelt innhold.
* **Utdanningssektoren:** Verktøy for interaktiv språk- og historielæring.
* **Monitorering og analyse:** Overvåking av API-bruk og dataflyt i sanntid.
