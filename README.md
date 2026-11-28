# Kaiyi Lu

Building **zero-backend, browser-native engineering tools** and **auditable JavaScript geometry & calculation modules**.

Most utility software ships a server it doesn't need. My work focuses on pushing deterministic calculations, vector CAD path generation, photometric & residential code layouts, and batch file/image pipelines directly into the client runtime using vanilla ES modules, WebAssembly/Canvas2D, SVG path math, and streaming browser APIs—with zero server uploads and zero account friction.

- **Engineering Hub & Spec Index:** [https://kaiyilu.github.io/](https://kaiyilu.github.io/)

---

### Open-Source Specifications & Zero-Dependency JS Modules

Small, dependency-free reference libraries and interactive field guides documenting the exact math behind production tools:

- **[building-layout-math](https://github.com/kaiyilu/building-layout-math)** · [Field Guide](https://kaiyilu.github.io/building-layout-math/)  
  IES lumen-method ceiling grids, 2D rotated physical fixture RCP collision math (overhead garage-door track bay caps + ceiling fan strobe radial push with `baseGrid` & `fanShifted` schedules), `1/4"=1'-0"` (`1:48`) & `ISO 1:50` CAD scale viewports, IRC R312.1.3 `< 4"` baluster centering, carpenter `1/16"` tape rounding, and retaining wall math.
- **[stained-glass-svg-math](https://github.com/kaiyilu/stained-glass-svg-math)** · [Field Guide](https://kaiyilu.github.io/stained-glass-svg-math/)  
  Planar half-edge polygon partitioning, shared interior seam deduplication, inward mitered kerf offsets for copper foil and lead came, and cut-ready SVG serialization.
- **[ecommerce-image-specs](https://github.com/kaiyilu/ecommerce-image-specs)** · [Field Guide](https://kaiyilu.github.io/ecommerce-image-specs/)  
  Marketplace image requirement specs, Canvas2D pure-white (`RGB 255,255,255`) background boundary scanning, and Amazon 85% product frame-fill calculation.
- **[canvas-story-deck-kit](https://github.com/kaiyilu/canvas-story-deck-kit)** · [Field Guide](https://kaiyilu.github.io/canvas-story-deck-kit/)  
  `crypto.getRandomValues` Fisher-Yates deck shuffling, card spread layout coordinates, and high-DPI `1080×1920` HTML5 Canvas2D card rendering.
- **[grid-and-fretwork-math](https://github.com/kaiyilu/grid-and-fretwork-math)** · [Field Guide](https://kaiyilu.github.io/grid-and-fretwork-math/)  
  31-bit bitmask Nonogram line deduction, mid-game partial-state continuation & cell-by-cell lookahead contradiction proofs, 4-connected Marching Squares (`99.2%` IoU), half-pixel `(2W+1)×(2H+1)` EDT wire-gauge (`#65–#44`) pinhole sealing, `40 px/in` (`304.80 mm`) cut-to-cut calibration, 2D BFS stencil island auto-bridging, and zero-dependency `/ToUnicode` + 1:1 tiled vector PDF math.
- **[dxf-laser-quote-math](https://github.com/kaiyilu/dxf-laser-quote-math)** · [Field Guide](https://kaiyilu.github.io/dxf-laser-quote-math/)  
  Autodesk DXF group-code `42` `LWPOLYLINE` bulge arc integration, `1/64` Arbitrary Axis (`210/220/230` OCS → WCS) transforms, `2`-core contour pierce counting, and cent-exact laser job-shop quoting.

---

### Production Browser-Native Web Tools

| Project | Domain | Key Capabilities & Sub-Tools |
| :--- | :--- | :--- |
| **[Lighting Layout Calculator](https://lightinglayoutcalculator.com/)** | Photometrics & IES Grids | IES lumen-method & 128-point inverse-square task-zone illuminance, 2D rotated linear fixture & overhead garage-door track collision audit, ceiling fan strobe avoidance (base + shifted schedules), and `1/4"=1'-0"` & `1:50` bilingual CAD SVG/PDF exports across [Recessed](https://lightinglayoutcalculator.com/recessed-lighting-layout-calculator/), [Garage](https://lightinglayoutcalculator.com/garage-lighting-layout-calculator/), [High Bay](https://lightinglayoutcalculator.com/high-bay-lighting-calculator/), [Shop Light](https://lightinglayoutcalculator.com/shop-light-calculator/), and [LED](https://lightinglayoutcalculator.com/led-lighting-layout-calculator/) layouts |
| **[Baluster Spacing Calculator](https://balusterspacingcalculator.com/)** | IRC Framing & Layout | 2024 IRC R312.1.3 `< 4"` sphere & R507.5 framing layouts with zero-drift `1/16"` hook-tape marks across [Spindles](https://balusterspacingcalculator.com/spindle-spacing-calculator/), [Pickets](https://balusterspacingcalculator.com/picket-spacing-calculator/), [Deck Posts](https://balusterspacingcalculator.com/deck-post-spacing-calculator/), [Deck Footings](https://balusterspacingcalculator.com/deck-footing-calculator/), and [Fence Posts](https://balusterspacingcalculator.com/fence-post-spacing-calculator/) |
| **[Retaining Wall Block Calculator](https://retainingwallblockcalculator.com/)** | Structural Masonry & Earthwork | IRC R404.4 & NCMA base course embedment, geogrid tieback, and BOM schedules across [Drainage Gravel](https://retainingwallblockcalculator.com/retaining-wall-gravel-calculator/), [Timber Walls](https://retainingwallblockcalculator.com/timber-retaining-wall-calculator/), [Cinder Block Walls](https://retainingwallblockcalculator.com/cinder-block-wall-calculator/), and [CMU Grout Fill](https://retainingwallblockcalculator.com/cmu-block-fill-calculator/) |
| **[Laser Cutting Cost Calculator](https://lasercuttingcostcalculator.com/)** | Sheet-Metal DXF & SVG Quoting | Browser-local 2D DXF/SVG bulge-arc cut length, `2`-core pierce counting, open-loop blueprint checks, and [Batch White-Label PDF/CSV Quotes](https://lasercuttingcostcalculator.com/pricing/) |
| **[Stained Glass Pattern Generator](https://stainedglasspatterngenerator.com/)** | Computational Craft & SVG CAD | Planar half-edge shared-seam & kerf-compensated templates across [Photo-to-Pattern](https://stainedglasspatterngenerator.com/photo-to-stained-glass-pattern/), [SVG CAD](https://stainedglasspatterngenerator.com/svg-stained-glass-pattern-generator/), [Suncatchers](https://stainedglasspatterngenerator.com/suncatcher-stained-glass-patterns/), and [Glass Costing](https://stainedglasspatterngenerator.com/stained-glass-cost-calculator/) |
| **[Scroll Saw Pattern Generator](https://scrollsawpatterngenerator.com/)** | Woodworking Fretwork & Stencil CAD | `99.2%` IoU Marching Squares `1:1` US Letter & A4 tiled vector PDFs, Floating-Island Export Guard + Intarsia override, `304.80 mm` zero-padding flat-bottom welded CJK/Latin [Name Plaques](https://scrollsawpatterngenerator.com/scroll-saw-name-pattern-maker/) with open-top descender relief coves & half-pixel EDT (`#65–#44`) pinhole sealing, [Photo Stencils](https://scrollsawpatterngenerator.com/stencil-maker-from-photo/), [Wood Burning](https://scrollsawpatterngenerator.com/wood-burning-pattern-generator/), and [Blade Sizing](https://scrollsawpatterngenerator.com/scroll-saw-blade-chart/) |
| **[NonogramGrid](https://nonogramgrid.com/)** | Deterministic Logic Puzzle Engine | Unique-solution guard at [Photo Generator](https://nonogramgrid.com/nonogram-generator/) (`Clean Silhouette`, `Sharp Contours` & `Portrait Dither`), mid-game partial-board [Step Solver](https://nonogramgrid.com/nonogram-solver/) (`5x5–20x20`, bulk clue paste & cell-by-cell lookahead contradiction proofs), 30-puzzle progressive `Mix 5->20` bilingual `/ToUnicode` vector PDF booklets at [Printable PDFs](https://nonogramgrid.com/printable-nonogram-puzzles/) (Letter/A4 + separate answer keys), and [Daily Nonogram](https://nonogramgrid.com/daily-nonogram/) |
| **[QuickKit](https://usequickkit.com/)** | Client-Side Ecommerce Pipelines | In-memory [Excel URL Downloader](https://usequickkit.com/how-to-download-files-from-excel-urls), [SKU Image Renamer](https://usequickkit.com/bulk-download-product-images-by-sku), [Shopify Size Guide](https://usequickkit.com/shopify-image-size-guide) & [Bulk Resizer](https://usequickkit.com/shopify-bulk-image-resizer), [Amazon](https://usequickkit.com/amazon-main-image-checker) & [Etsy](https://usequickkit.com/etsy-listing-photo-checker) checkers |
| **[VibeKit](https://usevibekit.com/)** | Canvas2D & Interactive Decks | Zero-account spreads including [Yes/No Tarot](https://usevibekit.com/yes-or-no-tarot), [Situationship Spread](https://usevibekit.com/situationship-tarot-spread), [Love](https://usevibekit.com/love-yes-or-no-tarot), [Thinking About Me](https://usevibekit.com/is-he-thinking-about-me-tarot), [Career](https://usevibekit.com/career-yes-or-no-tarot), and [Daily Vibe Card](https://usevibekit.com/daily-vibe-card) |

---

### Engineering Notes

- [4-Connected Marching Squares, Half-Pixel EDT Drill Clearance & 2D Ceiling CAD Collision Math in TypeScript](https://dev.to/kaiyilu/4-connected-marching-squares-half-pixel-edt-drill-clearance-2d-ceiling-cad-collision-math-in-17ep)
- [Zero-Dependency Bilingual Vector PDFs (/ToUnicode + 4x Scanlines) & Nonogram Contradiction Proofs in TypeScript](https://dev.to/kaiyilu/zero-dependency-bilingual-vector-pdfs-tounicode-4x-scanlines-nonogram-contradiction-proofs-19e5)
- [Solving Carpenter 1/16" Tape Rounding and IES Lighting Grids in Vanilla JS](https://dev.to/kaiyilu/solving-carpenter-116-tape-rounding-and-ies-lighting-grids-in-vanilla-js-399o)
- [Batch-Downloading Excel Image URLs & Calculating Amazon 85% Product Fill in Pure Browser JS](https://dev.to/kaiyilu/batch-downloading-excel-image-urls-calculating-amazon-85-product-fill-in-pure-browser-js-aip)
- [Generating Cut-Ready Stained Glass SVGs in Pure Browser JS: Shared Half-Edges & Copper Foil Kerf](https://dev.to/kaiyilu/generating-cut-ready-stained-glass-svgs-in-pure-browser-js-shared-half-edges-copper-foil-kerf-3dpm)
- [Frustum Concrete Pier Math, High-Bay Beam Cones & Running-Bond CMU Deductions in Vanilla TypeScript](https://dev.to/kaiyilu/frustum-concrete-pier-math-high-bay-beam-cones-running-bond-cmu-deductions-in-vanilla-typescript-3325)
- [Bitmask Nonogram Line Solvers & 2D BFS Stencil Island Bridging in Pure TypeScript](https://dev.to/kaiyilu/bitmask-nonogram-line-solvers-2d-bfs-stencil-island-bridging-in-pure-typescript-194d)
- [Exact 2D DXF Bulge Arcs, AutoCAD OCS Transforms & 2-Core Laser Pierce Counting in TypeScript](https://dev.to/kaiyilu/exact-2d-dxf-bulge-arcs-autocad-ocs-transforms-2-core-laser-pierce-counting-in-typescript-4a0c)
