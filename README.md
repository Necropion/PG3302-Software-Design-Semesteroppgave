# PG3302 Software Design Semesteroppgave

### Karakter: B

Eksamensoppgaven handlet om å lage en applikasjon i et team fra bunn. Målet var å bruke god tid på å planlegge hvordan strukturen til koden skulle se ut og implementere alle relevante teknologier.

### Merkeverdige teknologier med applikasjonen:
- Model View Controller kode struktur.
- Kodebasen følger Objekt Orientert Programmering og SOLID prinsipper.
- Prosjektet bruktet SQLite som Lokalt Database
- Interaktiv og Intuitivt bruker meny for å utføre relevante funksjoner
- En algoritme som jobber for å anbefalle deg spill som DU er interresert i

### Hurtigstartguide

Det er mulig at før du får kjørt programmet i deres IDE, så må du kjøre kommandoen 'dotnet restore' for å laste ned dependencies for programmet. Dette må gjøres i prosjektets root mappe.

Dette prosjektet inneholder et executable fil som kan kjøres uten en IDE om det er behov for det.

<p>For å komme i gang med applikasjonen etter at den er kjørt eller kompilert, skal navigasjonsmenyen dukke opp og gi deg 5 valg å velge mellom, der du bruker tastetrykk for å navigere opp/ned i menyen og trykker enter for å velge et alternativ.</p> <p>Inne i Bla gjennom-menyen kan du navigere gjennom spillene i det eksisterende biblioteket, hver side viser opptil 10 spill, og du blar gjennom ved å trykke på neste og forrige side-alternativer. Ved å velge et spill vil du få opp informasjon om spillet, og du får valget om å fjerne eller legge til spillet i interesselisten, eller gå tilbake.</p> <p>Inne i interesselisten vil du få en visning av de spillene som er lagt til, disse kan også velges og inspiseres. Du vil også ha to nye menyalternativer: “Legg til spill i interesselisten” og “se etter anbefalinger”.</p> <p>Hvis du velger navigasjonsvalget “Legg til spill i interesselisten”, vil du bli navigert til en undermeny/liste som viser kun spill som ikke er i interesselisten din. Den vil også ha en dynamisk teller som viser hvor mange spill som er igjen.</p> <p>Ved å gå tilbake kommer du tilbake til interesselisten. Det siste alternativet i denne menyen, “se etter anbefalinger”, vil navigere deg til anbefalingssiden. Denne siden vil bare vise anbefalinger hvis du har spill i interesselisten din, og den gir deg topp 5 spill som matcher interessene dine. Denne siden kan også nås via hovedmenyen, gjennom det tredje alternativet, “anbefalinger”.</p> <p>Uansett hvilken meny du er i, ved å velge et spill og trykke enter, vil du få opp en meny som lar deg enten legge til eller fjerne det valgte spillet, avhengig av om spillet allerede er i interesselisten din.</p> <p>Det fjerde alternativet er “Tilbakestill”, dette er mer en utviklerfunksjonalitet som vi ønsket å beholde i tilfelle brukeren ønsker å tilbakestille interesselisten sin. Det siste alternativet er å avslutte programmet.</p>
