# Toelichtingen

**Kleur**

Mede dankzij de groene achtergrond kleur is alle tekst slecht leesbaar vanwege slecht contrast, daarnaast is het lettertype ook ontzettend klein wat het contrast reeds verslechterd.

**Semantische HTML**

Bij gebruik van de schermlezer wordt alle content buiten de <article> (paginatitel, navigatiebalk, gerelateerd, zoekbak, reacties en kopieer rechten) volledig overgeslagen, dit is erg problematisch voor slechtzienden die graag meer over de website willen weten dan beren.
In de <article> zelf worden de afbeeldingen niet beschreven, en wordt de tabel onduidelijk toegelicht.

Veel van deze problemen kunnen opgelost worden met juist gebruik van HTML5 elementen semantiek.

**Overwegingen**
Voor het vervolg kunnen de volgende overwegingen nog eventueel gemaakt worden om maximale Accessibility te bereiken:

- Bij een <href> element noemen dat het over een link gaat voor schermlezers.

- Na het invullen van de naam de standaard "submit" functie van [enter/return] blokkeren in JavaScript met "preventDefault();"
