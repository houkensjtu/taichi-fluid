
![banner](./images/banner.png)

[![Github-widget](https://img.shields.io/github/stars/taichi-dev/taichi?label=Taichi-lang&style=social)](https://github.com/taichi-dev/taichi)
[![Youtube-widget](https://img.shields.io/youtube/channel/views/UCu-k1Wglo9Ll_o2j5Bxl4cw?label=Taichi%20Graphics&style=social)](https://www.youtube.com/channel/UCu-k1Wglo9Ll_o2j5Bxl4cw)
[![Twitter-widget](https://img.shields.io/twitter/follow/taichigraphics?style=social)](https://twitter.com/taichigraphics)
[![Zhihu-widget](https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-view-blue)](https://www.zhihu.com/org/tai-ji-tu-xing)
[![Bilibili-widget](https://img.shields.io/badge/Bilibili-view-blue)](https://space.bilibili.com/1779922645)

A collection of CFD related resources for Taichi developers.

[**Taichi**](https://github.com/taichi-dev/taichi) is an open-source, imperative, parallel programming language for high-performance numerical computation. It is embedded in Python and uses just-in-time (JIT) compiler frameworks (e.g. LLVM) to offload compute-intensive Python code to the native GPU or CPU instructions.

Taichi provides several advantages over existing computational fluid dynamics tools:
- Performance: Through the @ti.kernel decorator, Taichi's JIT compiler automatically compiles your Python functions into efficient GPU or CPU machine code for **parallel execution**.
- Portability: Write your code once and run it everywhere. You can easily **reproduce** other's work without worrying about environment setup.
- Simplicity: Data structure detached from computational logic. Tuning performance with only a few lines of change.

> :eyes: All fluid simulation projects in [**Taichi**](https://github.com/taichi-dev/taichi) are driven by and for the community. Please feel free to open up an issue to recommend any awesome fluid project you see or build.

## Contents
- [Installation of Taichi](#installation-of-taichi)
- [Learning Resources](#learning-resources)
- [CFD Projects in Taichi](#cfd-projects-in-taichi)

## Installation of Taichi
You can easily install Taichi with Python's package installer `pip`:

```bash
pip install taichi
```

After you have installed Taichi, running a Taichi program is as simple as：
```bash
python your_program.py
```

More information can be found in [Taichi's Documentation](https://docs.taichi.graphics/).

## Learning Resources
- Taichi's documentation: [Link](https://docs.taichi.graphics/)
- SIGGRAPH 2020 course on Taichi basics: [YouTube](https://youtu.be/Y0-76n3aZFA), [Bilibili](https://www.bilibili.com/video/BV1kA411n7jk/), [slides (pdf)](https://yuanming.taichi.graphics/publication/2020-taichi-tutorial/taichi-tutorial.pdf).


## CFD Projects in Taichi

### Incompressible Fluids ###

- SIMPLE Method
  - [karman_taichi](https://github.com/houkensjtu/karman_taichi) by [@houkensjtu](https://github.com/houkensjtu)
  - [SIMPLE-taichi](https://github.com/houkensjtu/SIMPLE-taichi) by [@houkensjtu](https://github.com/houkensjtu)
- Lattice-Boltzmann Method
  - [LBM_Taichi](https://github.com/hietwll/LBM_Taichi) by [@hietwll](https://github.com/hietwll)
  - [taichi-LBM](https://github.com/GeCao/taichi-LBM) by [@Gecao](https://github.com/GeCao)
  - [taichi_LBM3d](https://github.com/yjhp1016/taichi_LBM3D) by [@yjhp1016](https://github.com/yjhp1016)
  - [mcmp-lbm](https://github.com/geoelements/mcmp-lbm) by [@geoelements](https://github.com/geoelements/)
- Level-Set Method
  - [taichi_ferrofluid](https://github.com/g1n0st/taichi_ferrofluid) by [@g1n0st](https://github.com/g1n0st)
- Marker-And-Cell (MAC) Method
  - [2d-fluid-simulator](https://github.com/takah29/2d-fluid-simulator) by [@takah29](https://github.com/takah29)
  - [MAC-taichi](https://github.com/houkensjtu/MAC-taichi) by [@houkensjtu](https://github.com/houkensjtu)
- Volume-Of-Fluid (VOF) Method
  - [taichi-2d-vof](https://github.com/houkensjtu/taichi-2d-vof) by [@houkensjtu](https://github.com/houkensjtu)
  

### Compressible Fluids ###

- Convection Riemann solver
  - [taichi-fvm2d-fluid-ns](https://github.com/hejob/taichi-fvm2d-fluid-ns) by [@hejob](https://github.com/hejob)


### Particle Based Methods ###

- Smoothed-Particle Hydrodynamics (SPH) 
  - [SPH_Taichi](https://github.com/erizmr/SPH_Taichi) by [@erizmr](https://github.com/erizmr)
  - [wcsph](https://github.com/lyd405121/wcsph) by [@lyd405121](https://github.com/lyd405121)
  - [SPH-2D-Taichi](https://github.com/MmmmHeee/SPH-2D-Taichi) by [@MmmmHeee](https://github.com/MmmmHeee)
  - [taichiCourse01_tiSPHi](https://github.com/Rabmelon/taichiCourse01_tiSPHi) by [@Rabmelon](https://github.com/Rabmelon)
  - [Real-Time 3D Fluid Simulator](https://github.com/guardhao104/3DFluidSimulator) by [@guardhao104](https://github.com/guardhao104)
  - [SPH-Fluid](https://github.com/Mr-222/SPH-Fluid) by [@Mr-222](https://github.com/Mr-222/)
  - [2023project](https://github.com/Nope132/2023project) by [@Nope132](https://github.com/Nope132/)
  - [SPH_Project](https://github.com/jason-huang03/SPH_Project) by [@jason-huang03](https://github.com/jason-huang03/)
  - [CFD_Taichi](https://github.com/Jukgei/CFD_Taichi) by [@Jukgei](https://github.com/Jukgei/)


### Computational Graphics ###
- Eulerian solver
  - [Taichi_HW1_EulerianFluid](https://github.com/JerryYan97/Taichi_HW1_EulerianFluid) by [@JerryYan97](https://github.com/JerryYan97)
  - [2DEularianFluidSolver](https://github.com/Lee-abcde/2DEulerianFluidSolver/tree/main) by [@Lee-abcde](https://github.com/Lee-abcde/)

- Stable fuilds
  - [Stable_Fluid_3D_taichi](https://github.com/LEE-JAE-HYUN179/Stable_Fluid_3D_taichi) by [@LEE-JAE-HYUN179](https://github.com/LEE-JAE-HYUN179/)
  - [Euler-Fluid](https://github.com/jinjinhe2001/Euler-Fluid) by [@jinjinhe2001](https://github.com/jinjinhe2001/)
- FFT
  - [taichi-simple-fluid-solver](https://github.com/0xrabbyte/taichi_simple_fluid_solver) by [@0xrabbyte](https://github.com/0xrabbyte)
- Interactive surface flow
  - [TaichiSimplicialFluid](https://github.com/yhesper/TaichiSimplicialFluid) by [@yhesper](https://github.com/yhesper)
- PIC / FLIP
  - [apic2d](https://github.com/nepluno/apic2d) by [@nepluno](https://github.com/nepluno)
  - [Power-PIC](https://github.com/g1n0st/Power-PIC) by [@g1n0st](https://github.com/g1n0st)
- MPM
  - [HKUST_Advanced_Digital_Design_Project](https://github.com/DukeofCambridge/HKUST_Advanced_Digital_Design_Project/tree/main) by [@DukeofCambridge](https://github.com/DukeofCambridge)
  - [mpm-sandbox](https://github.com/chhsiao93/mpm-sandbox) by [@chhsiao93](https://github.com/chhsiao93)
  - [3D-FluidSimulation-PathTracing](https://github.com/Mirage-c/3D-FluidSimulation-PathTracing) by [@Mirage-c](https://github.com/Mirage-c/)
  - [DreaMPM](https://github.com/Zhuohua-HUANG/DreaMPM) by [@Zhuohua-HUANG](https://github.com/Zhuohua-HUANG/)
  - [taichi_mpm](https://github.com/yjchoi1/taichi_mpm) by [@yjchoi1](https://github.com/yjchoi1/)


### Fluid Engine ###
- [taichi-particles](https://github.com/taichi-dev/taichi-particles) by [@taichi-dev](https://github.com/taichi-dev)
- [taichi_fluids](https://github.com/taichi-dev/taichi_fluids) by [@taichi-dev](https://github.com/taichi-dev)
- [a-toy-fluid-engine](https://github.com/Jack12xl/a-toy-fluid-engine) by [@Jack12xl](https://github.com/Jack12xl)
- [Fluid-Engine-Dev-on-Taichi](https://github.com/JYLeeLYJ/Fluid-Engine-Dev-on-Taichi) by [@JYLeeLYJ](https://github.com/JYLeeLYJ)

### Artificial Intelligence ###
- Neural Fluid Fields
  - [HyFluid](https://github.com/y-zheng18/HyFluid) by [@y-zheng18](https://github.com/y-zheng18/)
  - [neural_flow_maps_code](https://github.com/yitongdeng-projects/neural_flow_maps_code) by [@yitongdeng-projects](https://github.com/yitongdeng-projects/)