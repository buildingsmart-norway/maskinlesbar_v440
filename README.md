# Maskinlesbar v440 og r762

## Introduksjon

Prosjektet Ferjefri E39 Bjørnafjorden har som mål å utvikle et Open Live Center (BOLC) for å holde oversikt og kontroll på informasjonsmengdene, underveis og etter overlevering, av prosjektet.

Data om broen vil brukes av mange forskjellige aktører, som igjen bruker mange forskjellige verktøy, som igjen behandler mange forskjellige typer av data, som også bruker mange forskjellige formater. For å kunne handlere denne informasjonsmengden effektivt er det kritisk at alle aktører og verktøy bruker samme kodesystem / språk for å angi betydningen av dataene. Dette kodesystemet/ “språket” er allerede angitt i Statens Vegvesens handbøker. For broer er Handbok V440 Bruregistrering og R762 Prosesskode 2 – Standardbeskrivelse for bruer og kaier gitt av prosjektet som de viktigste handbøkene å følge.

Dette prosjektet i Teknisk Rom i buildingSMART Norge skal bistå BLOC til å tilgjengeliggjøre disse kodesystemene digitalt. Prosjektet har følgende leveranser:

1) Maskinlesbar datamodell i semantisk web standard formater (RDF/OWL) som gjengir [V440](handboker/v440) og [R762](handboker/r762), ved bruk av Modelling and Linking Guide fra CEDR Interlink (som nå også standardiseres i CEN 442 WG4 TG3).

2) Tilgjengeliggjøre datamodell av V440 og R762 på nett tilsvarende slik EuroOTL har blitt publisert (teknisk rapport og viewer).

3) Gjennomføre [openLAB : Interoperate] for å støtte programvarer i implementering, samt lage veiledningsmateriale for programvareaktører og Bjørnafjorden for bruk i kravstilling.

## Hvordan delta og være informert
Abeidet fåregår i en prosjektgruppe under Teknisk Rom i buildingSMART Norge, ledet av Leder for Teknisk Rom, Jan-Erik Hoel.

I tillegg deltar Preben Madsen og Bjørnar Markussen fra BLOC, samt Chi Ho Lau og Sigve Pettersen fra buildingSMART Norge.

For mer informasjon om prosjektet, kontakt Leder for Teknisk Rom på [teknisk@buildingsmart.no](teknisk@buildingsmart.no).

Det vil bli gitt informasjon om prosjektet i de regelmessige møtene i Teknisk Rom. Prosjektet vil også bruke denne repositorien underveis i utviklingen, så man kan holde seg informert med å følge med på aktiviteten her.

## Hvordan bidra
Det er flere måter å bidra på.

1) Enten kan man bidra gjennom å klone dette repositoriet og foreslå innspill gjennom pull requests. Ellers kan man lage en kommentar gjennom et issue.

2) Man kan også bidra gjennom innspill i møtene i Teknisk Rom.

Eksperter vil arbeide i excel og et skript vil bli utviklet til å lage RDF/TTL fil(er). Dette vil bli publisert her. RDF/TTL filene kan vises og endres i f.eks. [Protegé som er nedlastbar her](https://protege.stanford.edu/). Dette er et gratisk programvare for å jobbe med ontologier.

## EUROTL Modelling and Linking

Prosjektet EUROTL utviklet en kjerneontologi, og et sett linker til andre ontologier, for å kunne integrere og skape interoperabilitet mellom de europeiske objekttype katalogene (slik som norske NVDB) mulig. Les mer om [EUROTL ontologiene her](https://www.roadotl.eu/static/eurotl-ontologies/index.html).

Dette prosjektet vil søke å linke til og gjenbruke innhold, samt følge veiledningene som ble utarbeidet i dette prosjektet.

## How to use the code in the Repository

This project uses python 3 and jupyter notebooks. For accessing bSDD the request library is used, and for working with the ontology the RDFLib library is used.

The [environment.yml](environment.yml). Install anaconda on your machine [create environment from this file](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file). After you can activate it by source activate {name of environment} and start the notebooks by ```jupyter notebook``` in the repo root.

## How to contribute
Please add an issue with ideas or comments, and feel free to add pull requests with alterations.
