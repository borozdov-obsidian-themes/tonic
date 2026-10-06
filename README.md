# Borozdov Tonic

A theme from the Borozdov collection. Two faces — light **Cream**, a soda-fountain menu on
warm paper, and dark **Bottle**, the same menu seen through green glass. Forest-teal
headlines in a fat display serif, pill buttons and a shelf of pastel flavors.

![Borozdov Tonic in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tonic/main/screenshots/light.png)

![Borozdov Tonic in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tonic/main/screenshots/dark.png)

## Principles

- **Retro apothecary.** Cream paper, white cards, a sage side panel and one authoritative
  forest teal for headlines, fills and the selected file.
- **Headlines shout, text whispers.** Tonic Serif Black at 900 for the title and the first
  three heading levels; the platform's own sans for everything else.
- **A shelf of flavors.** Callouts are pastel washes of their type's colour — banana,
  watermelon, apple, grape, cola — with no frame and soft 16px corners.
- **Pills and cards.** Buttons, fields, tags and checkboxes are round; cards, code and
  tables get 16px corners.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Round task checkboxes and toggles in forest teal; wine-red caret
- Tags as sage pills with a forest label; the selected file gets the same tint
- Code on a white card; tables as menu cards with a sage header band
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Trellis**. Install Borozdov Trellis under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Tonic** under Style Settings → Borozdov Trellis → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/tonic/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Tonic/`, then choose Borozdov Tonic under
Settings → Appearance → Themes.

## Font

Tonic Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Playfair
Display Black (© 2010–2012 Claus Eggers Sørensen), renamed because a modified copy may not
use the original's Reserved Font Name. One weight, headlines only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Крем» — меню содовой на тёплой
бумаге, и тёмный «Бутылка» — то же меню сквозь зелёное стекло. Лесные заголовки жирным
ретро-шрифтом с засечками (Tonic Serif), кнопки-пилюли и полка пастельных вкусов в колаутах.
В каталоге тема живёт вариантом Borozdov Trellis: установите Borozdov Trellis и плагин Style Settings, затем выберите Tonic в Style Settings → Borozdov Trellis → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
