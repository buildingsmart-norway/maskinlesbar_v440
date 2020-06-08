# Maskinlesbar v440

**For information about the project in English, please see the Presentations folder and the Wiki page of this repo.**

## Introduksjon

Statens vegvesen prosjektet E39 Bjørnafjorden har som mål å utvikle et Open Live Center (BOLC) for å holde oversikt og kontroll på informasjonsmengdene, underveis og etter overlevering av prosjektet.

![E39 Bjørnafjorden](/Pictures/E39%20-%20Bjoernafjorden%20-%20Bakgrunn.png)

Data om broen vil brukes av mange forskjellige aktører, som igjen bruker mange forskjellige verktøy, som igjen behandler mange forskjellige typer av data, som også bruker mange forskjellige formater. For å kunne håndtere denne informasjonsmengden effektivt er det kritisk at alle aktører og verktøy bruker samme kodesystem / språk for å angi betydningen av dataene. Dette kodesystemet/ “språket” er allerede angitt i Statens Vegvesens handbøker. For broer er Håndbok V440 Bruregistrering og R762 Prosesskode 2 – Standardbeskrivelse for bruer og kaier gitt av prosjektet som de viktigste handbøkene å følge.

Dette prosjektet i Teknisk Rom i buildingSMART Norge skal bistå BOLC til å tilgjengeliggjøre disse kodesystemene digitalt. Prosjektet har følgende leveranser:

1) Maskinlesbar datamodell i semantisk web standard formater (RDF/OWL), som gjengir [V440](https://github.com/buildingsmart-norway/maskinlesbar_v440/blob/master/handboker/v440.pdf), ved bruk av Modelling and Linking Guide fra CEDR Interlink (som nå også standardiseres i CEN 442 WG4 TG3).

2) Tilgjengeliggjøre datamodell av V440 på nett tilsvarende slik EuroOTL har blitt publisert (teknisk rapport og viewer).

3) Gjennomføre [openLAB : Interoperate] for å støtte programvarer i implementering, samt lage veiledningsmateriale for programvareaktører og Bjørnafjorden for bruk i kravstilling.

## Hvordan delta og være informert
Arbeidet foregår i en prosjektgruppe under Teknisk Rom i buildingSMART Norge, ledet av Leder for Teknisk Rom, Jan-Erik Hoel. 

Programvareleverandører og andre utviklere (f.eks. skriptere, plugin utviklere etc.) er også invitert med i **[openLAB : Interoperate]** som er et program hvor det vil bli gitt gratis teknisk support for implementasjon og testing av ontologien, samt anledning til å presentere demonstratorer for marekdet. 

I tillegg deltar Preben Madsen og Bjørnar Markussen fra BOLC, Chi Ho Lau fra buildingSMART Norge, Sigve Pettersen fra [mok-see], og teknisk ekspert Lars Wikström fra Triona. 

For mer informasjon om prosjektet, kontakt Leder for Teknisk Rom på [teknisk@buildingsmart.no](teknisk@buildingsmart.no).

Det vil bli gitt informasjon om prosjektet i de regelmessige møtene i Teknisk Rom. Prosjektet vil også bruke denne repositorien underveis i utviklingen, slik at man kan holde seg informert ved å følge med på aktiviteten her.

Innledende utforskning og modellering finnes i denne [miro tavlen](https://miro.com/app/board/o9J_kwr0pvw=/). 

## Hvordan bidra
Det er flere måter å bidra på.

1) Enten kan man bidra gjennom å klone dette repositoriet og foreslå innspill gjennom pull requests. Ellers kan man lage en kommentar gjennom et issue.

2) Man kan også bidra gjennom innspill i møtene i Teknisk Rom.

Eksperter vil arbeide i Excel og et skript vil bli utviklet til å lage RDF/TTL fil(er). Dette vil bli publisert her. RDF/TTL filene kan vises og endres i f.eks. [Protegé som er nedlastbar her](https://protege.stanford.edu/). Dette er en gratis programvare for å jobbe med ontologier.

## EUROTL Modelling and Linking

Prosjektet EUROTL utviklet en kjerneontologi og et sett linker til andre ontologier, for å kunne integrere og skape interoperabilitet mellom de europeiske objekttype katalogene (slik som norske NVDB) mulig. Les mer om [EUROTL ontologiene her](https://www.roadotl.eu/static/eurotl-ontologies/index.html).

Semantic Modelling and Linking Guide (SMLG) fra EUROTL prosjektet har blitt videreført i CEN 442 WG4 TG3. Dette prosjektet tester og bidrar med innspill til SMLG underveis i arbeidet. 

Dette prosjektet vil søke å linke til og gjenbruke innhold, samt følge veiledningene som ble utarbeidet i dette prosjektet.

## How to contribute
Please add an issue with ideas or comments, and feel free to add pull requests with alterations.

You can fork the repo, make your changes in the forked repo, and create a pull request. 
