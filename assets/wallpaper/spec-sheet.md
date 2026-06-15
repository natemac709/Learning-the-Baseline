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

### Directory: `billboard/`

#### Asset 7: Monumental Structural Facade
*   **Dimensions**: 7680 x 4320 px
*   **Aspect Ratio**: 16:9 (Ultra-HD Large-Format LED Grid)
*   **Format Constraint**: Rendered with raw, high-bit-depth pixel values to prevent color banding on large-scale urban outdoor emissive screens.
*   **Structural Layout**: Lower-Right Asymmetric Weight (The Daypack Shift).
    *   *System Overlay Zone (Top/Left 60%)*: `0px` to `4608px` horizontally. Leave this expansive area as a solid, unmoving field of deep `Everglade` green. This provides macro-scale breathing room and isolates the display from surrounding ambient urban noise.
    *   *Safe/Anchor Zone (Lower-Right 40%)*: `4608px` to `7680px` horizontally, locked between `y = 2160px` and `y = 4320px`.
*   **Editorial Composition**: Apply a minimal, highly contrastive geometric line illustration (such as stark, radiating linear strokes or an architectural silhouette) rendered in crisp `Olivetone` across the top horizon. Within the lower safe zone, position a single core phrase from the scriptural payload in massive, elegant `Warm White` Serif typography. Anchor the exact citation directly underneath in a single row of all-caps `Monospace`.
*   **Disruption Goal**: Transforms a high-stress, frantic commercial corridor or concrete transit plaza into a permanent digital stone monument. It provides immediate low-luminance relief, lowering eye strain for local commuters, transit neighbors, and workers on the street.

#### Asset 8: Spherical Architectural Projection (Exosphere Blueprint)
*   **Dimensions**: 8192 x 4096 px (or native 8K x 4K Equirectangular projection map layout).
*   **Aspect Ratio**: 2:1 Polar Grid Wrap (For 360-degree geodesic geodesic surfaces).
*   **Format Constraint**: Rendered with strict solid-fill vector rendering blocks; zero blending gradients or smooth shadow drop-offs to prevent dynamic pixel tearing across 1.2 million physical LED modules.
*   **Structural Layout**: Polar Asymmetric Bottom Inset.
    *   *System Overlay Zone (Upper 70% Hemisphere)*: This vast dome curve is flooded with a completely solid field of deep, low-luminance `Everglade` green. It forms an unmoving canopy of silent color over the city skyline, swallowing glare and acting as a physical circuit breaker for the strip.
    *   *Safe/Anchor Zone (Lower 30% Equator Rim)*: Pinned exclusively around the lower horizontal tracking base of the hemisphere ($y = 2867\text{px}$ to $y = 4096\text{px}$) to align with the direct line-of-sight of pedestrians and drivers on the street level.
*   **Editorial Composition**: Construct a continuous, minimalist `Olivetone` single-line frame wrapping entirely around the lower rim like an ancient stone base molding. Inside this lower band, position a single, high-contrast core phrase in authoritative `Warm White` Serif typography. Diagonal cross-lines or abstract structural shapes must use simple perfect stair-steps to prevent pixel-blur on the low-density external LED array.
*   **Disruption Goal**: Converts a hyper-frenzied commercial entertainment dome into a permanent, unmoving stone-like monument of absolute silence. It acts as a massive public sanctuary window that cools the local atmosphere and completely restores intentional focus to visitors and workers on the ground.

---

### Directory: `monument/`

#### Asset 9: Universal Ancient Structural Skin
*   **Dimensions**: 7680 x 4320 px (Scalable 8K Horizontal Projection Grid).
*   **Target Infrastructure**: Ancient or historic stone, brick, timber, or mud-brick facades (e.g., pyramids, ancient temples, classic masonry halls, ruins).
*   **Primary Engineering Intent**: Transforming a historic public monument into a living visual anchor of peace, using the structure's physical masonry as the grid system.
*   **Active Architectural Mapping Constraints**:
    *   **The Material Gutter Rule**: The projection engine must treat physical masonry seams, joints, or heavy pillars as natural margins. Text rows must nest cleanly *inside* flat stone surfaces or between structural columns.
    *   **The Texture Adaptability Check**: No soft digital shadows or complex shapes. Visual elements must stay restricted to flat, sharp geometric lines (using Olivetone `#7B8B0F`). This allows the design to read cleanly over textured surfaces like ancient brick, rough granite, or weathered timber without blurring.
    *   **Luminance Cap**: Total light output must be strictly limited to a matte, non-glare finish. This respects the historic building material and prevents light pollution in the surrounding community.

---

### Directory: `e-panel/`

#### Asset 9: Static E-Ink Ambient Plaquard
*   **Dimensions**: 2560 x 1600 px
*   **Aspect Ratio**: 16:10 (Standard Portrait/Landscape Electronic Ink Panel)
*   **Format Constraint**: Strict 1-bit or grayscale bitmap output profile optimized for electrophoretic reflective displays; zero anti-aliasing or pixel-blending to prevent micro-text blurring.
*   **Structural Layout**: Total Perimeter Framing.
    *   *System Overlay Zone (Outer 40px Rim)*: Keep entirely clear to match the physical bevel or wooden housing frame of the device.
    *   *Safe/Anchor Zone*: The inner text canvas container.
