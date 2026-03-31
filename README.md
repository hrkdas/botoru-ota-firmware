# botoru-firmware

OTA manifests are published per bottle variant:

- `manifest/boturo_cue/stable.json`
- `manifest/boturo_go/stable.json`
- `manifest/boturo_kids_routine/stable.json`
- `manifest/boturo_smart_auto/stable.json`
- `manifest/boturo_pill/stable.json`
- `manifest/boturo_baby/stable.json`
- `manifest/boturo_pro/stable.json`

During the migration window, Cue also keeps the legacy manifest at:

- `manifest/stable.json`

Release conventions:

- Preferred tag format: `boturo_<variant>-vX.Y.Z`
- Preferred asset format: `firmware_boturo_<variant>_vX.Y.Z.bin`
- Transitional Cue-only legacy format is still supported:
  - tag: `vX.Y.Z`
  - asset: `firmware_vX.Y.Z.bin`
