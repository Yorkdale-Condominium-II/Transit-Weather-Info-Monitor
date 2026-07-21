# Operator logos

The dashboard header shows each transit operator's logo. To display an
operator's **official** logo, drop its file into this folder using the
exact filename below. Until a file is present, the board automatically
shows a plain brand-coloured wordmark instead — so there is never a
broken image on screen.

| Operator      | Filename expected      | Where the board uses it        |
|---------------|------------------------|--------------------------------|
| TTC           | `ttc.svg`              | "Toronto Transit Commission" header |
| GO Transit    | `go.svg`               | "GO Transit" header            |

## Notes

- **Format:** SVG is preferred (stays crisp at any size on the TV). A
  PNG works too — if you only have a PNG, name it `ttc.png` / `go.png`
  and let me know so I can point the page at the `.png` file.
- **Source the official files** from each operator's brand / media
  resources (e.g. Metrolinx/GO media assets, the TTC's brand page).
  Using the operators' own published logo files keeps them accurate
  and correctly rendered.
- **Transparent background** looks best against the dark board; a logo
  on a solid white block will show that block.
- The logo is scaled to the header height (~22 px tall), so a wide
  horizontal lockup reads better than a tall stacked one.

## Adding more operators later

VIA Rail and the intercity coach operators (Megabus, Ontario
Northland, FlixBus) currently use the built-in wordmarks. They can be
switched to official files the same way — ask and I'll wire them to
`via.svg`, `megabus.svg`, `ontario-northland.svg`, and `flixbus.svg`.
