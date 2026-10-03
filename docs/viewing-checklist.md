# Viewing capture checklist

[English](viewing-checklist.md) | [日本語](viewing-checklist.ja.md)

For furniture layout, delivery access, cabling and appliance installation. Planned
visit: **Sunday, 2026-10-04**. Listing area is not usable room geometry. Fill a
private copy of the [measurement](../homes/home2/data/viewing-measurements.yaml)
and [delivery](../homes/home2/data/delivery-route.yaml) templates.

## Existing assumptions and preparation decision

Existing workflow: Polycam + smartphone photos → GLB and YAML in metres →
AI-assisted dimensioned PNG/SVG/PDF plans. Scan dimensions are approximate.
Device model, LiDAR, app version, plan and export entitlement are unconfirmed.

Resolve one bundle before departure: **phone/model and app version, LiDAR yes/no,
tested save/export/offline route on the current account, and capture permission**.
If unresolved, use photos + manual measurements. No paid app or new subscription
is required.

## Public templates, private evidence

This repository is public. Keep only generic checklists and blank templates here.
Save actual dimensions, floor plans, scans, photos, videos, addresses, unit numbers
and permission notes in a private folder **outside this Git checkout**, with an
access-controlled backup or existing private repository. Do not make public
Polycam links. Photography permission does not imply publication permission.

Suggested private tree: `home2/2026-10-04/{originals,exports,photos,notes,outputs}/`.
Preserve originals; keep redacted copies separately. Even nameless geometry and
window views can identify a home. Any separately approved publication needs
review of faces/reflections, possessions, documents, keys, labels, filenames,
EXIF/location and geometry. Existing public home1 assets are not permission for
home2 publication.

## Before the visit

- [ ] Confirm duration and agent/occupant permission for photos, scan, cupboards,
  common areas, lights, and opening doors/windows. Ask before moving objects or
  attaching removable labels; note restricted areas.
- [ ] Bring a 5 m+ tape, optional existing laser meter, notebook/pen, downloaded
  templates/checklist, removable labels if permitted, charged phone, power bank
  and cable. Use a helper for long readings where possible. No equipment purchase
  is required. Do not climb on unstable surfaces or open electrical equipment.
- [ ] Charge fully and clean lenses. Check storage with a test scan plus photos
  and leave headroom; Polycam's 2 GB minimum is not a multiroom capacity guarantee.
- [ ] Test a small capture: save, process, export to Files, reopen. Repeat with
  connectivity disabled; record network dependencies. Check capture limits,
  app version, actual model's LiDAR, available mode and privacy/sync settings.
  Avoid last-minute updates unless needed and tested; do not start a paid trial.
- [ ] Keep furniture and appliance dimensions offline, including packed and
  disassembled sizes. Existing 190 cm sofa and 120 cm table candidates also need
  circulation/chair space; supplier dimensions/claims require final verification.
- [ ] Test private backup transfer by cable/storage/private cloud without a
  public link. Keep the app installed and local originals until backup is verified.

## Minimum evidence if time is short

Complete these before long scans or optional lifestyle checks. For each item use
`done`, `not accessible`, or `not applicable`; explain omissions.

- [ ] Connected-room sketch, orientation and room/wall/opening/utility IDs.
- [ ] Delivery route: narrowest clear width/height, turns, lift and destination.
- [ ] Usable furniture walls, fridge/washer spaces, critical opening clearances
  with photos showing measured endpoints.
- [ ] Every room's two main spans, ceiling/low obstructions, wall segments,
  doors/windows, columns/beams/steps.
- [ ] Every wall and utility point photographed and located; appliance connections.
- [ ] Locally saved and inspected evidence, gap list, second private copy if possible.

Flow: permission/sketch → delivery route → room-by-room dimensions/photos →
optional scan → final sweep/file check. Reserve time to retake failed evidence.

## IDs, units and reference frame

Use room `R01`, clockwise wall segments `R01-W01`, door `R01-D01`, window
`R01-N01`, utility `R01-U01`, measurement `M001`, photo `P001`, route `T01`.
Map room names on the private sketch; identify shared openings consistently and
link both rooms. Split walls at recesses and mark each wall's start corner.

