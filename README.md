Evidence for tangency-labs/solidcraft#12311 (GLB export, #1553). Not for merging.

- `demo.json`: the CLI script that builds the demo design.
- `demo.glb`: `solidcraft-cli run demo.json --out demo.glb`.
- `demo-validator-report.json`: Khronos glTF-Validator 2.0.0-dev.3.10 on `demo.glb`.
- `demo-solidcraft.png`: `solidcraft-cli snapshot demo.json --view iso`.
- `demo-blender.png`: `demo.glb` imported into Blender 5.2.1 and rendered with Eevee.
