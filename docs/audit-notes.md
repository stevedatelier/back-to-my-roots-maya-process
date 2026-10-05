# Audit and selection notes

[Back to the case study](../README.md)

## Scope

The confirmed set contains House of Fireborn, Back to My Roots, and Organic Humanoid Head / MetalMask. Palm is excluded at the ownerâ€™s request. The two head pages describe overlapping material and are represented by one repository.

The audit recursively covered the supplied Fireborn process folder, chair screenshots, every folder in `playblast_files_folders_links.txt`, the project pages and their local asset folders. Review included movie metadata and sampled frames, numbered-sequence detection, sample comparisons with existing videos, and inspection of process screenshots.

## Evidence and exclusions

- The separate `REEL01_Knitting / SC030` branch contains cloth camera experiments, Vellum captures and six AVI files. It was audited, but no reliable attribution to these four projects was established; its footage is excluded from their narratives. This includes 425 MiB AVIs and numerous similar camera paths.
- Automata is outside the confirmed scope. Sparse numbered hero stills and separate clay viewpoints are not treated as animation.
- Repeated movie copies were identified by SHA-256. The Fireborn collection duplicates nine movies in the linked R&D directories; each selected movie is included once.
- The charcoal JPG batch matches its 93-frame AVI. The coating JPG batch matches its 136-frame movie. Existing movies were used, with delivery compression, rather than rebuilding these sequences.
- The incomplete `Viscosity_By_8.avi` cannot be decoded. Its numbered `.pic` batch was recoverable through Houdini `iconvert` and is included in the head repository.
- Movie frame rates are preserved. 24 fps is the documented review assumption for newly encoded image sequences, based on adjacent playblasts. No scene FPS was recovered directly.
- Masters, Houdini scenes and caches remain in their original locations. This repository is a process-media case study, not a reproducible simulation project.

## New sequence encodes

| Review | Original batch | Frames | FPS |
|---|---|---:|---:|

No animation sequence was found in the chair folder. The two review MP4s are labeled comparisons assembled from selected stills at two seconds per image. The GIF previews show the opening eight seconds; the MP4s contain all selected views.

## Delivery

H.264, yuv420p, fast-start MP4; source aspect ratio retained, up to 1920 Ã— 1080. Images are web delivery copies, resized only above 2800 pixels; larger PNGs in the head, chair and Palm archives use high-quality WebP compression. Most GIFs are 640 pixels wide; the noisy HQ transformation preview uses 480 pixels and 8 fps. Compression settings and file checksums are recorded in the manifest.

## Larger source files

| Source | Original | Delivery |
|---|---:|---:|
