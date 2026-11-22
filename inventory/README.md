# Inventory data dictionary

**Source of truth:** [items.json](items.json). Each object is one hardware item or lot; `id` is a stable `HW-####` identifier.

| Field | Meaning |
| --- | --- |
| `id` | Permanent ID; never reuse |
| `category` | Machine-friendly hardware family |
| `name`, `manufacturer`, `model`, `variant` | Identification; null when unknown |
| `quantity` | Number of physical units, or null if not established |
| `condition` | `unknown`, `working`, `untested`, `needs_repair`, `not_working` |
| `location` | Optional coarse storage location; avoid addresses |
| `verification_status` | `reported_unverified`, `photo_tentative`, `photo_verified` |
| `identification_confidence` | `not_assessed`, `low`, `medium`, `high` |
| `photo_ids` | Photo log IDs supporting the item |
| `connectivity`, `interfaces`, `accessories` | Optional arrays of confirmed attributes |
| `notes` | Distinctions, open questions, evidence, no guessed specs |
| `source` | Object describing the last/initial evidence type and reference |
| `updated_on` | Date record was last changed (YYYY-MM-DD) |

Suggested category values include `single_board_computer`, `microcontroller_board`, `sensor`, `actuator`, `robotics_drone`, `robotics_platform`, `ai_accelerator`, `fpga_development_board`, `electronics_kit`, `wireless_module`, `power`, `controller`, `smart_home`, `camera`, `tool`, and `accessory`.

An item that appears in several photos still has a single ID. Multiple identical loose devices may be one row with a confirmed quantity; unique or differently configured devices should be separate entries. The presence of a board does **not** establish that it works.