Per room choose an accessible floor corner O: +X along the first wall, +Y into
the room perpendicular to X, +Z upwards. Photograph the origin; draw axis arrows
and room origins on the connecting sketch. Separate scans do not share world
coordinates automatically. Mark approximate north and its source, not scan axes.

YAML uses **m**. Paper mm must be explicit and converted once (`800 mm = 0.800 m`).
Record finished-surface endpoints, method, repeat readings, uncertainty and photo
IDs. Distinguish measured/estimated values. `null` means unknown, never zero.
Utility positions: along-wall offset from its named start corner + floor height;
other features: coordinates or wall offsets. Record scan-to-sketch alignment.

## Manual room measurements

| Feature | Capture on site |
|---|---|
| Room shape | Every usable wall segment/recess; two main spans and an accessible diagonal; ceiling height at several points; skirting projections. Repeat at furniture height if geometry changes. Note hidden boundaries. |
| Beam/column/step | Width/depth/location; beam underside and lowest headroom; column footprint; floor level changes and threshold heights. |
| Door | Achievable open position's usable clear width/height, not frame outer size; hinge, swing arc, handle/stop projections, sliding travel/track and threshold. Test movement outside the active scan with permission. |
| Window/curtain | Opening/frame width/height, sill height, offsets from corners, operation/swing; rail usable length/height/wall offset, tracks/brackets and curtain-drop reference. |
| Storage | Clear entrance and usable internal width/depth/height; shelves/rails, door travel, pipes and fixed obstructions. |
| Furniture | Unobstructed wall lengths and available depth; chair pull-out, walking routes, door/drawer opening. Compare bed/desk/piano/shelves/sofa/table. Label personal clearance preferences rather than assuming a universal minimum. |
| Refrigerator | Narrowest usable width/depth/height; skirting/beam; hinge/full opening; model-specific ventilation/service space; socket/earth. |
| Washer | Pan outer AND usable inner width/depth, support heights; drain centre offset/type, tap height/projection, hose path/space above; outlet/earth; lid/door opening and service access. |
| Kitchen/appliances | Counter height, undercounter spaces, hood/cabinet clearance, visible water/drains, appliance positions and sockets. Do not disconnect equipment. |

For **every** socket, switch, LAN/TV outlet, light point and internet terminal:
ID, room/wall, along-wall offset, floor height, count, visible type/label, grounding
and close-up. LAN-shaped sockets do not establish active service. Ask about
provider, termination and construction permission. Sketch desk/router/TV cable
routes and door crossings while preserving walking paths.

Air conditioning: existing unit size/location/height, dedicated socket's visible
voltage label (otherwise unknown), pipe sleeve position/diameter if measurable,
mounting space, drain route, outdoor-unit location and installation permission.
Do not infer electrical capacity or test wiring from photos; unresolved items
go to the agent/installer. Observe water/drains; operate valves only if permitted.

## Delivery: loading point to final position

- [ ] Follow loading area → building entrance → lift/stairs → common corridor →
  unit entrance → hallway → each destination room.
- [ ] At each opening record smallest **clear** width/height, opening limits,
  thresholds, handles, closers, handrails and projections.
- [ ] At bends measure approach/exit widths, clear turning rectangle/landing
  and overhead limits; sketch the corner. One minimum width cannot prove a long
  package will turn.
- [ ] Lift: doorway clear width/height; usable cabin width/depth/height, diagonal
  if useful, capacity label and landing. Alternative stairs: clear width,
  landings, turns and lowest headroom.
- [ ] Ask about reservation, hours, protection, loading restrictions and supplier
  inspection. Do not remove fixtures. Compare packed dimensions, weight and
  possible orientations/turns; supplier confirmation is needed for tight margins.

## Photos and optional scan

- [ ] Per room: doorway overview, each wall straight-on including corners and
  floor/ceiling boundaries, reverse overview, ceiling/beam and floor/step details.
  Add overlapping/diagonal views for connections and large rooms.
- [ ] Per feature: context → close-up → readable scale in the same plane, with
  endpoint notes. Perspective alone does not give reliable dimensions. Retake
  blur/glare/overexposure; do not rely only on ultra-wide shots.
- [ ] Names: `R01_W01_overview_P001.jpg`,
  `R01_D01_clear-width_M001_P002.jpg`. Photo manifest maps original filename to
  photo/feature/measurement IDs, direction and description. Rename copies later
  if needed; retain originals and metadata privately.
