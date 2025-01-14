# Opdracht 3: Accordion met Checkbox-hack

## Omschrijving

Bouw een “accordion” waarbij elk onderdeel open- en dichtgeklapt kan worden op klik, zonder JavaScript. Je kunt de radio-button variant gebruiken als je maar één sectie tegelijk open wilt hebben, maar in dit voorbeeld gebruiken we checkboxes, zodat meerdere secties open kunnen staan.

## Vereisten

1. Verberg de checkboxes, gebruik `<label>` voor de klikbare titel.
2. De content is standaard niet zichtbaar (`max-height: 0; overflow: hidden;`).
3. Wanneer de checkbox actief is (`:checked`), geef je de content genoeg ruimte (`max-height` ruim boven de benodigde hoogte).
4. Maak de overgang vloeiend met een `transition`.

## Tips

- Stel `position: relative;` in op de titel als je een pijltje wilt laten draaien via `::after`.
- Experimenteer met styling, marges en padding.
- Gebruik `:focus` of `:hover` voor extra accent.
