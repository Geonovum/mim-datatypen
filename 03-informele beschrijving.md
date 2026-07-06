# Informele beschrijving

Informatiemodellen bevatten voor het specificeren van waardetypen van attributen onder andere referenties naar zogenaamde primitieve datatypen. Voorbeelden hiervan zijn: 'CharacterString', 'Integer', 'Date', 'GM_Point', 'Boolean'.

Een primitief datatype wordt primitief genoemd omdat het atomair is dat wil zeggen dat het binnen de context van een informatiemodel niet verder opgesplitst kan worden in kleinere datatypes. Deze primitieve datatypen zijn buiten een informatiemodel gespecificeerd. Meestal in internationale standaarden. Implementaties in een digitale omgeving en implementatie formaten maken dan gebruik van deze internationaal geldende specificaties. ISO/IEC 11404 Information technology - General-Purpose-Datatypes (GPD) beschrijft een primitief datatype als een datatype waarvan de waarderuimte is gespecificeerd door een axioma of door een enumeratie.

Meestal zijn primitieve datatypen enkelvoudig, het kan echter voorkomen dat een primitief datatype een structuur heeft en dus tevens een complex datatype is.

Primitieve datatype worden meestal alleen gebruikt voor het specificeren van waardetypen.

Voor Geonovum willen we afpraken maken over het gebruik van primitieve datatypen, welke het zijn, en wat hun definitie is. We doen dit in de vorm van een handreiking omdat we dit relateren aan internationale standaarden. Deze handreikingen plaatsen die datatypen in de context van de informatiemodellering van Geonovum.

Er wordt een opdeling gemaakt op basis van een aantal onderdelen van het raamwerk van Geostandaarden: de MIM standaard, het ISO 19107 geometrie model en een derde groep 'overig':

> OPMERKING:
> Onderstaande links zijn nu nog naar werkversies
>

- MIM - Metamodel voor Informatiemodellering (deze handreiking);

- [Geometrische primitieven conform het geometriemodel van ISO 19107](https://geonovum.github.io/iso-19107-datatypen/);

- [Geonovum datatypen](https://geonovum.github.io/geonovum-datatypen/). Overige primitieven die niet in bovenstaande groepen vallen.

In deze handreikingen worden de primitieve datatypen in een MIM 1.2 \[\[MIM12]] conform conceptueel informatiemodel gespecificeerd. Tevens wordt er een [[NL-SBB-20241010]] conform begrippenmodel gepubliceerd.


## MIM - Metamodel voor Informatiemodellering.

MIM - Metamodel voor informatiemodellering \[\[MIM12]] beschrijft een metamodel waar informatiemodellen mee gemaakt kunnen worden. Het beschrijft de metaklassen, metastructuur en metagegevens als grondslag voor een informatiemodel. Doel hiervan is standaardiseren van de methode van informatiemodelleren waarmee afstemming tussen informatiemodellen, vergelijkbaarheid in publicatie en gebruik van gemeenschappelijke tooling mogelijk wordt. MIM faciliteert hiermee het ontstaan van een stelsel van samenhangende informatiemodellen.

MIM benoemt een [aantal extern gedefinieerde primitieve datatypen](https://docs.geostandaarden.nl/mim/mim/#datatype-n) om binnen MIM conforme modellen te gebruiken. Deze datatypen zijn allen afkonstig uit andere internationale standaarden. Bij de definities van de datatypen wordt gebruik gemaakt en verwezen naar die standaarden. Voor meer detail wordt ook naar die standaarden verwezen.