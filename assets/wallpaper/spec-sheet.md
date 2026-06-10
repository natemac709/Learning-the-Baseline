# Master Production Specifications: Institutional Print & Canvas Alignment

This technical specification sheet outlines the spatial design rules, visual hierarchies, and human behavioral constraints for our multi-platform ambient asset library. It fuses the "Mindful Disruption" philosophy with the traditional, low-tech editorial DNA of historical institutions (the "open book" archetype). Every rule is calibrated to simulate the quiet authority of classic print publishing while engineering geometric safe zones around device user-interface overlays.

---

## Part 1: Core Brand Tokens & Typographic Systems

These specific visual properties must be enforced across all layout structures to maintain a unified, disciplined identity.

### 1. Color Palette System
*   **The Backdrop Base (`Everglade`)**: `#285127` — A deep, grounding green providing an atmospheric, low-luminance canvas for dark rooms and digital gaming engines.
*   **The Liturgical Signpost (`Olivetone`)**: `#7B8B0F` — Used strictly for structural lines, geometric highlights, thin rules, and subtle micro-typography metadata.
*   **The Uncoated Stock (`Warm White`)**: `#FDFBF7` or `#F4F1EA` — Pure digital white (`#FFFFFF`) is banned. This soft tone mimics un-coated book paper, completely eliminating appliance and screen glare.

### 2. Editorial Typography Rules
*   **Primary Display Headers (The "Tradition" Axis)**: Use an authoritative, historical Serif font family (e.g., *Garamond*, *Georgia*, or *Merriweather*). 
    *   *Spacing Constraint*: Open up letter-spacing slightly (`+0.04em`) to simulate traditional metal-type press spacing.
*   **Metadata Folios (The "Back-End" Axis)**: Use a highly disciplined, utilitarian monospace font family (e.g., *SF Mono* or *JetBrains Mono*).
    *   *Spacing Constraint*: All-caps, tracked out generously (`+0.1em`), scaled down to a tiny footprint to look like a precise catalog reference marker.
*   **Vertical Spacing (Leading)**: Line-height for any multi-line copy must sit between **140% and 160%** of the font size. This wide vertical breathing room forces a slower, more deliberate reading speed.

---

## Part 2: Folder Asset Specification Catalog

Below are the exact dimensions, structural boundaries, compositions, and behavior-oriented guidelines for the 6 assets in the repository.

### Directory: `alternative-web/`

#### Asset 1: Smart TV Backdrop
*   **Dimensions**: 3840 x 2160 px
*   **Aspect Ratio**: 16:9 (Ultra-HD Widescreen)
*   **Format Constraint**: Saved at a high-quality compression profile to completely smooth out color bands.
*   **Structural Layout**: Left-to-Right Asymmetric Split.
    *   *System Overlay Zone (Left 40%)*: `0px` to `1536px` horizontally. Keep this area a flat, solid field of `Everglade` green to accommodate loud Smart TV user interface cards and system menus.
    *   *Safe/Anchor Zone (Right 60%)*: `1536px` to `3840px` horizontally. 
*   **Editorial Composition**: Place a thin, double-ruled bounding box (`1px` thick lines) in `Olivetone` inside the upper-right quadrant. Nest a single, tiny, centered typographic folio inside it. 
*   **Disruption Goal**: Converts a glaring, chaotic television screen into a resting, dim "sanctuary window" when the streaming remote is paused.

#### Asset 2: Link-in-Bio Background
*   **Dimensions**: 1125 x 2436 px
*   **Aspect Ratio**: 9:19.5 (Modern Mobile Column)
*   **Format Constraint**: High-fidelity rendering to keep narrow text lines razor-sharp on mobile viewports.
*   **Structural Layout**: Vertical Sandwich Stack.
    *   *System Overlay Zone (Top/Bottom)*: Block out the top `150px` (mobile statuses) and bottom `200px` (in-app browser navigation bars). 
    *   *Safe/Anchor Zone (Center Column)*: A narrow vertical spine running straight down the center.
*   **Editorial Composition**: Set the background to `Warm White`. Create a central vertical gutter using two micro-thin `Olivetone` rules running top to bottom. Text lines inside this column must be strictly clamped to a 45-character measure.
*   **Disruption Goal**: Forces a user scrolling through hyper-fast links to drop their eyes down a clean, disciplined literary column, instantly slowing their navigation speed.

---

### Directory: `smart-appliances/`

