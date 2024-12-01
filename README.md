# Gallery
- Rendering
    - ***Path Tracer*** / ***Ray Tracer***
    <!-- - Rasterizer -->
- Geometry
    - Mesh / ARAP / L-System
- Simulation
    - ***MPM + 3DGS***
    <!-- - FEM -->
- Computational Photography & Vision
    - ***Raw 3DGS***
    - ***Gradient Domain HDR Compression in CUDA***
    <!-- - HDR, Exposure Fusion -->
    <!-- - View Interpolation -->
    <!-- - Poisson Blending -->
    <!-- - Texture Transfer -->
    <!-- - Panorama - Little Planet -->

---
*Click subtitles to check more results and details*

## Rendering
- [Monte Carlo Path Tracer](details/path-tracer.md)
    *& Image-based Lighting (IBL), Importance Sampling, Attenuation in Medium*.

    <img style="width:60%" src="results/path-ranrandy/student_outputs/extra/teapot_mitsuba.png" alt="path tracer teaser" />

- [Ray Tracer](details/ray-tracer.md) *& Bounding Volume Hierarchy (BVH)*.

    <img style="width:49%" src="results/raytracer/outputs/texture_uv_1024_768.png" alt="ray tracer teaser 1" />
    <img style="width:49%" src="results/raytracer/outputs/recursiveSpheres4.png" alt="ray tracer teaser 2" />

- [Rasterizer](details/rasterizer.md).

    <img style="width:60%" src="results/rasterizer/screenshots/dragon.png" alt="rasterizer teaser 1" />


## Geometry
- [Mesh](details/mesh.md): *Subdivision, Simplification, & Remeshing*.

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Input</strong><br>
        <img style="height:80%; width:auto;" src="results/mesh-ranrandy/student_outputs/extra/peter_input_1.png" alt="mesh teaser input" />
        </td>
        <td align="center" style="width:50%;">
        <strong>Remeshed</strong><br>
        <img style="height:80%; width:auto;" src="results/mesh-ranrandy/student_outputs/extra/remesh_peter_1.png" alt="mesh teaser remeshing output" />
        </td>
    </tr>
    </table>

- [As-Rigid-As-Possible (ARAP)](details/arap.md)

    <img style="width:100%" src="results/arap-ranrandy/result-videos/armadillo-teaser.gif" alt="ARAP teaser" />

- [L-System](details/l-system.md) *for trees*.

    <img style="width:49%" src="results/L-system/outputs/l_system_tree_3d_Figure_2_8_b.png" alt="L-system teaser 1" />
    <!-- <img style="width:36.75%" src="L-system/outputs/l_system_tree_3d_Figure_2_6_c.png" alt="L-system teaser 1" /> -->


## Simulation
- [Material Point Method (MPM) on 3D Gaussians](https://github.com/ranrandy/gaussian-splatting-mpm)

    <img style="width:70%" src="results/gs-mpm/elastic-lego.gif" alt="GS MPM teaser" />
    <img style="width:70%" src="results/gs-mpm/gs-mpm-elasticity-optimization.gif" alt="path tracer teaser" />

- [Finite Element Method (FEM)](details/fem.md).

    <img style="width:70%" src="results/fem-ranrandy/result-videos/basic.gif" alt="FEM teaser" />

## Computational Photography & Vision
- [Raw 3D Gaussian Splatting](details/raw-3dgs.md)

    <img style="width:100%" src="results/vision/raw-3dgs.png" alt="raw 3dgs teaser" />

- [Gradient Domain HDR Compression (CUDA)](https://github.com/ranrandy/hdrc)

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Gamma</strong><br>
        <img style="height:100%; width:auto;" src="results/vision/belgium_ldr_gamma.png" alt="hdrc teaser gamma" />
        </td>
        <td align="center" style="width:50%;">
        <strong>HDRC</strong><br>
        <img style="height:100%; width:auto;" src="results/vision/belgium_ldr_hdrc.png" alt="hdrc teaser hdrc" />
        </td>
    </tr>
    </table>

- HDR Imaging & Exposure Fusion

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Naive Fusion</strong><br>
        <img style="height:80%; width:auto;" src="results/vision/expoF_naive_wc1.0_ws1.0_wwe1.0_wes0.2.png" alt="Exposure fusion teaser input" />
        </td>
        <td align="center" style="width:50%;">
        <strong>Pyramid Fusion</strong><br>
        <img style="height:80%; width:auto;" src="results/vision/expoF_pyramid_wc1.0_ws1.0_wwe1.0_wes0.2.png" alt="Exposure fusion teaser remeshing output" />
        </td>
    </tr>
    </table>

    <img style="width:100%" src="results/vision/expoF_kfc.png" alt="path tracer teaser" />

- [View Interpolation](https://github.com/ranrandy/view-interpolation)

    <img style="width:100%" src="results/vision/view-interpolation.gif" alt="view interpolation teaser" />

- Poisson Blending

    <img style="width:100%" src="results/vision/poisson_blending.jpg" alt="poisson blending teaser" />

- Texture Transfer

    <img style="width:100%" src="results/vision/texture_transfer.png" alt="texture transfer teaser" />

- Panorama - Little Planet

    <img style="width:100%" src="results/vision/pano_little_planet.jpg" alt="little planet teaser" />
