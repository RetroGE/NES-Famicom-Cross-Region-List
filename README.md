# NES ↔ Famicom — Cross‑Region List (GitHub Pages Pack — Full, with Variants)

This package contains everything you need to update your site:
- `index.html` — mobile-friendly app with light/dark theme, column toggles, and "download filtered CSV".
- `/data/nes_famicom_cross_region_verified_TIGHT_A_to_Z_PLUS_VARIANTS.csv` — default dataset (tight‑verified + FamicomBox + Variant Type).
- `/data/first_party_block_A_mappers.csv` — Nintendo canonical block with mappers/HVC/FDS + save methods.
- `/data/first_party_block_B_mappers_WIP.csv` — early black‑box set (mappers/HVC TBD).
- `/data/jp_only_variants_ann_mario_etc.csv` — JP‑only variants (All Night Nippon SMB, SMB2J, Kaettekita Mario Bros., Clu Clu Land D).

## Update steps
1. Unzip this folder into your repo root (replace existing `index.html` and `/data` files).
2. Commit and push to your GitHub repository.
3. In **Settings → Pages**, ensure Source = your branch, Folder = `/ (root)`.
4. Open your Pages URL. Use `?csv=jp_only_variants_ann_mario_etc.csv` to view the JP‑only variants dataset.

## Notes
- **Variant Type** examples: “Rebrand / Asset swap”, “Theme swap”, “Remix (engine reuse + level edits)”, “Update (FDS exclusive)”, “Retitle (license)”, etc.
- Your preferences persist locally: theme (`nfc_theme`) and columns (`nfc_columns_v1`). 
- Use the **⬇️ Download filtered** button to export whatever you’re currently viewing.

**Build stamp:** 20250813_010352 UTC
