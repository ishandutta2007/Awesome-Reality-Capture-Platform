# Awesome-Reality-Capture-Platform

## Top Reality Capture Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on 360° Capture, Photogrammetry, 3D Reconstruction, Point Clouds, Digital Twins, Drone Mapping & Site Documentation*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Reality Capture**. These tools turn photos, 360° imagery, laser scans, and drone data into accurate 3D models, point clouds, orthomosaics, digital twins, and progress documentation for construction, architecture, surveying, and industrial use.

**Examples** include OpenSpace, Matterport, DroneDeploy, Reconstruct, HoloBuilder, Cupix, NavVis, GeoSLAM, Pix4D, OpenDroneMap Cloud, Cintoo Cloud, and RealityCapture (the category leaders).

**Open-source emphasis**: Reality capture has an exceptionally strong open-source ecosystem. **OpenDroneMap / WebODM**, **COLMAP**, **Meshroom (AliceVision)**, **OpenSfM**, **MicMac**, **openMVG + openMVS**, and related tools provide production-capable photogrammetry and 3D reconstruction pipelines. This section is heavily expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Primary Focus & Capabilities | Starting Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Matterport](https://matterport.com/)** | 3D spatial capture, digital twins, virtual tours, and photorealistic property documentation from smartphones and 360° cameras. | Starts at **$12/month** ($144/year billed annually) or **$14/month** (billed monthly) for Starter 5 (5 active spaces, 1 user seat). | **Free forever plan**: 1 active space, 1 user account, capture via iOS/Android phones and supported 360° cameras (excludes Matterport Pro cameras and schematic floor plan exports). |
| **[OpenDroneMap Cloud (WebODM Lightning)](https://www.opendronemap.org/)** | Hosted photogrammetry cloud service converting drone, aerial, and terrestrial imagery into orthomosaics, 3D textured models, and digital elevation models. | Starts at **$24/month** (billed annually at $288/year) or **$29/month** (billed monthly) for Starter tier (up to 1,500 images/map, 1 concurrent task, 100 GB storage); pay-as-you-go credits start from **$10**. | **Free tier credits**: **150 free processing credits** upon account signup (~150 drone images processed) with no expiration date. (Self-hosted WebODM is free forever with unlimited processing). |
| **[Cupix](https://www.cupix.com/)** | 3D reality capture, 360° video site walkthroughs, BIM-to-as-built comparison, and digital twin platform for construction site documentation. | Starts at **$20.40/month** (billed annually at $245/year) or **$24/month** (billed monthly) for Cupix Studio/Homes entry tier; CupixWorks construction enterprise tiers start at **~$500/month**. | **Free forever plan**: 1 active 3D virtual tour / workspace per month. **30-day free trial** includes 1 active workspace and 250 MB cloud storage for full virtual tour creation. |
| **[GeoSLAM (FARO Connect / Sphere XG)](https://geoslam.com/)** | Handheld and mobile LiDAR SLAM registration, 3D point cloud generation, geospatial filtering, and cloud digital twin hosting. | Starts at **$99/month** for FARO Sphere XG Connect cloud entry tier (or **~$4,500** perpetual desktop license with ~$1,200/year maintenance). | **30-day free trial**: Fully functional evaluation license via FARO providing full mobile LiDAR SLAM processing, point-cloud filtering, and registration tools. |
| **[Cintoo Cloud](https://cintoo.com/)** | Cloud-based reality capture platform converting massive laser scan point clouds into high-resolution 3D surface meshes for BIM coordination and scan-to-BIM comparison. | Starts at **~$100/month** (billed annually from ~$1,200/year for entry 100-scan packages) or **€90/month** for basic cloud hosting tiers. | **30-day free trial**: Full access to cloud point-cloud mesh viewer, scan-to-BIM overlay comparison, cropping, and measurement tools using pre-loaded sample scans or custom scan uploads. |
| **[Pix4D (PIX4Dcloud)](https://www.pix4d.com/)** | Professional photogrammetry cloud suite processing drone and terrestrial imagery into survey-grade 2D orthomosaics, 3D point clouds, and elevation models. | Starts at **$107.50/month** (billed annually at $1,290/year) or **$129/month** (billed monthly) for PIX4Dcloud Starter (500 processing credits/year, 500 GB cloud storage). | **15-day free trial** of PIX4Dcloud Pro: Includes 40 cloud processing credits, timeline comparisons, and 2D/3D measurement tools (raw file export and download disabled during trial). |
| **[HoloBuilder (FARO Sphere XG)](https://www.holobuilder.com/)** | 360° construction reality capture, sheet/drawing mapping, progress monitoring, and remote collaboration for jobsites. | Starts at **$125/user/month** (or entry project plans starting from **~$500/month** / $6,000/year under FARO Sphere XG). | **21-day free trial**: Full access to JobWalk mobile app, 2D floor plan sheet mapping, and 1 active trial project with unlimited 360° photo uploads (no credit card required). |
| **[NavVis (NavVis IVION)](https://www.navvis.com/)** | High-precision indoor mobile mapping, factory/building digital twins, cloud point-cloud streaming, and spatial asset management. | Starts at **€1,685/year** (~**$154/month** or ~$1,850/year) for NavVis IVION Core 25 (up to 25 site datasets/panoramas and cloud hosting). | **Free forever interactive Cloud Demo**: Unrestricted access to pre-loaded factory and enterprise facility digital twin sandboxes; **30-day proof-of-concept (POC)** available for enterprise site evaluations upon consultation. |
| **[DroneDeploy](https://www.dronedeploy.com/)** | Autonomous drone mapping and reality-capture platform producing orthomosaics, 3D point clouds, elevation analytics, and 360° ground walkthroughs. | Starts at **$329/month** (billed annually at $3,948/year) or **$499/month** (billed monthly) for Individual tier (1 user, up to 1,000 images per map). | **14-day free trial**: Full access to aerial photogrammetry, Live Map, and 360 Walkthroughs (capped at standard 1,000 images/map; no credit card required). Mobile flight planning app remains permanently free with no processing. |
| **[Reconstruct](https://www.reconstructinc.com/)** | Visual Command Center integrating drone photogrammetry, 360° walk capture, and 4D BIM schedule-versus-reality progress tracking. | Starts at **~$500/month** (**$6,000/year**) for single-project entry license deployments; enterprise multi-project contracts scale from $10,000+/year. | **30-day free trial / guided pilot**: 1 active project deployment with unlimited user seats, 4D BIM schedule integration, and multi-source reality capture (drones, 360° cameras, and smartphones). |
| **[OpenSpace](https://www.openspace.ai/)** | AI-powered construction reality-capture platform providing automated 360° video walkthroughs, BIM side-by-side comparison, and Vision Engine site progress tracking. | Starts at **~$833/month** (**$10,000/year** minimum platform entry threshold), scaling based on annual construction volume and feature modules. | **30-day proof-of-concept (POC) pilot**: 1 active jobsite deployment with 360° video walk processing, BIM alignment, and field team onboarding. OpenSpace Academy learning resources are permanently free. |
| **[RealityCapture (Capturing Reality / Epic Games)](https://www.capturingreality.com/)** | High-performance photogrammetry engine and RealityScan mobile app for photorealistic 3D mesh reconstruction from aerial, handheld, and DSLR photos. | **Free** for businesses and individuals earning under $1M gross annual revenue; **$1,250/seat/year** (~**$104.17/month**) subscription for organizations exceeding $1M/year. | **Free forever tier**: Full-featured photogrammetry desktop processing with unlimited exports for users/companies with <$1M annual revenue. RealityScan mobile iOS/Android app is permanently free. |

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
