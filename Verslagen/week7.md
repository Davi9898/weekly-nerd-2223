# Hidde de Vries
Vers uit Dusseldorf
Modal Mischief & Dialog Dilemmas
Gewerkt voor w3c overheid en mozilla
Hij probeerde de webstandaarden toegankelijker te maken voor de gebruiker en de developers.

In het begin was content linear. Content kan tegenwoordig overlappen. Hoe kun je de nieuwste webstandaarden gebruiken? dialog element en pop up attribuut.

Terminology
Modal vs Non-modal Modal = enige ding waarmee je iets kan(interacten)
The rest van de pagina is inert.( je kan het niet scrollen je kan het niet selecteren)
chat widgets(niet modal)
Modal element is een drastisch measure, de gebruiker kan niks doen. Gebruik wijzelijk.
light vs explicit dismiss
z-index Top-layer(top-layer ligt helemaal bovenop alles)
full screen content 
dialogs
popovers
backdrop(sommige elementen hebben een backdrop. Dit kun je stylen met ::backdrop)
keyboard focus traps(always temporary)

Patterns
Dialog ( Component that contains an action or some task to perform)(continue? if you wnat to open a new file)
Modal dialogs en non-modal(modal= outside content = inert[Toplayer]esc-> yes(browser doet dit))(non-modal kun je overal bij niet top-layer en soms weg bij esc).
<dialog></dialog> Wordt top-layer inertness close on esc.
div role="dialog"> Just semantics geen gedrag zoals toplayer
Popover aan de andere kant van dialog. Popover is een attribuut. Als je dit toevoegt krijgt het element meerder behaviours. 
popovers inert no: toplayer yes closes on esc yes - non modial dialogs no top layer no maybe(als je het toevoegt esc sluiting)
anchor positioning om popovers te positioneren.
disclosure widgets 
<details>
    <summary>
    
Open UI(Groep die maakt html elementen die devs graag willen bouwen en stylen)