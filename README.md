About csm
=========

The Community Sensor Model API

csm is a C++ API for terrestrial and planetary sensor models

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-csm-green.svg)](https://anaconda.org/conda-forge/csm) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/csm.svg)](https://anaconda.org/conda-forge/csm) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/csm.svg)](https://anaconda.org/conda-forge/csm) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/csm.svg)](https://anaconda.org/conda-forge/csm) |

Installing csm
==============

Installing `csm` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `csm` can be installed with:

```
conda install csm
```

It is possible to list all of the versions of `csm` available on your platform with:

```
conda search csm --channel conda-forge
```

Building csm
============

This repo uses a CMake based build configuration. Run CMake with the desirge configurations and generator to configure your build. Then, run your build system or use cmake. For example:

```
mkdir build install
cd build
cmake -DCMAKE_BUILD_TYPE=RELEASE -DCMAKE_INSTALL_PREFIX=../install ..
cmake --build . --target install
```

will build the library in your `build` directory and install it and the headers into your `install` directory.
