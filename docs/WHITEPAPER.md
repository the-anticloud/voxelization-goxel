# Technical Whitepaper — GOXEL

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/guillaumechereau/goxel
**Category:** VOXELIZATION

## Abstract

This whitepaper describes the Anticloud integration of `GOXEL` (Open-source 3D voxel editor)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local 3D scene understanding from voxel grids
2. AIOSS provenance chain for all 3D scan and reconstruction data
3. AES-256 encryption for proprietary 3D models and point clouds
4. Single-binary voxelization tool with no cloud dependency
5. Zero-cloud: all meshing, analysis, and AI inference run locally
6. GPU/CPU equalizer: CUDA voxelization on GPU, CPU fallback for deployment
7. Open point cloud format: LAS/LAZ/PLY export without proprietary lock-in
8. Offline coordinate system and georeference support

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.