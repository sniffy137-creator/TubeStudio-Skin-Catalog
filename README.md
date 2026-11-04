# Tube Studio Skin Catalog

20 original CC0 static clock systems for HN-H401 / IPSTubeA_III. Five original 2.5 systems plus 15 new 2.6 systems. Every ZIP contains 14 glyphs, RGB565 135×240 and PNG previews; editable SVG geometry is in source/. No external fonts, borrowed images, vendor art, characters, APKs, private photos or private keys.

- catalog.json and catalog-v1.json: signed schema 1 for existing 2.5/2.5.1 clients; 20 entries.
- catalog-v2.json: same 20 packs plus signed descriptions, category and tags for 2.6.
- Both use the same pinned ECDSA P-256/SHA-256 key and domain UTF8("TubeSkinCatalog/v1") || byte00 || exact canonical UTF8 payload. No signature bypass or trust-key rotation.
- Existing pack hashes/versions and immutable URLs are unchanged. Preview strips are palette PNGs; full RGB565 images remain in each SHA-256-verified pack.
- Limits remain 256KiB payload, 400000-byte envelope, 50 entries and 32768-byte preview.
- All effects are static raster artwork. Glow, gears, pointers, pixels and glass do not imply animation or new firmware features. Installation checks model, supported layout, existing names and actual free filesystem bytes before writing; publishing does not install anything on a clock.

## New collection

- **Nixie Laboratory** — Стеклянный баллон, сетка анода, слои катодов и тёплое статическое свечение.
- **Brass Engine** — Латунный картуш, зубчатые колёса и гравированные цифры с засечками.
- **Industrial Gauge** — Круглая шкала заводского прибора, стрелка и крупное контрольное значение.
- **Cyber Grid** — Скошенные многоугольные цифры на узлах пространственной сетки.
- **Neon Tokyo** — Круглые неоновые трубки, двойной контур и геометрия ночной вывески.
- **Bauhaus** — Круги и прямоугольники, асимметричная композиция и первичные цвета.
- **Monochrome OLED** — Большие чистые белые цифры на сплошном чёрном поле.
- **Vintage Radio** — Тканевая решётка, частотная шкала и кремовый индикатор старого приёмника.
- **Space Mission** — Белые модульные знаки, тёмная бортовая панель и служебные индикаторы.
- **Arcade Pixel** — Авторская блочная матрица, ступенчатая рамка и пиксельные игровые фигуры.
- **Military Terminal** — Трафаретная нумерация, оливковая полевая панель и контрольные метки.
- **Art Deco Gold** — Узкие геометрические цифры, золотые веера и ступенчатый орнамент.
- **Liquid Crystal** — Пассивные сегменты LCD, тёмный графит и зеленоватая подложка.
- **Blueprint** — Контур цифры на миллиметровой сетке с размерными линиями.
- **Retro Computer** — Зелёная растровая матрица, текстовые рамки и курсор домашнего компьютера.

CC0-1.0: https://creativecommons.org/publicdomain/zero/1.0/
