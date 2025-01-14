# Opdracht 2: Sterrenbeoordeling (Star Rating)

## Omschrijving

Maak een 5-sterrenbeoordeling waarbij de geselecteerde ster en alle sterren links ervan “oplichten”. Er komt geen JavaScript aan te pas: je gebruikt radio-buttons en labels.

## Vereisten

1. Verberg de radio-buttons, zodat alleen de sterren (★) zichtbaar zijn.
2. Bij hover laat je het aantal sterren tot die “hovered” ster oplichten.
3. Als de gebruiker klikt (selecteert), blijven die sterren opgevuld.

## Tips

- Je kunt `display: none;` of `visibility: hidden;` voor de radio-button gebruiken.
- Gebruik combinaties van `:hover ~ label`, `:checked ~ label`.
- De volgorde van de inputs in HTML kan handig zijn voor de styling (vaak “omgekeerd”).

## Extra Uitdaging

- Laat bij hover ook zien wat de beoordeling in cijfers is, bijvoorbeeld “4/5”.
- Voeg een reset-knopje toe om de keuze ongedaan te maken.
