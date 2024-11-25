# Gallery
- Rendering
    - **Path Tracer**
    - **Ray Tracer**
    - Rasterizer
- Geometry
    - Mesh
    - ARAP
    - L-System
- Simulation
    - **MPM + 3DGS, Young's Modulus Estimation**
    - FEM
- Computational Photography & Vision
    - **View Interpolation**
    - **Raw 3DGS**
    - **Exposure Fusion**
    - **Gradient Domain HDR Compression in CUDA**
    - Poisson Blending
    - Texture Transfer
    - Panorama - Little Planet

---
*Click subtitles to check more results*

## Rendering
- [Monte Carlo Path Tracer](path-tracer.md)
    *& Image-based Lighting (IBL), Importance Sampling, Attenuation in Medium*.

    <img style="width:60%" src="path-ranrandy/student_outputs/extra/teapot_mitsuba.png" alt="path tracer teaser" />

- [Ray Tracer](ray-tracer.md) *& Bounding Volume Hierarchy (BVH)*.

    <img style="width:49%" src="raytracer/outputs/texture_uv_1024_768.png" alt="ray tracer teaser 1" />
    <img style="width:49%" src="raytracer/outputs/recursiveSpheres4.png" alt="ray tracer teaser 2" />

- [Rasterizer](rasterizer.md).

    <img style="width:60%" src="rasterizer/screenshots/dragon.png" alt="rasterizer teaser 1" />


## Geometry
- [Mesh](mesh.md): *Subdivision, Simplification, & Remeshing*.

    | **Input**                                  | **Remeshed**                             |
    |:------------------------------------------:|:----------------------------------------:|
    | ![Input](mesh-ranrandy/student_outputs/extra/peter_input_1.png) | ![Remeshed](mesh-ranrandy/student_outputs/extra/remesh_peter_1.png) |

- [As-Rigid-As-Possible (ARAP)](arap.md)

    <img style="width:100%" src="arap-ranrandy/result-videos/armadillo-teaser.gif" alt="ARAP teaser" />

- [L-System](l-system.md) *for trees*.

    <img style="width:49%" src="L-system/outputs/l_system_tree_3d_Figure_2_8_b.png" alt="L-system teaser" />
    <!-- <img style="width:36.75%" src="L-system/outputs/l_system_tree_3d_Figure_2_6_c.png" alt="rasterizer teaser 1" /> -->


## Simulation
- [Material Point Method (MPM) on 3D Gaussians](https://github.com/ranrandy/gaussian-splatting-mpm)

    <img style="width:70%" src="gs-mpm/elastic-lego.gif" alt="MPM teaser" />
    <img style="width:70%" src="gs-mpm/gs-mpm-elasticity-optimization.gif" alt="MPM optimizer teaser" />

- [Finite Element Method (FEM)](fem.md).

    <img style="width:70%" src="fem-ranrandy/result-videos/basic.gif" alt="FEM teaser" />

## Computational Photography & Vision
- [View Interpolation](https://github.com/ranrandy/view-interpolation)

    <img style="width:100%" src="vision/view-interpolation.gif" alt="view interpolation teaser" />

- [Raw 3D Gaussian Splatting](raw-3dgs.md)

    <img style="width:100%" src="vision/raw-3dgs.png" alt="raw 3dgs teaser" />

- [Gradient Domain HDR Compression (CUDA)](https://github.com/ranrandy/hdrc)

    | **Gamma**                                  | **HDRC**                                 |
    |:------------------------------------------:|:----------------------------------------:|
    | ![Gamma](vision/belgium_ldr_gamma.png)     | ![HDRC](vision/belgium_ldr_hdrc.png)     |

- Exposure Fusion

    | **Naive Fusion**                           | **Pyramid Fusion**                       |
    |:------------------------------------------:|:----------------------------------------:|
    | ![Naive Fusion](vision/expoF_naive_wc1.0_ws1.0_wwe1.0_wes0.2.png) | ![Pyramid Fusion](vision/expoF_pyramid_wc1.0_ws1.0_wwe1.0_wes0.2.png) |

    <img style="width:100%" src="vision/expoF_kfc.png" alt="Exposure Fusion with Flash teaser" />

- Poisson Blending

    <img style="width:100%" src="vision/poisson_blending.jpg" alt="poisson blending teaser" />

- Texture Transfer

    <img style="width:100%" src="vision/texture_transfer.png" alt="texture transfer teaser" />

- Panorama - Little Planet

    <img style="width:100%" src="vision/pano_little_planet.jpg" alt="little planet pano teaser" />
