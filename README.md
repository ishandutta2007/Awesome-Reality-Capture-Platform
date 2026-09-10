# Awesome-Reality-Capture-Platform

Markdown
Copy
Copied
## Top Reality Capture Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on 360° Capture, Photogrammetry, 3D Reconstruction, Point Clouds, Digital Twins, Drone Mapping & Site Documentation*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Reality Capture**. These tools turn photos, 360° imagery, laser scans, and drone data into accurate 3D models, point clouds, orthomosaics, digital twins, and progress documentation for construction, architecture, surveying, and industrial use.

**Examples** include OpenSpace, Matterport, DroneDeploy, Reconstruct, HoloBuilder, Cupix, NavVis, GeoSLAM, Pix4D, and OpenDroneMap Cloud (the category leaders).

**Open-source emphasis**: Reality capture has an exceptionally strong open-source ecosystem. **OpenDroneMap / WebODM**, **COLMAP**, **Meshroom (AliceVision)**, **OpenSfM**, **MicMac**, **openMVG + openMVS**, and related tools provide production-capable photogrammetry and 3D reconstruction pipelines. This section is heavily expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[OpenSpace](https://www.openspace.ai/)**  
  Leading construction reality-capture platform focused on 360° walkthroughs, progress tracking, and AI-powered site documentation.

- **[Matterport](https://matterport.com/)**  
  Popular 3D capture and digital-twin platform for spaces, with high-quality textured models, virtual tours, and property documentation.

- **[DroneDeploy](https://www.dronedeploy.com/)**  
  Comprehensive drone mapping and reality-capture platform producing orthomosaics, point clouds, 3D models, and site analytics, with autonomous flight support.

- **[Reconstruct](https://www.reconstructinc.com/)**  
  Reality-capture and progress-tracking solution aimed at construction teams needing accurate as-built documentation and comparison against plans.

- **[HoloBuilder](https://www.holobuilder.com/)**  
  360° reality-capture and construction progress platform for site documentation and remote collaboration.

- **[Cupix](https://www.cupix.com/)**  
  3D reality-capture and digital-twin platform for construction and facility documentation from photos and 360 imagery.

- **[NavVis](https://www.navvis.com/)**  
  High-accuracy indoor mobile mapping and reality-capture solutions producing detailed point clouds and digital twins of buildings.

- **[GeoSLAM](https://geoslam.com/)**  
  Handheld and mobile LiDAR scanning systems and software for rapid indoor/outdoor point-cloud capture and processing.

- **[Pix4D](https://www.pix4d.com/)**  
  Professional photogrammetry suite for drone and terrestrial imagery, generating accurate maps, point clouds, and 3D models.

- **[OpenDroneMap Cloud](https://www.opendronemap.org/)**  
  Hosted/cloud offering built on the open-source OpenDroneMap toolkit for processing drone imagery into maps and 3D models.

- **[Other reality-capture platforms](https://www.openspace.ai/)**  
  Additional commercial solutions covering terrestrial laser scanning, mobile mapping, and construction digital twins.

## Open-Source GitHub Projects

- **[OpenDroneMap (ODM) / WebODM](https://github.com/OpenDroneMap/ODM)**  
  Leading open-source toolkit for processing drone, aerial, or terrestrial imagery into orthomosaics, point clouds, 3D models, and digital elevation models. Fully self-hostable via command line or the WebODM web interface.

- **[COLMAP](https://github.com/colmap/colmap)**  
  State-of-the-art open-source Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline. Research-grade accuracy for camera pose estimation and dense 3D reconstruction from unordered photos.

- **[Meshroom (AliceVision)](https://github.com/alicevision/meshroom)**  
  User-friendly, node-based open-source 3D reconstruction software built on the AliceVision photogrammetry framework. Excellent GUI for turning image sets into textured meshes.

- **[OpenSfM](https://github.com/OpenSfM/OpenSfM)**  
  Open-source Structure-from-Motion library (Python + C++) used as a core component in OpenDroneMap. Supports sparse reconstruction, dense clouds, meshes, and georeferenced outputs.

- **[MicMac](https://github.com/micmacIGN/micmac)**  
  Powerful free open-source photogrammetric suite from IGN (France) for high-precision 3D reconstruction from photographs in professional and academic settings.

- **[openMVG + openMVS](https://github.com/openMVG/openMVG)**  
  Modular open-source Multiple View Geometry library (openMVG) paired with open Multi-View Stereo (openMVS) for complete photogrammetry pipelines from sparse to dense reconstruction and texturing.

- **[Other photogrammetry & SfM tools](https://github.com/awesome-photogrammetry/awesome-photogrammetry)**  
  Additional active projects including MVE, Bundler descendants, and specialized reconstruction pipelines.

- **[Point-cloud & mesh processing](https://github.com/search?q=Open3D+OR+CloudCompare+OR+MeshLab)**  
  Open libraries and applications (Open3D, CloudCompare, MeshLab) for cleaning, meshing, texturing, and analyzing captured point clouds and models.

### Additional Strong Open-Source Options

- **Drone mapping pipelines**: Full OpenDroneMap / WebODM workflows for aerial reality capture.
- **Gaussian Splatting & NeRF tools**: Community projects for neural radiance fields and Gaussian splats from reality-capture imagery.
- **SLAM & mobile mapping**: Open SLAM libraries that support handheld or backpack reality-capture workflows.
- **Georeferencing & GIS tools**: OpenSfM geo pipelines, GDAL, and QGIS for accurate coordinate systems and orthophotos.
- **Mesh texturing & refinement**: AliceVision components and openMVS for high-quality textured outputs.
- Integration examples connecting COLMAP/Meshroom/OpenDroneMap outputs to web viewers or digital-twin platforms.

**Frameworks for building custom systems**:  
The strongest open-source reality-capture path is **OpenDroneMap / WebODM** for drone/aerial mapping, **COLMAP** or **Meshroom (AliceVision)** for general photogrammetry, and **openMVG + openMVS** or **MicMac** for high-precision work.  
Pair these with **Open3D**, **CloudCompare**, or **MeshLab** for post-processing and **OHIF** or Potree-style viewers for delivery.  
Commercial platforms (OpenSpace, Matterport, DroneDeploy, Pix4D, NavVis, GeoSLAM, etc.) add polished capture apps, cloud processing, AI progress tracking, and managed scale.  
Many teams run fully self-hosted photogrammetry pipelines for cost control and data privacy, or hybrid setups that process locally and publish to commercial digital-twin viewers.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Reality-capture data often includes sensitive site, building, or infrastructure information. Proper access controls, data retention policies, and privacy considerations are essential.
- Open-source photogrammetry and reconstruction tools deliver excellent results when run on adequate hardware but require technical expertise for installation, parameter tuning, georeferencing, and quality control. Evaluate compute requirements and accuracy needs carefully against managed commercial services.

---

**Made for construction teams, surveyors, architects, digital-twin practitioners, and reality-capture specialists.**  
Let's make high-quality 3D capture and reconstruction more open, accurate, and accessible—whether through managed platforms or fully open-source pipelines.
