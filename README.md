# Gallery
- Rendering
    - Path Tracer
    - Ray Tracer
    - Rasterizer
- Geometry
    - Mesh
    - L-System
- Simulation
    - FEM
    - ARAP
    - MPM + 3DGS, Young's Modulus Estimation
- Computational Photography & Vision
    - HDR, Exposure Fusion
    - Gradient Domain HDR Compression in CUDA
    - Raw 3DGS
    - Poisson Blending
    - Texture Transfer
    - Panorama - Little Planet
    - View Interpolation

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

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Input</strong><br>
        <img style="height:80%; width:auto;" src="mesh-ranrandy/student_outputs/extra/peter_input_1.png" alt="mesh teaser input" />
        </td>
        <td align="center" style="width:50%;">
        <strong>Remeshed</strong><br>
        <img style="height:80%; width:auto;" src="mesh-ranrandy/student_outputs/extra/remesh_peter_1.png" alt="mesh teaser remeshing output" />
        </td>
    </tr>
    </table>

- [L-System](l-system.md) *for trees*.

    <img style="width:49%" src="L-system/outputs/l_system_tree_3d_Figure_2_8_b.png" alt="rasterizer teaser 1" />
    <!-- <img style="width:36.75%" src="L-system/outputs/l_system_tree_3d_Figure_2_6_c.png" alt="rasterizer teaser 1" /> -->


## Simulation
- [Finite Element Method (FEM)](fem.md).

    <img style="width:70%" src="fem-ranrandy/result-videos/basic.gif" alt="path tracer teaser" />

- [As-Rigid-As-Possible (ARAP)](arap.md)

    <img style="width:100%" src="arap-ranrandy/result-videos/armadillo-teaser.gif" alt="path tracer teaser" />

- [Material Point Method (MPM) on 3D Gaussians](https://github.com/ranrandy/gaussian-splatting-mpm)

    <img style="width:70%" src="gs-mpm/elastic-lego.gif" alt="path tracer teaser" />
    <img style="width:70%" src="gs-mpm/gs-mpm-elasticity-optimization.gif" alt="path tracer teaser" />

## Computational Photography & Vision
- HDR Imaging & Exposure Fusion

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Naive Fusion</strong><br>
        <img style="height:80%; width:auto;" src="vision/expoF_naive_wc1.0_ws1.0_wwe1.0_wes0.2.png" alt="mesh teaser input" />
        </td>
        <td align="center" style="width:50%;">
        <strong>Pyramid Fusion</strong><br>
        <img style="height:80%; width:auto;" src="vision/expoF_pyramid_wc1.0_ws1.0_wwe1.0_wes0.2.png" alt="mesh teaser remeshing output" />
        </td>
    </tr>
    </table>

    <img style="width:100%" src="vision/expoF_kfc.png" alt="path tracer teaser" />

- [Gradient Domain HDR Compression (CUDA)](https://github.com/ranrandy/hdrc)

    <table>
    <tr>
        <td align="center" style="width:50%;">
        <strong>Gamma</strong><br>
        <img style="height:100%; width:auto;" src="vision/belgium_ldr_gamma.png" alt="mesh teaser input" />
        </td>
        <td align="center" style="width:50%;">
        <strong>HDRC</strong><br>
        <img style="height:100%; width:auto;" src="vision/belgium_ldr_hdrc.png" alt="mesh teaser remeshing output" />
        </td>
    </tr>
    </table>

- [Raw 3D Gaussian Splatting](raw-3dgs.md)

    <img style="width:100%" src="vision/raw-3dgs.png" alt="path tracer teaser" />

- Poisson Blending

    <img style="width:100%" src="vision/poisson_blending.jpg" alt="path tracer teaser" />

- Texture Transfer

    <img style="width:100%" src="vision/texture_transfer.png" alt="path tracer teaser" />

- Panorama - Little Planet

    <img style="width:100%" src="vision/pano_little_planet.jpg" alt="path tracer teaser" />

- [View Interpolation](https://github.com/ranrandy/view-interpolation)

    <img style="width:100%" src="vision/view-interpolation.gif" alt="path tracer teaser" />
