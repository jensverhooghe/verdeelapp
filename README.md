# Groepsverdeler

**Versie: 1.0.0**

Een eenvoudige webapp die een lijst met namen eerlijk en willekeurig over groepen verdeelt. Bedoeld voor leerkrachten die snel klasgroepen willen samenstellen — zonder discussie en zonder gedoe.

## Wat het doet

- Namen invoeren, één per regel of gescheiden door komma's
- Verdelen op **aantal groepen** of op **personen per groep**
- Volledig willekeurige verdeling: elke klik schudt opnieuw
- Groepen worden zo gelijk mogelijk in grootte gemaakt
- Klaslijsten opslaan in de browser, zodat je ze niet telkens opnieuw hoeft in te voeren

## Gebruiken

Open de live versie:

**https://jensverhooghe.github.io/verdeelapp/**

Of download `index.html` en open het bestand lokaal in een browser. Er is geen installatie of internetverbinding nodig om de app te laten werken.

## Hoe het werkt

De hele app zit in één HTML-bestand (`index.html`) met ingebouwde HTML, CSS en JavaScript. Er is geen backend, build-stap of externe afhankelijkheid.

Opgeslagen klaslijsten worden lokaal bewaard via de `localStorage` van de browser. Dat betekent dat lijsten per toestel en per browser zijn — ze worden niet automatisch tussen verschillende gebruikers gedeeld.

## Privacy

Ingevoerde namen blijven volledig op je eigen toestel. Er worden geen gegevens verzonden of op een server bewaard.

## Licentie

Vrij te gebruiken en aan te passen voor onderwijsdoeleinden.
