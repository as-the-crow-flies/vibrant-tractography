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

If you use this software in your work, please cite the arXiv article:

APA
```
Kraaijeveld, B., Jalba, A. C., Vilanova, A., & Chamberland, M. (2025). Real-Time Rendering of Dynamic Line Sets using Voxel Ray Tracing. arXiv preprint arXiv:2510.09081. https://doi.org/10.48550/arXiv.2510.09081
```

BibTeX
```
@article{Kraaijeveld2025RealTimeRendering,
  author = {Kraaijeveld, Bram and Jalba, Andrei C. and Vilanova, Anna and Chamberland, Maxime},
  doi = {10.48550/arXiv.2510.09081},
  journal = {arXiv preprint arXiv:2510.09081},
  title = {{Real-Time Rendering of Dynamic Line Sets using Voxel Ray Tracing}},
  url = {https://arxiv.org/abs/2510.09081},
  year = {2025}
}
```

## Issues

If you are experiencing any issues, please file an [issue on GitHub](https://github.com/as-the-crow-flies/vibrant-tractography/issues). Please note this is experimental software.
