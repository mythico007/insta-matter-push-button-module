# insta-matter-switch-tap-sequences
Blueprint for Home Assistant to automate the INSTA GmbH Matter switch.

This blueprint is for the <strong>INSTA Matter Push Button Module</strong> (https://www.insta.de/matter) that is also used by JUNG Group (https://www.jung-group.com/de-DE/Produkte/Loesungen/Matter-Taster/), SMATTEX (https://smattex.de/collections/schalter), Gira for their products.

It creates n automation to:
- Perform predefined actions when a button is tapped (1,2,3 times) or 
- held and released (the initial action and delay after each repeat-cycle can be set for every button individually)

Switch Layout:
|  1  |  3  |
|-----|-----|
|  2  |  4  |


