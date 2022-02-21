# Computational Fluid Dynamics in Taichi
A collection of CFD related resources for Taichi developers.

[**Taichi**](https://github.com/taichi-dev/taichi) is an open-source, imperative, parallel programming language for high-performance numerical computation. It is embedded in Python and uses just-in-time (JIT) compiler frameworks (e.g. LLVM) to offload compute-intensive Python code to the native GPU or CPU instructions.

Taichi provides several advantages over existing computational fluid dynamics tools:
- Performance: Through the @ti.kernel decorator, Taichi's JIT compiler automatically compiles your Python functions into efficient GPU or CPU machine code for **parallel execution**.
- Portability: Write your code once and run it everywhere. You can easily **reproduce** other's work without worrying about environment setup.
- Simplicity: Data structure detached from computational logic. Tuning performance with only a few lines of change.

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


- Lattice-Boltzmann Method
  - [LBM_Taichi](https://github.com/hietwll/LBM_Taichi) by [@hietwll](https://github.com/hietwll)

### Compressible Fluids ###

### Surface Flow ###

### Particle Based Methods ###

- Smoothed-Particle Hydrodynamics (SPH) 
  - [SPH_Taichi](https://github.com/erizmr/SPH_Taichi) by [@erizmr](https://github.com/erizmr)
  - [wcsph](https://github.com/lyd405121/wcsph) by [@lyd405121](https://github.com/lyd405121)
  - [SPH-2D-Taichi](https://github.com/MmmmHeee/SPH-2D-Taichi) by [@MmmmHeee](https://github.com/MmmmHeee)
  - [taichiCourse01_tiSPHi](https://github.com/Rabmelon/taichiCourse01_tiSPHi) by [@Rabmelon](https://github.com/Rabmelon)
