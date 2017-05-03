Moved to Crowdin: https://crowdin.com/project/joomla-cms/nb#
=============

OUTDATED - Norwegian Core Translations
=============

This is the Norwegian Core language project, this project has Norwegian as it's natural language - please contact us if you need English information about it.

### Det Norske oversettelsesprosjektet for Joomla-kjernen

Dette er prosjektsiden for norske oversettelser for Joomla-kjernen, som tilbyr Norsk bokmål (nb-NO), Norsk Nynorsk (nn-NO) og Nordsamisk (se-XX).

Oversettere som vil bidra med oversettelse av kjernen må ha vist at de behersker norsk språk og rettskriving bra, ved å ha oversatt utvidelser, hjelpesider eller andre tekster. Man må også ha vist at man ønsker å dele sitt arbeid med andre, ved å utgi dette offentlig gjennom nettsidene til Foreningen Joomla! i Norge, Joomla.org, utviklers nettside eller pakke (utvikler av utvidelsen).

**MERK!** Ingen blir opptatt som oversetter eller gitt tilgang kun ved å trykke **Join team**, vi må vite hvem du er og om du kan levere først.

Vær også oppmerksom på at noen filer kan inneholde feil og mangler, men dette er noe vi jobber med så langt tiden tillater oss. Men vi er også avhengige av tilbakemeldinger og gjerne oppdaterte filer, for å kunne gjøre de så bra som mulig. Vi har med dagens frivillige ressurser ingen mulighet til å gå igjennom og oppdatere alle filer fort nok alene.


### Installasjon av språkpakker

Språkpakkene kan fra og med Joomla 2.5.7 lastes ned og installeres direkte fra administrasjonen i Joomlasiden din, her vil du da også bli varslet om, og kunne installere oppdateringer av språkpakkene når dette utgis.

Fra og med Joomla 3.0 kan man også installere språkpakker direkte under siste trinn i installasjonen av systemet.


### Pakking og utgivelse

#### Viktig - XML-filer og versjoner

Alle nødvendige xml-filer ligger i mappene, husk bare på å oppdatere utgivelsesdato og versjon før utgivelse og pakking utføres.

Dersom det i noen utgivelse legges til eller fjernes språkfiler må man også huske på å legge til eller fjerne disse i install.xml i samme mappe.

Versjon angis som **2.5.0.1**, hvor **2.5.0** er Joomla-versjon, og **.1** er pakkeversjon (starter på 1).

**MERK!** Pakkeversjon er påkrevd. Brukes i tilfelle man har behov for ny utgivelse av språkpakke, før ny versjon av Joomla utgis.


#### Pakking komplett språkpakke

Språkpakke kan i praksis pakkes og installeres direkte fra GitHub ved å velge **Download ZIP** når som helst.

For de offisielle utgivelsene skal man dog bruke **GitHub Releases**:
https://help.github.com/articles/creating-releases/

Etter å ha klargjort en **GitHub Release** laster man ned en **Source code**-pakke, som man så pakker ut lokalt. Deretter pakker man på nytt, slik at ny pakke kun inneholder mappene **admin_nb-NO** og **site_nb-NO** pluss filene **pkg_nb-NO.xml** og **LICENSE.txt**

Pakken navngis som **nb-NO_joomla_lang_full_2.5.0v1.zip**, hvor **2.5.0** er Joomla-versjon, og **v1** er pakkeversjon.

**MERK!** Pakkenavn kan ikke avvike fra standard, ettersom dette brukes av skripter på sentral oppdateringsserver.


#### Pakking komplett norsk Joomla! 2.5+

Komplett engelsk pakke av Joomla lastes ned og pakkes ut lokalt.

Kopier over de norske filene:

pkg_nb-NO.xml                   -> Kopieres over til mappen **administrator/manifests/packages**
admin_nb-NO                     -> Innholdet kopieres over til **administrator/language/nb-NO** (mappen nb-NO opprettes).
~~images                          -> Hele mappen kopieres direkte over, "overskriver" eksisterende.~~
installation                    -> Hele mappen kopieres direkte over, "overskriver" eksisterende.
site_nb-NO                      -> Innholdet kopieres over til **/language/nb-NO** (mappen nb-NO opprettes).

Alt pakkes på nytt og utgis med filnavn **nb-NO_Joomla_2.5.x-Stable-Full-Distro.zip** (x erstattes med riktig del-versjonsnummer, evt. Stable med RC f.eks om aktuelt).


### TODO - Huskeliste
* Det finnes en miks av visning og utforming i bl.a. **admin/com_content** som det bør ryddes opp i, samt dårlig formulerte beskrivelser. Hele filen bør samtidig sjekkes mot original.
* ~~**Paginering** bør endres. Er jo enkelt og greit **Sidenavigering**.~~
* ~~**Hurtiglager** burde nesten endres til mer folkelige og forståelige **Mellomlager**.~~
  ~~- **Innholdet mellomlagres** vs. **Innholdet hurtiglagres** ...?!~~
* Sjekk navn og beskrivelser på moduler og programtillegg, er noe ukonsekvent.
* ~~På **Rediger menypunkt** bør feltbeskrivelsen **Merk** endres til **Merknad** eller annet. Samme gjelder på moduler hvor samme felt og funksjon bruker **Kommentar** som beskrivelse.~~
* ~~Sjekk hvorfor det er oversatt til **Avanserte valg** på menypunktbehandling.~~
* Sjekk og rydd opp i miks av **Skriv inn**, **Angi** og **Fyll inn**. Personlig foretrekker jeg **Fyll inn** ettersom man kan fylle feltene på flere måter (skrive, klip og lim, kopier og lim).


