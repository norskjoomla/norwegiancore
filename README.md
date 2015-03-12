Norwegian Core Translations
=============

This is the Norwegian Core language project, this project has Norwegian as it's natural language - please contact us if you need English information about it.

### Det Norske oversettelsesprosjektet for Joomla-kjernen

Dette er prosjektsiden for norske oversettelser for Joomla-kjernen, som tilbyr Norsk bokmål, Norsk Nynorsk og Nordsamisk (?).

Oversettere som vil bidra med oversettelse av kjernen må ha vist at de behersker norsk språk og rettskriving bra, ved å ha oversatt utvidelser, hjelpesider eller andre tekster. Man må også ha vist at man ønsker å dele sitt arbeid med andre, ved å utgi dette offentlig gjennom nettsidene til Foreningen Joomla! i Norge, Joomla.org, utviklers nettside eller pakke (utvikler av utvidelsen).

MERK! Ingen blir opptatt som oversetter eller gitt tilgang kun ved å trykke 'Join team', vi må vite hvem du er og om du kan levere først.

Vær også oppmerksom på at noen filer kan inneholde feil og mangler, men dette er noe vi kontinuerlig jobber med så langt tiden tillater oss. Men vi er også avhengige av tilbakemeldinger og gjerne oppdaterte filer for å gjøre de så bra som mulig, vi har med dagens frivillige ressurser ingen mulighet til å gå igjennom og oppdatere alle filer fort nok alene.

##### Installasjon av språkpakker
Språkpakkene kan fra og med Joomla 2.5.7 lastes ned og installeres direkte fra administrasjonen i Joomlasiden din, her vil du da også bli varslet om, og kunne installere oppdateringer av språkpakkene når dette utgis. Fra og med Joomla 3.0 kan man også installere språkpakker direkte under installasjonen av systemet.

##### Pakking og utgivelse

**ALLTID - VIKTIG**

Alle nødvendige xml-filer ligger i mappene, husk bare på å oppdatere utgivelsesdato og evt. versjon før utsjekking og pakking gjøres. Om det i noen utgivelse legges til nye språkfiler må man huske å legge disse til også i install.xml i samme mappe.


**PAKKING KOMPLETT SPRÅKPAKKE**

Pakking for 1.6 og nyere skiller seg litt fra 1.5 ved at det nå må opprettes to zip-filer først. En for admin og en for brukerdelen, som navngis som følgende:

admin_nb-NO.zip (Pakk mappen admin_nb-NO direkte til zip-fil.)
site_nb-NO.zip (Pakk mappen site_nb-NO direkte til zip-fil.)

Disse to zip-filene pakkes i en ny zip-fil, sammen med pkg_nb-NO.xml:

nb-NO_joomla_lang_full_2.5.0v1.zip

- 2.5.0 = Joomla-versjon
- v1 = Pakkeversjon

**OPPDATERING AV OPPDATERINGSSERVERENS XML-FILERE**

Må skrives ...

**PAKKING KOMPLETT NORSK JOOMLA! 2.5+**

Komplett engelsk pakke av Joomla lastes ned og pakkes ut lokalt.

Kopier over de norske filene:

pkg_nb-NO.xml                   -> Kopieres over til mappen 'administrator/manifests/packages'
admin_nb-NO                     -> Innholdet kopieres over til 'administrator/language/nb-NO' (mappen nb-NO opprettes).
images                          -> Hele mappen kopieres direkte over, "overskriver" eksisterende.
installation                    -> Hele mappen kopieres direkte over, "overskriver" eksisterende.
site_nb-NO                      -> Innholdet kopieres over til '/language/nb-NO' (mappen nb-NO opprettes).

Alt pakkes på nytt og utgis med filnavn nb-NO_Joomla_2.5.x-Stable-Full-Distro.zip (x erstattes med riktig del-versjonsnummer, evt. Stable med RC f.eks om aktuelt).


##### TODO - Huskeliste
* Det finnes en miks av visning og utforming i bl.a. admin/com_content som det bør ryddes opp i, samt dårlig formulerte beskrivelser. Hele filen bør samtidig sjekkes mot original.
* 'Paginering' bør endres. Er jo enkelt og greit 'Sidenavigering'.
* 'Hurtiglager' burde nesten endres til mer folkelige og forståelige 'Mellomlager'.
  - 'Innholdet mellomlagres' vs. 'Innholdet hurtiglagres' ...?!
* Sjekk navn og beskrivelser på moduler og programtillegg, er noe ukonsekvent.
* På 'Rediger menypunkt' bør feltbeskrivelsen 'Merk' endres til 'Merknad' eller annet. Samme gjelder på moduler hvor samme felt og funksjon bruker 'Kommentar' som beskrivelse.
* Sjekk hvorfor det er oversatt til 'Avanserte valg' på menypunktbehandling.
* Sjekk og rydd opp i miks av 'Skriv inn', 'Angi' og 'Fyll inn'. Personlig foretrekker jeg 'Fyll inn' ettersom man kan fylle feltene på flere måter (skrive, klip og lim, kopier og lim).

