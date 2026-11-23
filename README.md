# Kaiyi Lu

Building **zero-backend, browser-native engineering tools** and **auditable JavaScript geometry & calculation modules**.

Most utility software ships a server it doesn't need. My work focuses on pushing deterministic calculations, vector CAD path generation, photometric & residential code layouts, and batch file/image pipelines directly into the client runtime using vanilla ES modules, WebAssembly/Canvas2D, SVG path math, and streaming browser APIs—with zero server uploads and zero account friction.

- **Engineering Hub & Spec Index:** [https://kaiyilu.github.io/](https://kaiyilu.github.io/)

---

### Open-Source Specifications & Zero-Dependency JS Modules

Small, dependency-free reference libraries and interactive field guides documenting the exact math behind production tools:

- **[building-layout-math](https://github.com/kaiyilu/building-layout-math)** · [Field Guide](https://kaiyilu.github.io/building-layout-math/)  
  IES lumen-method ceiling grid spacing, IRC R312.1.3 `< 4"` baluster centering, carpenter `1/16"` fraction rounding without cumulative drift, and segmental retaining wall course/aggregate math.
- **[stained-glass-svg-math](https://github.com/kaiyilu/stained-glass-svg-math)** · [Field Guide](https://kaiyilu.github.io/stained-glass-svg-math/)  
  Planar half-edge polygon partitioning, shared interior seam deduplication, inward mitered kerf offsets for copper foil and lead came, and cut-ready SVG serialization.
- **[ecommerce-image-specs](https://github.com/kaiyilu/ecommerce-image-specs)** · [Field Guide](https://kaiyilu.github.io/ecommerce-image-specs/)  
  Marketplace image requirement specs, Canvas2D pure-white (`RGB 255,255,255`) background boundary scanning, and Amazon 85% product frame-fill calculation.
- **[canvas-story-deck-kit](https://github.com/kaiyilu/canvas-story-deck-kit)** · [Field Guide](https://kaiyilu.github.io/canvas-story-deck-kit/)  
  `crypto.getRandomValues` Fisher-Yates deck shuffling, card spread layout coordinates, and high-DPI `1080×1920` HTML5 Canvas2D card rendering.

---

### Production Browser-Native Web Tools

| Project | Domain | Key Capabilities & Sub-Tools |
| :--- | :--- | :--- |
| **[Lighting Layout Calculator](https://lightinglayoutcalculator.com/)** | Photometrics & IES Grids | S/MH ratio & ceiling coordinate plots for [Recessed](https://lightinglayoutcalculator.com/recessed-lighting-layout-calculator/), [Garage](https://lightinglayoutcalculator.com/garage-lighting-layout-calculator/), [High Bay](https://lightinglayoutcalculator.com/high-bay-lighting-calculator/), and [LED](https://lightinglayoutcalculator.com/led-lighting-layout-calculator/) layouts |
| **[Baluster Spacing Calculator](https://balusterspacingcalculator.com/)** | IRC Framing & Layout | Centered vs. even-bay `1/16"` tape marks for [Spindles](https://balusterspacingcalculator.com/spindle-spacing-calculator/), [Deck Posts](https://balusterspacingcalculator.com/deck-post-spacing-calculator/), and [Fence Posts](https://balusterspacingcalculator.com/fence-post-spacing-calculator/) |
| **[Retaining Wall Block Calculator](https://retainingwallblockcalculator.com/)** | Structural Masonry & Earthwork | Base course embedment and BOM schedules for [Drainage Gravel](https://retainingwallblockcalculator.com/retaining-wall-gravel-calculator/), [Timber Walls](https://retainingwallblockcalculator.com/timber-retaining-wall-calculator/), and [CMU Grout Fill](https://retainingwallblockcalculator.com/cmu-block-fill-calculator/) |
| **[Stained Glass Pattern Generator](https://stainedglasspatterngenerator.com/)** | Computational Craft & SVG CAD | Kerf-compensated templates for [Photo-to-Pattern](https://stainedglasspatterngenerator.com/photo-to-stained-glass-pattern/), [SVG CAD](https://stainedglasspatterngenerator.com/svg-stained-glass-pattern-generator/), [Suncatchers](https://stainedglasspatterngenerator.com/suncatcher-stained-glass-patterns/), and [Glass Costing](https://stainedglasspatterngenerator.com/stained-glass-cost-calculator/) |
| **[Scroll Saw Pattern Generator](https://scrollsawpatterngenerator.com/)** | Woodworking Fretwork & Stencil CAD | 2D BFS floating-island detection & auto-bridges for [Name Plaques](https://scrollsawpatterngenerator.com/scroll-saw-name-pattern-maker/), [Photo Stencils](https://scrollsawpatterngenerator.com/stencil-maker-from-photo/), [Wood Burning](https://scrollsawpatterngenerator.com/wood-burning-pattern-generator/), and [Blade Sizing](https://scrollsawpatterngenerator.com/scroll-saw-blade-chart/) |
| **[NonogramGrid](https://nonogramgrid.com/)** | Deterministic Logic Puzzle Engine | Bitmask uniqueness-verified grids with [Photo-to-Nonogram Generator](https://nonogramgrid.com/nonogram-generator/), [Daily Nonogram](https://nonogramgrid.com/daily-nonogram/), [Printable PDF Packs](https://nonogramgrid.com/printable-nonogram-puzzles/), and [Step Solver](https://nonogramgrid.com/nonogram-solver/) |
| **[QuickKit](https://usequickkit.com/)** | Client-Side Ecommerce Pipelines | In-memory [Excel URL Downloader](https://usequickkit.com/how-to-download-files-from-excel-urls), [SKU Image Renamer](https://usequickkit.com/bulk-download-product-images-by-sku), [Shopify Size Guide](https://usequickkit.com/shopify-image-size-guide) & [Bulk Resizer](https://usequickkit.com/shopify-bulk-image-resizer), [Amazon](https://usequickkit.com/amazon-main-image-checker) & [Etsy](https://usequickkit.com/etsy-listing-photo-checker) checkers |
| **[VibeKit](https://usevibekit.com/)** | Canvas2D & Interactive Decks | Zero-account spreads including [Yes/No Tarot](https://usevibekit.com/yes-or-no-tarot), [Situationship Spread](https://usevibekit.com/situationship-tarot-spread), [Love](https://usevibekit.com/love-yes-or-no-tarot), [Thinking About Me](https://usevibekit.com/is-he-thinking-about-me-tarot), [Career](https://usevibekit.com/career-yes-or-no-tarot), and [Daily Vibe Card](https://usevibekit.com/daily-vibe-card) |

---

### Engineering Notes

- [Solving Carpenter 1/16" Tape Rounding and IES Lighting Grids in Vanilla JS](https://dev.to/kaiyilu/solving-carpenter-116-tape-rounding-and-ies-lighting-grids-in-vanilla-js-399o)
- [Batch-Downloading Excel Image URLs & Calculating Amazon 85% Product Fill in Pure Browser JS](https://dev.to/kaiyilu/batch-downloading-excel-image-urls-calculating-amazon-85-product-fill-in-pure-browser-js-aip)
- [Generating Cut-Ready Stained Glass SVGs in Pure Browser JS: Shared Half-Edges & Copper Foil Kerf](https://dev.to/kaiyilu/generating-cut-ready-stained-glass-svgs-in-pure-browser-js-shared-half-edges-copper-foil-kerf-3dpm)
