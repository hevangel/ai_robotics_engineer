# Agent instructions — photo-to-inventory

This project maintains a **physical hardware inventory** from photographs and user reports.

## Required actions for each incoming photo

1. Inspect all visible hardware in the photo, including accessories. Don't claim to see hidden components.
2. Determine visible count per identifiable model/item. If objects overlap or the count cannot be determined, say so and leave quantity unknown.
3. Look for evidence such as silkscreen, manufacturer logo, connectors, chip markings, board shape, revision, FCC/model identifiers, and packaging. Ask for a close-up only when an important ambiguity cannot be resolved from the photo.
4. Search `inventory/items.json` first to prevent duplicates. A new picture of an existing device should enrich its current entry, not create a duplicate. When unsure whether the device is the same physical unit, keep identity unresolved.
5. Assign stable sequential `HW-####` IDs only to new records, never recycle old IDs. Keep categories consistent and distinguish board, module, kit and accessory.
6. Add a unique photo ID `P-YYYYMMDD-###` to `intake/photos.json` for each photo; set `captured_on` to null unless known, `processed_on` to the date actually processed, and list corresponding hardware IDs.
7. Record `verification_status` as `photo_verified`, `photo_tentative`, or `reported_unverified`. Use `identification_confidence` of `high`, `medium`, `low`, or `not_assessed`. Confidence refers to the *model identification*, not inferred working condition.
8. Fill missing details with null or an empty array, rather than guess. Do not infer a working condition, quantity, model revision or location without evidence.
9. Put actual photos in `photos/YYYY/MM/` when available as safe binary attachments; otherwise use a local conversation/photo reference and mark the asset as `not_stored`. Never create fake image links.
10. Update `inventory/summary.md` from the current JSON, and commit the changes to the repo. Report additions, updates, uncertain items and any upload limitations.

## Canonical data

- `inventory/items.json` is source of truth. The summary is derived text and should not conflict with it.
- `intake/photos.json` is a photo-to-item evidence log. One photo may show multiple IDs; an item may appear in multiple photos.
- For multiple identical boards, a single record with `quantity` is acceptable if individual unit identity is unnecessary; split units if serials, condition, or storage locations matter. Do not store full serial numbers.
- `source.type` distinguishes `photo`, `prior_conversation`, and `user_report`. Prior reports are leads, not verified ownership counts.
- Remove no entry solely because it wasn't present in a later photo. Use clear status/notes for donated, sold, lost or disposed items if the owner confirms.

## Safety

Never copy secrets or personal identifying numbers from images into GitHub. Be careful with batteries and damaged electronics: don't assert something is safe to power without inspection.
