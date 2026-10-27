# Survivor Incognito — Subnautica 2D Terrain Atlas

An interactive, unofficial *Subnautica* map by **Survivor Incognito**. Explore source-derived seafloor relief, biome regions, cave charts, notable locations, and an Aurora interior schematic in your browser.

**Status:** Public beta v0.9. Terrain coverage, location references, and navigation guidance may be refined as the atlas develops.

## What's included

- **Crater seafloor:** terrain relief and biome views, with selectable geography layers.
- **Underground regions:** Jellyshroom Caves, Lost River, Inactive Lava Zone, and Lava Lakes, with available depth views.
- **Location markers:** lifepods, wrecks, entrances, signals, landmarks, hazards, and story locations.
- **Aurora interior:** room schematic, upper/lower entrance route highlighting, and locally saved explored-room progress.
- **Primary Containment Facility:** a distinct marker and an *approximate* story-location footprint in Lava Lakes. Story locations can be hidden to avoid spoilers.
- **Map controls:** search, region switching, zoom and drag, mobile pinch-to-zoom, and an expanded/full-screen map view.
- **Coordinates:** selected locations show X, Y, and Z in game order, with plain-number copying and location links.

## How to use it

1. Choose a region from the region tabs or the mobile region selector.
2. Use the layer controls and filters to show the information you need.
3. Tap or click a marker to see its name and coordinates; open **View details** for more information.
4. Use the **Copy X, Y, Z** control to copy coordinates as plain numbers (for example, `305, -100, 450`).
5. Zoom using the `+` and `−` buttons or pinch on a touch screen. Use **Expand** for a larger map view.
6. Enable **Story** locations when you want to reveal story-related markers such as the Primary Containment Facility.

## Publish with GitHub Pages

This repository is a **static, single-page site**. No build step, package manager, or server-side code is required: the maps, styles, and scripts are included in `index.html`.

1. Create a **public** GitHub repository, for example `subnautica-atlas`.
2. Upload `index.html` and `README.md` to the repository's **top level** (not into a subfolder).
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Once GitHub Pages finishes publishing, open the URL shown in the repository's **Pages** settings. Test the map on a desktop browser and on your phone before linking it from your Survivor Incognito website.

To update the atlas later, replace the root-level `index.html` with the updated version and commit the change.

## Accuracy and limitations

- The terrain artwork is rendered from locally supplied *Subnautica* terrain and biome data. **Source coverage varies by region.** Hatched or unconfirmed areas are not surveyed surfaces.
- Location coordinates are references and have **not all been independently verified**. Do not assume a straight-line bearing is a safe in-game route.
- The Primary Containment Facility overlay is an indicative landmark/story footprint, **not an exact building outline**.
- Depth views and seafloor relief are for exploration reference, **not safe-navigation depth charts**.
- The atlas is a work in progress. Expect corrections and refinements as issues are identified.

## Credits and disclaimer

Created by **Survivor Incognito**. The atlas artwork was rendered from locally supplied game terrain and biome data. Community references used during development include the *Subnautica Wiki* and Rocketsoup's numbered wreck inventory; references to locations and potential finds remain approximate.

This is a **free, unofficial fan project**. *Subnautica* belongs to **Unknown Worlds Entertainment**. No affiliation or endorsement is implied.

## Repository files

- `index.html` — the complete interactive atlas (open this file in a browser to test locally).
- `README.md` — this guide and publishing instructions.

No separate image, CSS, JavaScript, or data downloads are needed for the supplied release file.
