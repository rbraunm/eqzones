# eqzones

EverQuest zone work files: only what a 3D environment artist would save. No code and no Claude config; binaries follow the LFS rules in `.gitattributes`.

| Path | Holds |
|---|---|
| `zones/<zoneName>/<zoneName>.blend` | Zone work file |
| `zones/<zoneName>/textures/` | Zone-only textures, on paths relative to the .blend |
| `library/kits/<kitName>.blend` | Kit libraries of marked assets, linked into zones |
| `library/textures/<textureName>/` | Shared textures: `diffuse.png`, `normal.png`, `source.txt` (CC0 attribution) |
| `ref/<zoneName>/concept/` | Concept art |
| `ref/<zoneName>/screenshots/` | Reference screenshots |
| `ref/common/` | References shared across zones |

Textures are always separate files on relative paths, never packed into a .blend.
