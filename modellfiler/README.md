# Vedlagt script klassifiserer Storbruen.ifc med v440

Tar inn Storbruen.ifc og legger til v440 koder. Kodene er valgt ut i samarbeid med Bjørnar Markussen.

Klassifisert fil, Storbruenv440_klassifisert.ifc, finnes under modellfiler. Denne har klassifikasjon lagt til iht. NS8360 for material og klasse iht. v440. NS8360 beskriver altså hvor i IFC filen klassifikasjonen ligger, og hvordan klassifikasjonsreferansene er koblet til produktene.

For hvert [IfcProduct](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x3/TC1/HTML/ifckernel/lexical/ifcproduct.htm) finner man klassifikasjon via ```HasAssociations``` som gir tilbake IfcRelAssociates objecter (både for materialer og klassifikasjoner). Mange objekter har to klassifikasjonsreferanser. Noen viewere viser bare én av klassifikasjonsreferansene. 

Bildet under viser hvordan klassifikasjonen vises i Solibri.

![Storbruen Klassifisert i Solibri](../Pictures/storbruen_klassifisert.png)

Scriptet ligger ved som jupyter notebook. Koden kan også kjøres i egne filer ved å importere requests og [ifcopenshell](http://ifcopenshell.org/).

Lær mer om bruk av ifcopenshell og python på [ifcopenshell academy](http://academy.ifcopenshell.org/)
