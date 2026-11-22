# Photo intake log

The canonical photo-to-item mapping lives in [photos.json](photos.json).

Each photo record uses:
- `id`: unique `P-YYYYMMDD-###` (intake processing date and counter)
- `captured_on`: date actually taken, or null
- `processed_on`: date inspected
- `file`: repository-relative image path when present; otherwise null
- `asset_status`: `stored` or `not_stored`
- `source_description`: short description of which image/lot was inspected
- `item_ids`: IDs of items identified or possibly identified
- `notes`: image-quality limits, unclear counts, requested close-ups

Record **every** photo, even a blurry one, if it contains possible inventory evidence. An empty `item_ids` list is valid. A photo is not evidence of an item that is not actually visible.
