# Awesome-3D-Gaussian-Splatting-Spatial-Computing
# Awesome-3D-Gaussian-Splatting-Spatial-Computing

# Top 3D Gaussian Splatting & Spatial Computing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Real-Time Radiance Fields, 3DGS Training & WebGPU/WebGL Viewers, Spatial Intelligence & Photorealistic Capture*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Gaussian Splatting & Spatial Computing**. These tools capture photorealistic 3D scenes from video or LiDAR, train and compress Gaussian splats locally or in the cloud, edit point-based radiance fields, and render real-time spatial computing worlds in browsers, XR headsets, and game engines.

**Examples** include Luma AI, Polycam, Jawset Postshot, KIRI Engine, Scaniverse, Gracia AI, Spline, Nerfstudio, SuperSplat, and bilawalsidhu/gods-eye-view (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for local 3DGS training across CUDA/Metal/WebGPU, browser-based splat editors, spatial intelligence globes, 2D/4D Gaussian Splatting, and Unreal/Unity/Blender/Three.js runtimes — ideal for spatial computing engineers, VFX artists, computer vision researchers, and WebXR developers building vendor-free pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Luma AI (Luma Capture & Genie)](https://lumalabs.ai)**  
  Cloud AI platform for capturing photorealistic 3D Gaussian Splats from smartphone videos, generating 3D assets from text, and embedding interactive WebGL radiance fields.

- **[Polycam](https://poly.cam)**  
  Cross-platform mobile and web 3D scanning suite supporting cloud 3D Gaussian Splatting, LiDAR capture, photogrammetry, and browser-based splat sharing.

- **[Jawset Postshot](https://www.jawset.com/)**  
  High-speed local desktop 3D Gaussian Splatting and radiance field reconstruction software featuring live training previews, ACES color pipelines, and Unreal Engine / After Effects plugins.

- **[KIRI Engine](https://kiriengine.app)**  
  Cloud 3D scanning and Gaussian Splatting platform offering mobile capture, splat-to-mesh conversion, quad-retopology, and official Blender add-on integration.

- **[Niantic Scaniverse](https://scaniverse.com)**  
  Mobile spatial scanning app capable of on-device 3D Gaussian Splatting capture, editing, and geospatial world mapping without requiring cloud uploads.

- **[Gracia AI](https://gracia.ai)**  
  Spatial computing platform for publishing, streaming, and experiencing photorealistic 6DoF volumetric 3D Gaussian Splatting scenes across VR headsets, desktop, and web.

- **[Spline (3DGS Support)](https://spline.design)**  
  Collaborative browser-based 3D design studio supporting imported 3D Gaussian Splats alongside interactive lighting, physics, and embeddable web showrooms.

- **[Arrival.Space](https://arrival.space)**  
  Cloud spatial computing and virtual showroom platform designed for hosting, decorating, and walking through photorealistic 3D Gaussian Splatting environments in browsers.

- **[StorySplat / SplatCloud](https://storysplat.com)**  
  Cloud hosting and interactive storytelling builder for creating guided camera tours, audio hotspots, and embedded web presentations from `.ply` and `.splat` files.


## Open-Source GitHub Projects

- **[Nerfstudio](https://github.com)**  
  Modular open-source (`Apache-2.0`) PyTorch framework unifying 3D Gaussian Splatting (`splatfacto`), NeRFs, COLMAP/GLOMAP pose estimation, and a real-time web viewer.

- **[gsplat (Nerfstudio)](https://github.com/nerfstudio-project/gsplat)**  
  High-performance open-source (`Apache-2.0`) CUDA-accelerated differentiable rasterization library for 3DGS with up to 4x lower memory usage, LiDAR modes, and multi-GPU scaling.

- **[SuperSplat (PlayCanvas)](https://github.com/playcanvas/supersplat)**  
  Free and open-source (`MIT`) browser-based 3D Gaussian Splatting editor and optimizer for cropping, cleaning floaters, compressing (`.compressed.ply` / `.sog`), and publishing splats.

- **[Brush (ArthurBrussee/brush)](https://github.com/ArthurBrussee/brush)**  
  Cross-platform open-source (`Apache-2.0`) 3DGS training and rendering engine built in Rust with Burn and WebGPU—running natively on NVIDIA, AMD, Intel, Apple Silicon, Android, and browsers.

- **[LichtFeld Studio](https://github.com)**  
  Modular open-source (`GPL-3.0`) C++/CUDA native workstation for 3D Gaussian Splatting enabling local training, real-time inspection, editing, automation, and export in one app.

- **[bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view)**  
  Open-source (`MIT`) browser-based spatial intelligence and photorealistic 3D globe simulator built on CesiumJS with live aircraft, satellite, seismic, and OSINT telemetry feeds.

- **[Original 3D Gaussian Splatting (`graphdeco-inria`)](https://github.com)**  
  Reference SIGGRAPH 2023 open-source CUDA implementation for real-time radiance field rendering, accompanied by SIBR real-time interactive viewers.

- **[OpenSplat](https://github.com)**  
  Free and open-source (`AGPL-3.0`) C++ implementation of 3D Gaussian Splatting supporting NVIDIA CUDA, Apple Silicon Metal, AMD ROCm, and CPU execution without Python dependencies.

- **[GaussianSplats3D (`mkkellogg`)](https://github.com)**  
  Popular open-source (`MIT`) Three.js-based WebGL implementation and progressive streaming viewer for rendering 3D Gaussian Splats inside custom web applications.

- **[Spark (World Labs)](https://github.com)**  
  Advanced open-source (`MIT`) WebGL2 3D Gaussian Splatting renderer deeply integrated with Three.js for high-performance spatial scenes, shaders, and WebXR experiences.

- **[2D Gaussian Splatting (`hbb1/2d-gaussian-splatting`)](https://github.com)**  
  SIGGRAPH 2024 open-source (`MIT`) extension representing 3D scenes with geometrically accurate 2D oriented planar disks for clean mesh extraction and surface reconstruction.

- **[4D Gaussian Splatting (`hustvl/4DGaussians`)](https://github.com)**  
  CVPR 2024 open-source (`MIT`) dynamic scene reconstruction framework extending 3DGS with spatial-temporal HexPlane deformation fields for real-time volumetric video.

- **[Luma WebGL Library (`luma-web`)](https://github.com)**  
  Official open-source (`MIT`) Three.js library from Luma AI for rendering interactive Gaussian Splats with lighting integration, fog, and custom GLSL shaders.

- **[UnityGaussianSplatting (`aras-p`)](https://github.com)**  
  Widely adopted open-source (`MIT`) Unity package for importing, editing, compressing, and rendering 3D Gaussian Splatting assets in real time inside Unity.

- **[XV3DGS / Unreal Gaussian Splatting Plugins](https://github.com)**  
  Open-source Unreal Engine 5 plugin ecosystem for importing, relighting, and rendering 3D Gaussian Splats in virtual production and spatial computing worlds.

### Additional Strong Open-Source Options

- **[COLMAP](https://github.com)** and **[GLOMAP](https://github.com)** for open-source Structure-from-Motion (SfM) and ultra-fast global camera pose estimation prior to 3DGS training.
- **[DUSt3R](https://github.com)** and **[MASt3R](https://github.com)** for pose-free dense 3D pointmap reconstruction from uncalibrated image pairs.
- **[3DGS.cpp](https://github.com)** and **[MetalSplat](https://github.com)** / **[Splat Local](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)** for lightweight native C++ and Apple Silicon Metal 3DGS training pipelines.
- **[SuperSplat Viewer](https://github.com/playcanvas/supersplat-viewer)** and **[Antimatter15/splat](https://github.com)** for zero-dependency WebGL/WebGPU splat embedding with stochastic depth-tested XR rendering.
- **[MrNeRF/awesome-3D-gaussian-splatting](https://github.com/MrNeRF/awesome-3D-gaussian-splatting)** and **[ishandutta2007/Awesome-Gaussian-Splatting](https://github.com/ishandutta2007/Awesome-Gaussian-Splatting)** for comprehensive research paper indexes and specialized 3DGS forks.

**Frameworks for building custom systems**: Combine **GLOMAP** + **Nerfstudio (`gsplat`)** or **Brush** with **SuperSplat** (for cleanup & `.sog` compression) and **Spark / GaussianSplats3D** (for Three.js & WebXR deployment) for end-to-end open-source spatial computing pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Training 3D Gaussian Splatting models locally requires significant VRAM (CUDA, ROCm, Metal, or WebGPU) and calibrated camera poses (via COLMAP/GLOMAP or SfM-free predictors).
- Verify license compatibility (`MIT`, `Apache-2.0`, `GPL-3.0`, `AGPL-3.0`, or non-commercial research weights) before deploying capture tools or viewers in commercial spatial computing products.

---

**Made for spatial computing engineers, 3D capture artists, computer vision researchers, and WebXR developers.**  
Let's make 3D Gaussian Splatting and spatial intelligence more open, real-time, and accessible.
