# Voyager demo

Smithsonian Voyager Explorer showing two phytolith meshes (Strömberg lab, UW), served from GitHub Pages
exactly as in https://dpo.si.edu/blog/hosting-your-own-interactive-3d-web-experiences-smithsonian-voyager-platform :
one `<voyager-explorer>` element pointing at a folder with a scene document and the mesh.

- https://muratmaga.github.io/voyager-demo/ — Aira caryophylla (scene document: full tool set)
- https://muratmaga.github.io/voyager-demo/anomochloa.html — Anomochloa marantoidea (scene document)
- https://muratmaga.github.io/voyager-demo/geometry.html — Aira via the bare `geometry=` attribute (no scene document, fewer tools)
- https://muratmaga.github.io/voyager-demo/official.html — the Smithsonian's own example scene, as a control

The scene documents were adapted from the blog's shuttle example: same camera and lights, one
`Geometry` derivative pointing at the PLY. Units are declared as mm because Voyager has no
micrometre unit; the coordinates are micrometres.
