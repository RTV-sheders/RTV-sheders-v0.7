# RTV — Ray Tracing Visual

**RTV (Ray Tracing Visual)** is a modified shader build based on the ray-tracing tutorial and code by **timetravelbeard**.

The main focus is voxel-based ray tracing, global illumination, and light bounce. It also includes ray-traced reflections, configurable shadows, temporal accumulation, and denoising to help keep the image cleaner over time.

RTV comes with several quality presets and a range of settings for lighting, water, glass, shadows, and color. You can adjust the balance between image quality and performance to suit your setup.

## Features

- **Ray-Traced Global Illumination** — Adds indirect lighting and light bounce throughout the scene.
- **Voxel-Based Ray Tracing** — Traces rays through a voxelized scene for lighting and reflection effects.
- **Ray-Traced Reflections** — Reflections are traced against scene data, with adjustable settings for supported surfaces.
- **Ray-Traced Shadows** — Configurable ray-traced shadows, alongside shadow map options.
- **Temporal Accumulation** — Reuses previous frames to help reduce persistent noise while maintaining detail.
- **Spatial Denoising** — Uses edge-aware filtering to reduce visible noise while taking surface normals and depth into account.
- **Animated Water** — Includes animated surface ripples, adjustable reflections, and underwater depth absorption.
- **Glass Refraction** — Adjustable refraction and distortion for glass surfaces.
- **Day and Night Lighting** — Night illumination follows Minecraft's world time, with a separate control for moonlight and sky bounce.
- **Color Controls** — Adjust saturation, vibrance, exposure, and tone mapping.
- **Quality Presets** — Choose between Low, Medium, High, and Extreme.

## Version & Requirements

- **Shader version:** 0.3
- **Shader loader:** Iris Shaders
- **Graphics API:** OpenGL 4.3 or newer
- **Shader language:** GLSL 4.30 compatibility
- **Required Iris feature:** Custom Images

## Performance

Ray tracing can be demanding, especially at higher settings. Start with the Low or Medium preset if performance is an issue, then increase the quality as needed. High and Extreme use more ray-tracing steps and can have a greater performance cost.

Actual performance will depend on your GPU, render resolution, Minecraft setup, and selected settings.

## Credits & License

RTV is a modified build based on the ray-tracing tutorial and code by **timetravelbeard**.

The original project credits and MIT license notices are retained. This is a modified version, not a claim of ownership over the original shader code.

**License: MIT.** Please keep `LICENSE.txt` and the original copyright and license notices intact when redistributing this shader or substantial portions of its code.

Original creator: [timetravelbeard on YouTube](https://youtube.com/@timetravelbeard3588)

Have fun exploring and tweaking RTV!
