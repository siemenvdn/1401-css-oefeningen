# Opdracht 1: Flip Card Animatie

## Omschrijving

Maak een “flip card” die omdraait wanneer je er met de muis overheen gaat (hover) of bij klik (als je dat wilt). De kaart moet een 3D-rotatie maken, zodat de voor- en achterkant elkaars positie innemen.

## Vereisten

1. Gebruik een container met `perspective`.
2. Plaats een voorzijde (front) en achterzijde (back) in een element dat je om zijn Y-as roteert.
3. Bij hover of focus roteert dit element 180 graden (`transform: rotateY(180deg)`).
4. Zorg voor een vloeiende overgang met `transition`.

## Tips

- Gebruik `transform-style: preserve-3d;` in de container zodat front en back in 3D blijven.
- Gebruik `backface-visibility: hidden;` om te voorkomen dat de achterzijde door de voorzijde heen schijnt.
- Experimenteer met `:hover` op de `.flip-card-container` of `.flip-card` zelf.
