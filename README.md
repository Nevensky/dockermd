# GMXPlumed
[![](https://images.microbadger.com/badges/version/nevensky/gmxplumed:latest-gpu.svg)](https://microbadger.com/images/nevensky/gmxplumed:latest-gpu) [![](https://img.shields.io/docker/pulls/nevensky/gmxplumed.svg)](https://hub.docker.com/r/nevensky/gmxplumed) ![](https://img.shields.io/microbadger/image-size/nevensky/gmxplumed/latest-gpu.svg) ![](https://img.shields.io/microbadger/layers/nevensky/gmxplumed/latest-gpu.svg) [![](https://img.shields.io/github/last-commit/nevensky/gmxplumed.svg)](https://github.com/Nevensky/gmxplumed/commits) [![](https://img.shields.io/github/issues-raw/nevensky/gmxplumed.svg)](https://github.com/Nevensky/gmxplumed/issues)

## Software versions
*  Gromacs v2018.4
*  Plumed v2.5.0
*  CUDA v10.0
*  Ubuntu v16.04

## Notes
Gromacs is configured to use AVX2_256 instructions and will therefore run only on newest Intel hardware. MPI is enabled for PLUMED, while Gromacs is compiled with gcc with OpenMP threading only.
