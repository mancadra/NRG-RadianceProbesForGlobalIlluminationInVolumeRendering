# NRG-RadianceProbesForGlobalIlluminationInVolumeRendering

## Radiance probes for global illumination in volume rendering
Accurate and efficient computation of global illumination is a significant challenge in volume rendering. The
appearance of materials is heavily influenced by the surrounding environment, making the quality of rendering
depend on effective environment sampling. While path tracing can produce accurate results, it is often too slow for
real-time execution. A common practical solution is to precompute radiance at fixed points in space known as
radiance probes or light probes and use these values during rendering to avoid costly computation for every light ray.
In this seminar, you will explore the radiance probe method and implement it in a prototype application. You will
evaluate the results both qualitatively and quantitatively and compare them to path tracing.

### References:

`
[1] R. Khlebnikov, P. Voglreiter, M. Steinberger, B. Kainz, D. Schmalstieg, “Parallel Irradiance Caching for
Interactive Monte‐Carlo Direct Volume Rendering,” Computer Graphics Forum, vol. 33, no. 3, 2014, doi:
10.1111/cgf.12362
`

### Project tools
- WebGPU
- JS
- glMatrix
- Three.js?

### Project Timeline

- **Week 1-2**  
  - Implement basic volume renderer  
  - Load volumetric data (.raw)
  - Design probe placement strategy  

- **Week 3-4**  
  - Compute lighting for all probes  
  - Integrate probe lighting into volume rendering  
  - Implement interpolation during rendering

- **Week 5**  
  - Implement reference path tracer  
  - Run comparative evaluations  

- **Week 6**  
  - Evaluation (Qualitative & Quantitative)
  - Write final report  
  - Polish visual results 