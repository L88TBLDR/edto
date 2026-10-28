# EDTO Mind Map (A320)

Offline-capable study app for Scoot A320/A321 EDTO: OM-A 12.23 paragraph by paragraph, FCOM PRO-SPO-40, a phase-of-flight timeline and a tickable checklist.

Built from the operator manuals in the author's command-prep project (OM-A I3R7, FCOM 26 MAY 26, FCOM1A I4R1). Every leaf cites its paragraph. Personal study aid; the manuals remain the authority.

## Use
- Open https://l88tbldr.github.io/edto/ once while online, then "Add to Home Screen" (iOS Safari: Share → Add to Home Screen; Android Chrome: Install app). After that it opens offline.
- Tabs: **Map** (mind map, filter, jump links with Back), **Timeline** (what to do at which phase), **Checklist** (tick per phase; saved on the device; Reset all before the next sector).

## Update
Edit `index.html`, then bump `CACHE` in `sw.js` (e.g. `edto-v2`) so installed copies refresh.
