# Hardware inventory — 2026-11-22

## Inventory counts

- **Total records:** 17 distinct item/lot records (assemblies and boxed kits are counted once)
- **Records linked to at least one photo:** 9
- **Photo-verified visible device or owner-confirmed hardware type:** 5
- **Photo-supported but only retail packaging seen:** 4
- **Previously reported, no photo yet:** 8
- **Photo intake records:** 9

**Interpretation:** A retail box establishes the packaging/product label, not proof the box is complete or a device has been tested. For HW-0001, the owner specifically checked that the Raspberry Pi 4 board is inside; the other boxes remain unchecked. No claim is made that any pictured electronic device is working.

## Latest photo batch — 002

| ID | Item | Evidence | Scope |
| --- | --- | --- | --- |
| HW-0006 | Google AIY Vision Kit | Retail box; claims Raspberry Pi included | Package only |
| HW-0014 | Intel Neural Compute Stick 2 | Retail box; Movidius Myriad X | Package only |
| HW-0001 | Raspberry Pi 4 Model B, 2 GB RAM | Element14 retail box; owner checked board is inside | Board presence owner-confirmed; board unphotographed |
| HW-0015 | LCD electronic component / transistor tester | Device visible; blue ZIF socket, display and acrylic enclosure | Device photographed |
| HW-0016 | Retroflag SUPERPi CASE retro-gaming system | Case visible; owner tentatively identifies internal Pi 3 Model B, 1 GB RAM | Case photographed; Pi 3B model not visually verified |
| HW-0017 | NXP Rapid IoT Prototyping Kit | Retail box | Package only |

**Deduplication:** HW-0001 and HW-0006 were already in the inventory; those entries were enriched instead of creating duplicates. The Raspberry Pi mentioned on the AIY Vision Kit package is a component of that kit, **not** counted as a separate owned Raspberry Pi.

**SUPERPi CASE:** Owner believes the installed board is a **Raspberry Pi 3 Model B, 1 GB RAM**, configured for retro gaming (correcting an earlier '2G' recollection). The **Model B** identification remains tentative until the board markings or OS-reported model are checked; only the enclosure is photographed. [Pi 3 B](https://www.raspberrypi.com/products/raspberry-pi-3-model-b/) · [Pi 3 B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/).

[Detailed batch 002 notes](batches/2026-11-22-002.md) · [Full photo log](../intake/photos.json)

## Earlier photo batch — 001

| ID | Item | Status |
| --- | --- | --- |
| HW-0011 | 4WD acrylic robot car chassis kit | Photo/owner-confirmed |
| HW-0012 | Quartz analog clock movement with hands | Photo/owner-confirmed |
| HW-0013 | Conductive tape for paper circuits | Photo/owner-confirmed |

[Detailed batch 001 notes](batches/2026-11-22-001.md)

## Previously reported, awaiting photos

| ID | Item | Status |
| --- | --- | --- |
| HW-0002 | Raspberry Pi 5 | Awaiting photograph |
| HW-0003 | Coral USB Accelerator | Awaiting photograph |
| HW-0004 | Kria KV260 Vision AI Starter Kit | Awaiting photograph |
| HW-0005 | AIY Voice Kit | Awaiting photograph |
| HW-0007 | Tello drone | Awaiting photograph |
| HW-0008 | Flight joystick | Awaiting photograph |
| HW-0009 | Nest doorbell | Awaiting photograph |
| HW-0010 | Nest Wi-Fi camera | Awaiting photograph |

## Data and asset handling

Canonical source of truth: [items.json](items.json). Photographs have been inspected in conversation but **original image bytes are not yet stored in the GitHub repository**; see [photos.json](../intake/photos.json) for image filename references and batch mappings. Quantity is recorded as 1 for each visibly present box/device/assembly; unverified accessory counts and standalone component ownership are not inferred.