*   **Editorial Composition**: Set the canvas to a flat, untextured `Warm White` layer. Construct a clean, double-ruled geometric border frame using a `1px` thick line in pure `True Black` or deep `Everglade` green. Center a short, authoritative, two-line serif statement or citation precisely in the middle of the frame.
*   **Disruption Goal**: Converts an active digital screen into a completely passive, zero-glare, stone-like decorative plaque that blends seamlessly into the physical furniture or woodwork of a quiet home study or library.

---

### Directory: `pillar/`

#### Asset 10: Standalone Floor Kiosk Matrix
*   **Dimensions**: 1080 x 2340 px
*   **Aspect Ratio**: 9:19.5 (Vertical Standalone Enclosure)
*   **Format Constraint**: High-fidelity, sharp compression profile to ensure high-contrast legibility for close-in, face-to-face foot traffic.
*   **Structural Layout**: Central Column Isolation Block.
    *   *System Overlay Zone (Top/Bottom 400px)*: Keep entirely clear of text to account for heavy physical finger-smudging, ambient light reflections, or device touch menus.
    *   *Safe/Anchor Zone (Center Gutter)*: Pinned exactly between `y = 400px` and `y = 1940px`.
*   **Editorial Composition**: Set the background to a solid field of deep `Everglade` green. Construct a rigid, vertical text column centered in the gutter, bordered by thin, vertical `Olivetone` lines running top to bottom. Text lines inside this column must be strictly clamped to a 40-character maximum measure using a crisp Serif font scale.
*   **Disruption Goal**: Interrupts the routine process of checking in at a lobby, hospital wayfinder, or registration podium with a highly ordered, reverent typographic sanctuary window.

---

### Directory: `transit/`

#### Asset 11: Environmental Transit Pylon Facade
*   **Dimensions**: 2160 x 3840 px
*   **Aspect Ratio**: 9:16 (High-Scale Vertical Infrastructure Pylon)
*   **Format Constraint**: High-bit-depth pixel values to prevent color banding across massive public emissive outdoor screens.
*   **Structural Layout**: Top-Biased High Clearance.
    *   *System Overlay Zone (Bottom 50%)*: `1920px` to `3840px` vertically. Keep this entire lower zone a solid, flat, un-moving field of `True Black` or deep `Everglade` green to clear physical visual interference from passing vehicles, crowds, or transit text tickers.
    *   *Safe/Anchor Zone (Top 50%)*: Locked cleanly between `y = 0px` and `y = 1920px` to match the elevated line-of-sight of travelers.
*   **Editorial Composition**: Flood the upper safe canvas with a low-luminance `Everglade` backdrop. Center a single core phrase from the scripture payload using massive, elegant `Warm White` Serif typography. Diagonal lines or accent structural marks must use simple, unblended stair-steps to prevent pixel tearing on low-density LED arrays.
*   **Disruption Goal**: Transforms a high-stress, frantic transit hub or urban walking path into an unhurried, peaceful landmark, providing immediate visual relief for tired commuters and workers.

---

### Directory: `liturgy/`

#### Asset 12: Architectural Stage Projection Sheet
*   **Dimensions**: 3840 x 1080 px
*   **Aspect Ratio**: 32:9 (Ultra-Wide Panorama Stage Canvas)
*   **Format Constraint**: High-contrast, low-luminance rendering to prevent light leak or wash-out from physical stage lights.
*   **Structural Layout**: Extreme Lower-Right Corner Shift.
    *   *System Overlay Zone (Left/Center 75%)*: Keep this vast expanse a flat, solid field of deep `Everglade` green or strict black to leave room for human interaction, speakers, or sanctuary architectural features.
    *   *Safe/Anchor Zone (Lower-Right 25%)*: Locked tightly along the bottom right margins.
*   **Editorial Composition**: Apply a minimal, highly contrastive geometric line pattern (using fine `1px` lines in `Olivetone`) that mirrors the natural architectural lines or roof pitch of the gathering space. Within the lower-right safe quadrant, place a single citation and reference in clean, thin `Warm White` Serif typography, leaving massive padding around the text block.
*   **Disruption Goal**: Replaces chaotic, moving video loops or flashing church media banners with a quiet, motionless, and deeply reverent architectural backdrop that respects the sanctity of the room.

---

## Part 3: The Design Execution Blueprint

When drafting the visual composition for these assets, execute them using this strict developmental sequence:

1.  **Isolate the Canvas Spaces**: Block out the global dimensions using your three primary color blocks (`Everglade`, `Olivetone`, and `Warm White`) as flat backgrounds.
2.  **Impose the Structural Shadows**: Draw lines or place shapes that explicitly map out the system overlay zones. Treat these overlay boxes as "walls" that your design cannot touch or cross.
3.  **Apply Typographic Weights**: Place your text copy or central architectural symbols purely inside the safe zones. Check that the serif headers have enough letter-spacing to look ancient and unhurried.
4.  **Verify Contrast and Measure**: Test the layout's readability. If it's a dark background (`Everglade`), ensure the text is heavy enough to be legible from a distance. If it's a light background (`Warm White`), check that the margins take up at least half of the total canvas area.
