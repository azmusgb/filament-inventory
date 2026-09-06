# Filament Inventory — archived predecessor

> **Superseded repository.** Active Filament Inventory development has moved to `azmusgb/filamentinventory`.
>
> Do not deploy or extend this repository for production use. It is retained only for historical provenance of the original local-only inventory prototype.

## Historical scope

This repository contains the early mobile-first, local-first filament inventory PWA that predated the current multi-profile, cloud-sync, printer/AMS, recovery and grounded-Assistant architecture.

Its original capabilities included:

- conservative starter inventory based on the photo audit;
- brand, material/type, color, spool format, location and confidence;
- visual remaining-% estimates when that was all that was known;
- gross-weight minus tare-weight measurements overriding visual estimates;
- measurement history;
- reorder thresholds;
- opened/bagged storage state;
- purchase metadata;
- search/filtering;
- JSON backup/restore;
- CSV export;
- responsive/offline PWA behavior.

## Historical data behavior

Inventory in this predecessor is stored in browser `localStorage` and does **not** provide the current cross-device/profile-scoped cloud architecture.

## Canonical repositories

Use these repositories instead:

- `azmusgb/filamentinventory` — Filament Inventory PWA, Bill/Aimee profile isolation, cloud sync, device APIs and grounded inventory Assistant.
- `azmusgb/bambuhelper-smart-display` — canonical Waveshare Workshop OS / WS350 firmware, hardware controls, OTA/recovery and physical acceptance.

## Preservation policy

Keep this repository read-only after archival. Do not delete or rewrite its Git history; it remains useful as provenance for the initial product lineage.
