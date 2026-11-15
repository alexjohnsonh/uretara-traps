# AT220 Trap Service app – Uretara Island

Offline phone app for servicing the NZ Autotraps AT220 traps on Uretara Island.

## What it does
- **Traps** – list of all 34 traps, distance/direction from you, sort by nearest or "to do first".
- **Locate** – compass arrow + distance to the trap, location notes, set location from phone GPS, Google Maps link (when online).
- **Map** – offline plot of all traps and your position (green = serviced this round).
- **Service** – 8-step wizard: trap → safety/LED → data (NZAT app counts or manual) → battery → lure → sensor eyes → ladder/tags → re-set, comments, photos. No. days is calculated from the last service.
- **Guides** – step-by-step how-tos (safety, reading data, battery, lure, cleaning eyes, debris/mesh, LED lights, re-setting). Add your own photos to each step.
- **Report** – round summary, results table in the same layout as the "AT 220 TRAP SERVICE RESULTS" spreadsheet, catch map, maintenance list. Print/Save PDF, Excel, CSV.
- **Import** – load an updated trap spreadsheet (.xlsx/.csv with trap #, Lat, Long + any location/notes/comments column).
- **Editable text** – guide steps, tips, warnings, photos and service-form wording live in **app-text.xlsx** (see its "How to edit" sheet). Photos/screenshots go in the **images** folder.
- **Backup/restore** – JSON file incl. photos. Data is stored on the phone only.

October 2026 results are preloaded as history. Traps 24–30 and 34 use coordinates from New Traps.kmz.

## Getting it onto phones (needs https for offline mode)
1. Create a GitHub repo (e.g. `nz-auto-traps-app`), upload all files in this folder (including app-text.xlsx and the images folder), then Settings → Pages → deploy from `main`.
2. Open the Pages address on the phone while online.
3. iPhone: Share → Add to Home Screen. Android: ⋮ → Install app.
4. Open from the home-screen icon – works with no signal from then on.

Instructions are based on NZ Autotraps / project guidance – check against the current AT220 user manual.