- [ ] Photograph open/closed states separately and record the chosen scan state.
  Avoid people/reflections, papers, identifying labels and exterior views. Common
  areas need permission. Do not move doors or objects during a scan.
- [ ] Before leaving each room, check walls/openings/ceiling/floor/storage/utilities/
  appliances against IDs and camera roll; mark any gaps immediately.

| Actual tested equipment | Route |
|---|---|
| LiDAR confirmed; Polycam Space works | Open required doors before starting and keep fixed. Move slowly with even light, include floor-to-ceiling boundaries and connections, check missing surfaces/drift. Short room scans are a fallback for a failed whole-home scan; record their placement separately. |
| No LiDAR; compatible Polycam Space works | Official non-LiDAR Space is currently iOS/device-limited. Use the tested local processing route, textured corners/features and overlapping views. Do not assume identical floor-plan outputs to LiDAR. |
| Unsupported/unknown/export blocked/failure | Smartphone context/detail photos + manual tape dimensions + annotated sketch complete the visit. Video is supplementary with permission. Photogrammetry is optional only if already tested. |

If tracking breaks, note it and recapture a smaller area. Glass/mirrors, blank
walls and hidden edges require manual evidence. Use existing hardware and light
processing; no GPU service or heavy reconstruction is needed at the visit.

## Calibration and fit decisions

Per room measure two independent horizontal spans in different directions and
one height, plus every purchase/delivery-critical clearance. Match exact endpoints
in photos and model. Record scan ID/value, manual value, signed difference
`scan - manual`, and relative difference. Repeat suspicious manual readings.

Keep original models unchanged. Uniform scaling is only a derived option if
reference spans agree; record factor, units, transformation and before/after
checks. Inconsistent spans suggest local distortion/drift: rescan or use manual
geometry. If remaining clearance is comparable to measurement uncertainty,
remeasure and consult the supplier; do not declare a fit. No fixed accuracy is
assumed for scans or AI plans.

## Before leaving: save, reopen, back up

- [ ] All room/feature/route IDs match notes/photos. Essential values have units,
  endpoints, methods and evidence, or explicit missing reasons.
- [ ] Inspect critical photos at full size and models for missing rooms, floor/
  ceiling, broken joins, doubled walls and wrong orientation.
- [ ] Retain native captures/raw data where accessible and unedited photos.
  Export tested GLB if offered, otherwise GLTF with **all** `.bin`/texture
  sidecars/export archive. OBJ needs material/texture files. Point clouds and
  app floor-plan exports are optional only if already entitled; mesh ≠ raw data.
- [ ] Independently reopen export if possible, verify textures/units/axes/scale
  against a reference; reopen notes and sample original photos. Record file names,
  sizes, device/app/version/mode and export status in a private manifest.
- [ ] Second private copy: compare counts/sizes and open samples. If transfer is
  impossible onsite, verify local originals, mark backup pending and copy on return.
  Do not uninstall/reset/delete until verified. Public links are not backups.
- [ ] Ask about revisit/access for gaps; restore doors, lights and objects as agreed.

After return: fill private YAML copies, compare furniture and model-specific
appliance requirements, generate private dimensioned plans/layouts with provenance
and uncertainty. Public templates stay empty. Ask about move-in/internet rules,
musical instruments/noise and visible damp/leaks. One visit's noise/light does
not establish conditions throughout the day.

## Official references

Checked 2026-10-03 JST. Actual device/account tests determine availability; vendor
documentation is not a measurement accuracy guarantee.

- [LiDAR Space](https://learn.poly.cam/hc/en-us/articles/36655587097620-How-to-Use-Space-Mode-with-LiDAR-enabled-devices): preparation and local capture storage; app deletion removes local captures.
- [Non-LiDAR Space](https://learn.poly.cam/hc/en-us/articles/43933482446996-How-to-Use-Space-Mode-Non-LiDAR-Devices): current iOS/device limits and offline on-device processing.
- [Export formats](https://learn.poly.cam/hc/en-us/articles/27756102599572-What-File-Types-Can-Polycam-Export): Free GLTF only; other formats depend on mode/plan. Historical GLB is not proof of current entitlement.
- [Plans](https://poly.cam/pricing): Free lists public link sharing; use local export/private storage without starting a new paid plan.
