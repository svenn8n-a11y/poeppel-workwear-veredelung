# Veredelungsseite — Kleidungs-Icons (Flat-Set)

Erstellt: 2026-07-06 · für Sektion „Wo Ihr Logo sitzen kann" (Workwear-Veredelung/Logoservice)

## Ergebnis der Bildrecherche (wichtig)

Auftrag war ursprünglich, **lizenzsichere Produktfotos** (Unsplash/Pexels/Pixabay) je
Kleidungsstück zu beschaffen. Recherche-Befund über alle drei Plattformen:

- **Freigestellte Foto-Freisteller** von Kleidung: fast nur Personen, die Kleidung tragen;
  kaum navy, **keine** brauchbaren Freisteller für Polo/Softshell/Bundhose/Latzhose.
- **Rückansichten** als Freisteller: praktisch nicht existent (nur Personen von hinten).
- **Flat-Illustrationen** (Pixabay): für T-Shirt/Polo etwas vorhanden, aber **uneinheitlicher
  Stil**, türkis/weiß statt navy — und für Softshell/Bundhose/**Latzhose 0 brauchbare Treffer**.

**Entscheidung Sven:** Statt eines uneinheitlichen/unvollständigen Stock-Mixes ein
**eigenes, konsistentes Flat-Icon-Set** in Workwear-CI. Nur Vorderansichten.

## Dateien

| Datei | Motiv | Format |
|---|---|---|
| `tshirt.svg` / `.png` | T-Shirt | SVG (Quelle) + PNG 800×800 |
| `polo.svg` / `.png` | Poloshirt (Kragen + Knopfleiste) | SVG + PNG 800×800 |
| `jacke.svg` / `.png` | Arbeits-/Softshelljacke (Reißverschluss, Stehkragen) | SVG + PNG 800×800 |
| `cap.svg` / `.png` | Cap (Schirmmütze) | SVG + PNG 800×800 |
| `hose.svg` / `.png` | Arbeits-/Bundhose (Taschen, Seitennähte) | SVG + PNG 800×800 |
| `latzhose.svg` / `.png` | Latzhose (Latz, Träger, Schnallen) | SVG + PNG 800×800 |
| `_vorschau.jpg` | Übersicht aller 6 Kacheln | — |

## Quelle & Lizenz

- **Quelle:** Eigenerstellung (Claude Code), von Grund auf als SVG gezeichnet — **keine
  Stock-/Hersteller-/Katalogbilder verwendet.**
- **Lizenz:** frei nutzbar (Pöppel-eigenes Asset). Keine Fremdrechte, keine Marken/Logos,
  keine abgebildeten Personen (DSGVO unkritisch).
- **CI:** Navy `#16273f` (Fläche) + `#1e3150`/`#24395c` (Tiefe), Orange `#ff6600`
  (Naht-/Detail-Akzente). Transparenter Hintergrund → Kachel-BG frei wählbar
  (Pastellblau `#DCECF5`, Navy oder Weiß).

## Hinweise für den Einbau (Claude Max)

- **SVG bevorzugt** einbinden (scharf in jeder Größe, exakte CI-Farben, ~1,5 KB je Datei).
  PNGs (800×800, transparent) als Fallback beigelegt.
- Icons sind auf transparentem Grund zentriert mit Rand — passen direkt in quadratische Kacheln.
- Farben sind im SVG als Hex hinterlegt und leicht anpassbar (z. B. Akzent auf Pöppel-Rot,
  falls doch gewünscht).
