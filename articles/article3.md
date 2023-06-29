# Ontdekking van Modal Mischief & Dialog Dilemmas

Dit is het derde artikel in een serie van vier, waarin ik dieper inga op thema's waarover we tijdens onze minor gastcolleges hebben gehad. Deze keer richt ik mijn schijnwerpers op de gastlezing van Hidde de Vries. Hidde is een toegangkelijkheidsexpert die gewerkt heeft voor w3c en mozilla. Hij probeert de webstandaarden toegankelijker te maken voor gebruikers en developers.

Volgens Hidde was in het begin van het web was content voornamelijk lineair, waarbij informatie op een gestructureerde manier werd gepresenteerd. Tegenwoordig is dit niet meer het geval. Content kan nu overlappen, wat nieuwe uitdagingen en mogelijkheden biedt. Het gebruik van de nieuwste webstandaarden zoals het 'dialog' element en 'pop up' attributen, zijn hierbij cruciaal.

## Modal vs Non-Modal

De terminologie "Modal" en "Non-modal" kan verwarrend zijn. Modal houdt in dat het het enige element is waarmee je kunt interacten, terwijl de rest van de pagina inert wordt, dat wil zeggen niet te scrollen of te selecteren. Het is een maatregel die de gebruiker beperkt in zijn acties, dus het moet slim worden gebruikt. Daarentegen zijn chat-widgets een voorbeeld van non-modale elementen.

In het webdesign komt het modal-element met verschillende aspecten zoals light vs explicit dismiss, z-index top-layer die boven alles ligt, fullscreen content dialogs, popovers, en backdrops die gestyled kunnen worden met de ::backdrop selector. Het beheersen van deze technieken helpt bij het creëren van effectieve gebruikersinteracties.

## Dialog & Popover

Dialog is een component dat een actie of taak bevat die uitgevoerd moet worden. Modal dialogs zijn top-layer en maken de buitenste content inert, terwijl non-modal dialogs dat niet doen. Popover, aan de andere kant van de dialoog, is een attribuut dat een element meerdere gedragingen geeft wanneer het wordt toegevoegd.

Organisaties zoals Open UI werken aan het creëren van HTML-elementen die ontwikkelaars graag willen bouwen en stylen, wat helpt om de implementatie van deze interactieve elementen te vergemakkelijken.

## Open UI
Hidde de Vries is actief bij het initiatief Open UI. Open UI is een initiatief dat wordt gedreven door een gemeenschap van ontwerpers, ontwikkelaars en bedrijven met het doel om universele standaarden te creëren voor User Interface (UI) componenten. Het is een open source project dat de nadruk legt op samenwerking, inclusiviteit en toegankelijkheid.

Het belangrijkste doel van Open UI is om de basis te leggen voor de ontwikkeling van toekomstige UI-componenten. Dit doen ze door onderzoek te doen naar gemeenschappelijke UI-patronen en -componenten, en deze informatie vervolgens te documenteren en te delen met de gemeenschap. Deze componenten kunnen variëren van basisitems zoals knoppen en invoervelden tot complexere componenten zoals datumpickers en modale dialoogvensters.

Open UI focust zicht op drie uitdagingen:
1. Interoperabiliteit: Compabiliteit tussen UI-frameworks en -bibliotheken vergroten.
2. Efficiëntie: Het creëren van een gedeelde basis UI-componenten zodat deze makkelijk consistent gebruikt kunnen worden.
3. Toegankelijkheid: Streven ernaar om de toegankelijkheidsstandaarden te bevorderen door best practices in specificaties op te nemen.

## Webstandaarden

Het begrijpen en effectief toepassen van webstandaarden is dus niet alleen essentieel voor het creëren van webapplicaties, maar draagt ook bij aan een beter, inclusiever en toegankelijker web voor iedereen. 


### Resources
* https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog?retiredLocale=nl
* https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/popover
* https://www.nngroup.com/articles/modal-nonmodal-dialog/#:~:text=Nonmodal%20dialogs%20are%20less%20offensive,they%20require%20too%20complex%20interactions.
* https://open-ui.org/