# 3D Asset Sources

## Gobkit Nature Kit
- Source: https://gobkit.com/freebies
- Catalogue/API: https://gobkit.com/api/free
- License stated by the publisher: CC0 1.0 Universal
- Use in this project: static low-poly scenery models loaded as GLB files at runtime

Models referenced by `index.html`:
- TreeHigh001: https://gobkit.com/freebies/environment/TreeHigh001.glb
- TreeHigh002: https://gobkit.com/freebies/environment/TreeHigh002.glb
- TreeMed001: https://gobkit.com/freebies/environment/TreeMed001.glb
- Rock001: https://gobkit.com/freebies/environment/Rock001.glb
- Rock002: https://gobkit.com/freebies/environment/Rock002.glb
- Bush001: https://gobkit.com/freebies/environment/Bush001.glb
- Bush002: https://gobkit.com/freebies/environment/Bush002.glb
- Grass001: https://gobkit.com/freebies/environment/Grass001.glb
- Grass002: https://gobkit.com/freebies/environment/Grass002.glb

The publisher states that its free Nature Kit models are CC0 1.0, allowing use, modification, and redistribution without attribution. The game currently loads these models from the publisher's host for this prototype. A future production build should bundle the model files locally so the game does not depend on that host.

If a model request fails, `index.html` creates a simple procedural fallback prop.
