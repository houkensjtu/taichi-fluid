# Computational Fluid Dynamics in Taichi
A collection of CFD related resources for Taichi developers.

[**Taichi (太极)**](https://github.com/taichi-dev/taichi) is an open-source, imperative, parallel programming language for high-performance numerical computation. It is embedded in Python and uses just-in-time (JIT) compiler frameworks (e.g. LLVM) to offload compute-intensive Python code to the native GPU or CPU instructions.

Taichi provides several advantages over existing computational fluid dynamics tools:
- Performance: Through the @ti.kernel decorator, Taichi's JIT compiler automatically compiles your Python functions into efficient GPU or CPU machine code for **parallel execution**.
- Portability: Write your code once and run it everywhere. You can easily **reproduce** other's work without worrying about environment setup.
- Simplicity: Data structure detached from computational logic. Tuning performance with only a few lines of change.

## Installation
You can easily install Taichi with Python's package installer `pip`:

```bash
pip install taichi
```
More information can be found in [Taichi's Documentation](https://docs.taichi.graphics/).

## Taichi Learning Resources
- **SIGGRAPH 2020 course on Taichi basics**: [YouTube](https://youtu.be/Y0-76n3aZFA), [Bilibili](https://www.bilibili.com/video/BV1kA411n7jk/), [slides (pdf)](https://yuanming.taichi.graphics/publication/2020-taichi-tutorial/taichi-tutorial.pdf).
- Chinagraph 2020 用太极编写物理引擎: [哔哩哔哩](https://www.bilibili.com/video/BV1gA411j7H5)
- GAMES 201 高级物理引擎实战指南2020: [课件](https://github.com/taichi-dev/games201)
- 太极图形课第一季：[课件](https://github.com/taichiCourse01)


## Basic CFD theories


## CFD projects in Taichi
