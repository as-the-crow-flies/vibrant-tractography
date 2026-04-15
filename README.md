# VIBRANT Tractography

🪩 Render your tracrography, vibrantly 🪩

---

![Big Segmented Tractogram, rendered vibrantly](cover.png)

[➡️ Click to run the Web Demo ⬅️](https://as-the-crow-flies.github.io/vibrant-tractography/) ([Ensure your Browser supports WebGPU](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status))

## Feature highlights

- 🎥 Renders Tractograms using Ray Tracing
- 😎 Renders Ambient Occlusion and Soft Shadows using Voxel Cone Tracing
- 🫥 Renders correct Transparency
- 🗃️ Supports loading one or more MRtrix .tck files at a time

## How to run natively

Running the app natively generally gives better performance than the Web. Building the source on your device only takes two steps:

1. Ensure you have the Rust toolchain installed on your system using https://rustup.rs/
2. Build and Run using `cargo run`

## Citing this repository

If you use this software in your work, please cite the article:

APA
```
Kraaijeveld, B., Jalba, A. C., Vilanova, A., & Chamberland, M. (2026). Real‐Time Rendering of Dynamic Line Sets using Voxel Ray Tracing. Computer Graphics Forum, e70372. https://doi.org/10.1111/cgf.70372
```

BibTeX
```
@article{https://doi.org/10.1111/cgf.70372,
author = {Kraaijeveld, B. and Jalba, A.C. and Vilanova, A. and Chamberland, M.},
title = {Real-Time Rendering of Dynamic Line Sets using Voxel Ray Tracing},
journal = {Computer Graphics Forum},
volume = {n/a},
number = {n/a},
pages = {e70372},
doi = {https://doi.org/10.1111/cgf.70372},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.70372},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.70372}
}
```

## Issues

If you are experiencing any issues, please file an [issue on GitHub](https://github.com/as-the-crow-flies/vibrant-tractography/issues). Please note this is experimental software.
