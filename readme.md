# Toelichtingen

**Kleur**

Mede dankzij de groene achtergrond kleur is alle tekst slecht leesbaar vanwege slecht contrast, daarnaast is het lettertype ook ontzettend klein wat het contrast reeds verslechterd.

**Semantische HTML**

Bij gebruik van de schermlezer wordt alle content buiten de article element (paginatitel, navigatiebalk, gerelateerd, zoekbak, reacties en kopieer rechten) volledig overgeslagen, dit is erg problematisch voor slechtzienden die graag meer over de website willen weten dan beren.
In de article element zelf worden de afbeeldingen niet beschreven, en wordt de tabel onduidelijk toegelicht.

Veel van deze problemen kunnen opgelost worden met juist gebruik van HTML5 elementen semantiek.

**Overwegingen**

Voor het vervolg kunnen de volgende overwegingen nog eventueel gemaakt worden om maximale Accessibility te bereiken:

- Bij een <href> element om naar een andere pagina the navigeren kan het handig zijn om te noemen dat het over een link gaat, zodat slechtzienden via schermlezers op de hoogte blijven.

- Abbreviations toevoegen bij onbekende of moeilijke termen, zoals Baloo, voor de laaggeletterden m.b.v. de <abbr> tag.

- De taal van het document definieren.

- Afbeeldingen insluiten m.b.v. de figure en figcaption elementen.

- Na het invullen van de naam kan de standaard "submit" functie van [enter/return] het beste worden geblokkeerd in JavaScript met "preventDefault();", zodat er niet per ongeluk een comment vroegtijdig verstuurd word.
