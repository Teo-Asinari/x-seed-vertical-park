# Concept art

Renders, 3D models, sketches, and other visual material for the X-Seed Vertical Park. Anything that helps a reader picture the structure belongs here.

## In this directory

- `generate_silhouette.py` — stdlib-only Python script that emits a Wavefront `.obj` of the basic X-Seed silhouette (truncated cone on a thick cylindrical sea-base disc). Parameters are at the top of the file.
- `x-seed-silhouette.obj` — the output of running the script with default parameters. Lightweight massing model, suitable for quick reference renders or as a starting block in a sculpting tool.

Run `python3 generate_silhouette.py` to regenerate the `.obj` after changing parameters.

## Existing community models

Third-party models of the original Taisei proposal that may be useful as reference. License terms vary — check each before redistributing.

- [Sketchfab — X-Seed 4000 Tower 3D](https://sketchfab.com/3d-models/x-seed-4000-tower-3d-2756c2b0185a414083c2cd64379b3840)
- [3D Warehouse — X-SEED 4000](https://3dwarehouse.sketchup.com/model/6da683be-b793-4cea-8919-1b7c5957c20d/X-SEED-4000?hl=en)
- [3D Warehouse — X-Seed 4000 (updated)](https://embed-3dwarehouse-classic.sketchup.com/model/041ce397-8dd3-4c94-8a9f-b966f13b7a99/X-Seed-4000-updated)
- [STLFinder — X-Seed 4000 search](https://www.stlfinder.com/3dmodels/x-seed-4000/)

## Contributing art

If you want to contribute, keep files reasonably small (compress renders, decimate heavy meshes), include a short note on what the piece depicts, and confirm the license is compatible with the repository's CC-BY-4.0.
