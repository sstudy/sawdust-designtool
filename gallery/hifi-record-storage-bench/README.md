# Hi-Fi Record Storage Bench

A long, low walnut-plywood cabinet with two sliding doors, five internal dividers making six LP cubbies, a cushioned seat on top and six tapered solid-walnut feet. About 80" wide, 16½" deep and 19" tall with the feet. Turntable and amplifier sit on the open end; records file between the dividers.

**Files**

- `hifi-record-storage-bench.swdt` — the design. Open it with File → Open in SawDust (6.0 or later).
- `bench.png` — the viewport view.

**Try it first**

Open the **Params** tab and change `CarcaseWidth` (80¼" as shipped) to 96, or `FootHeight` to 6. The six cubbies re-space themselves, the dados move with the dividers, the two doors resize and still meet in the middle, the feet and cushion follow, and the records stay in their cubbies. Then open the cut list again — every part and every dado is an expression of a few named parameters, so the whole bench resizes from a handful of numbers.

**What it demonstrates**

- A carcass in 3/4" walnut plywood with a 1/4" plywood back in rabbets, and solid banding on every visible plywood edge (the `Top Front Banding`, `Left Side Front Banding`… parts), each glued on with a butt joint.
- Five dividers housed in stopped dados in the top and bottom, spaced by a `CubbyWidth` parameter derived from the carcase width.
- Sliding door panels running in top and bottom grooves of different depths (`DoorGrooveDepthTop` deeper than `DoorGrooveDepthBottom`, so a door lifts in and drops down), sized by `DoorPanelLength`/`DoorPanelHeight` so they always overlap by `DoorOverlap`.
- Tapered feet cut with `taper` features, mitred banding corners with `miterCut`, and a rounded-over "fiddle" rail around the cushion.
- Record props and a cushion on an **Extras** layer, excluded from the shop outputs — the cut list, sheet layout, shop drawings and assembly pages show only what you build.
- A hardware list with the door pulls on it (the design notes say where to buy them).

Updated 2026-10-15: the design was reworked so that every placement, not just every dimension, follows its parameters. The dimensions and positions at the default values are unchanged from the original.

**Contributed by** Stephen Study. Licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