#### Asset 3: Smart Fridge Full Screen
*   **Dimensions**: 1080 x 1920 px
*   **Aspect Ratio**: 9:16 (Standard Portrait Display)
*   **Format Constraint**: Zero digital artifacting allowed to preserve clean, un-coated paper texturing.
*   **Structural Layout**: High-Margin Vertical Stack.
    *   *System Overlay Zone (Bottom 300px)*: Keep this area empty of core graphics to account for heavy physical finger-smudging and device swipe menus.
    *   *Safe/Anchor Zone (Top/Middle)*: Elevated 3:2 ratio framing to hit natural eye level.
*   **Editorial Composition**: Use a `Warm White` background canvas. Place a stark, bold initial drop-cap header in `Everglade` green right at eye level (`y = 400px` to `y = 800px`). Frame the text with massive padding margins (minimum `120px` on left/right edges).
*   **Disruption Goal**: Replaces chaotic, glaring digital widgets with the elegant, peaceful illusion of a giant page printed on heavy matte cardstock embedded into the kitchen wall.

#### Asset 4: Smart Fridge Widget Panel
*   **Dimensions**: 1080 x 1080 px
*   **Aspect Ratio**: 1:1 (Square Module Canvas)
*   **Format Constraint**: Rigid grid boundaries to fit modular dashboard windows.
*   **Structural Layout**: Centered Monolith block.
    *   *System Overlay Zone (Top 100px)*: Leave empty for the permanent hardware dashboard (Wi-Fi, clock, operating temperature).
    *   *Safe/Anchor Zone*: The remaining `980px` square container.
*   **Editorial Composition**: A deep `Everglade` solid background block. Construct a clean square inset boundary border using a single-pixel `Olivetone` line, inset by exactly `60px` on all sides. Center a short, authoritative, three-line serif verse or statement within it.
*   **Disruption Goal**: Interrupts the routine process of checking a grocery list with a highly ordered, reverent typographic plaque.

---

### Directory: `virtual-worlds/`

#### Asset 5: Roblox Billboard Texture
*   **Dimensions**: 1024 x 512 px
*   **Aspect Ratio**: 2:1 (Wide Landscape Polygonal Mapping)
*   **Format Constraint**: Crisp texture formatting optimized for 3D engine rendering and network streaming pipelines.
*   **Structural Layout**: Concentric Center Ring.
    *   *System Overlay Zone (Outer 10% Edge)*: Leave entirely empty to absorb 3D dynamic game camera stretching and engine perspective distortion.
    *   *Safe/Anchor Zone*: The inner 80% box.
*   **Editorial Composition**: Set the billboard to a flat, completely solid `Everglade` block. Center an abstract, architectural emblem (like a clean, flat, stylized archway silhouette) using pure `Warm White` with an outer accent line in `Olivetone`. No digital gradients or artificial engine lighting shadows.
*   **Disruption Goal**: A player sprinting past at high-adrenaline game speeds encounters an oasis of absolute solid flat color and ancient geometry, serving as an intentional structural landmark.

#### Asset 6: Minecraft Map Art Mosaic
*   **Dimensions**: 128 x 128 px
*   **Aspect Ratio**: 1:1 (Fixed Grid Locking, 1 pixel = 1 Block)
*   **Format Constraint**: Hard color profile matching the game engine's native in-game map palette limits.
*   **Structural Layout**: Total Canvas Grid.
    *   *System/Safe Zone*: There are zero system overlays or margins here. The layout requires perfect pixel-level alignment; shifting a line by one pixel breaks the pattern in-game.
*   **Editorial Composition**: Build a stark, blocky structural layout. Use a heavy block-cross or an unadorned vertical line layout using solid pixel rows of `Everglade` green and `Warm White`. Diagonal lines must be structured in perfect, matching stair-steps to maintain order.
*   **Disruption Goal**: Replaces a noisy, procedurally generated video game terrain with a highly refined, hand-built architectural monument of pure human intent.

---

## Part 3: The Design Execution Blueprint

When drafting the visual composition for these assets, execute them using this strict developmental sequence:

1.  **Isolate the Canvas Spaces**: Block out the global dimensions using your three primary color blocks (`Everglade`, `Olivetone`, and `Warm White`) as flat backgrounds.
2.  **Impose the Structural Shadows**: Draw lines or place shapes that explicitly map out the system overlay zones. Treat these overlay boxes as "walls" that your design cannot touch or cross.
3.  **Apply Typographic Weights**: Place your text copy or central architectural symbols purely inside the safe zones. Check that the serif headers have enough letter-spacing to look ancient and unhurried.
4.  **Verify Contrast and Measure**: Test the layout's readability. If it's a dark background (`Everglade`), ensure the text is heavy enough to be legible from a distance. If it's a light background (`Warm White`), check that the margins take up at least half of the total canvas area.
