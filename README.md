# AI Robotics Engineer — Hardware Inventory

A photo-driven catalog for IoT hardware, Arduino-compatible boards, Raspberry Pi computers, microcontrollers, sensors, actuators, robotics kits, FPGA boards, development tools, and smart-home devices.

## Current inventory snapshot (2026-11-22)

- **49** hardware inventory entries, including kits, enclosures, prototyping equipment and power accessories
- **42** unique photographs inspected and logged (some photos show multiple items; some items appear in multiple photos)
- **43** catalog entries linked to photographs; **6** previously reported items still await photos
- **Next available hardware ID: `HW-0050`**
- **Latest update:** photographed existing Ryze Tello drone with prop guards; added boxed 2.4 GHz wireless microphone kit and ATUVOS Apple Find My trackers

[Batch 001](inventory/batches/2026-11-22-001.md) · [Batch 002](inventory/batches/2026-11-22-002.md) · [Batch 003](inventory/batches/2026-11-22-003.md) · [Batch 004](inventory/batches/2026-11-22-004.md) · [Batch 005](inventory/batches/2026-11-22-005.md) · [Batch 006](inventory/batches/2026-11-22-006.md) · [Batch 007](inventory/batches/2026-11-22-007.md) · [Batch 008](inventory/batches/2026-11-22-008.md)

**Photo-storage note:** All 42 unique JPGs are still conversation attachments; the repository currently stores their descriptive evidence log, not their original image binaries. Do not treat filenames in the log as GitHub-hosted images.

## Inventory

- **[Master inventory](inventory/items.json)** — canonical machine-readable item records (one record per distinct item/lot, with quantity when established).
- **[Inventory summary](inventory/summary.md)** — human-readable index; updated as devices are identified.
- **[Photo intake log](intake/photos.json)** — links each inspected photo to the IDs found in it.
- **[Photo evidence index](photos/manifest.md)** — human-readable index of all 17 image filenames and associated inventory records.
- **[Item data rules](inventory/README.md)** — fields, categories, verification and duplicate handling.
- **[Photo handling guide](photos/README.md)** — evidence, filenames, privacy and photo storage.
- **[Agent instructions](AGENTS.md)** — rules for adding new images and updating the catalog.

## How to inventory items

1. Take a photo and send it in the ChatGPT conversation. A wide shot is fine for mixed lots; close-ups of boards and readable markings improve model identification.
2. The AI identifies visible devices, counts each item, checks for duplicates and assigns persistent IDs such as `HW-0011`. **Uncertain models stay uncertain.**
3. Add/update records in `inventory/items.json`; log the photo in `intake/photos.json`; update `inventory/summary.md`. Keep original photo in `photos/YYYY/MM/` when photo bytes can be committed safely. If not, use a descriptive evidence reference and don't invent a photo URL.
4. Flag missing facts (exact model, board revision, voltage, protocol, condition, storage location). Update those fields only when evidence arrives.

### Confidence / provenance

- `photo_verified`: enough visible evidence to identify the recorded item/model.
- `photo_tentative`: visible item, but model or quantity is uncertain.
- `reported_unverified`: mentioned previously, but not photographed for this catalog.

**Initial state:** the inventory includes a small number of devices previously mentioned in conversation, clearly marked `reported_unverified`. These are **not** counted as photographed or physically audited. Quantities are unknown until established.

## Goals

Build an accurate collection index for future microcontroller, robotics, IoT, FPGA and AI-at-the-edge projects. Later, the same catalog can support project-to-parts matching, inventory searches, and a web dashboard.

## Privacy

This repository is private. Do not commit API keys, Wi-Fi credentials, access tokens, addresses, MAC addresses, or full device serial numbers. Crop/redact sensitive labels if they appear in a photograph. Avoid exposing precise home storage locations.
