# Specfem3D

SPECFEM3D_Cartesian simulates acoustic (fluid), elastic (solid), coupled acoustic/elastic, poroelastic or seismic wave propagation in any type of conforming mesh of hexahedra (structured or not.)

It can, for instance, model seismic waves propagating in sedimentary basins or any other regional geological model following earthquakes. It can also be used for non-destructive testing or for ocean acoustics


SPECFEM3D was founded by Dimitri Komatitsch and Jeroen Tromp, and is now being developed by a large, collaborative, and inclusive community. A complete list of authors can be found at
https://specfem3d.readthedocs.io/en/latest/authors/

## Installation

Instructions on how to install and use SPECFEM3D are
available in the

- PDF manual located in directory: [doc/USER_MANUAL](doc/USER_MANUAL)

- HTML manual (latest version): [specfem3d.readthedocs.io](http://specfem3d.readthedocs.io/)


## Development

[![Actions Status](https://github.com/geodynamics/specfem3d/workflows/CI/badge.svg)](https://github.com/geodynamics/specfem3d/actions)
[![Travis Status](https://app.travis-ci.com/geodynamics/specfem3d.svg?branch=devel)](https://app.travis-ci.com/geodynamics/specfem3d)
[![Azure Status](https://dev.azure.com/danielpeter22/SPECFEM3D/_apis/build/status/geodynamics.specfem3d?branchName=devel)](https://dev.azure.com/danielpeter22/SPECFEM3D/_build/latest?definitionId=5&branchName=devel)
[![codecov](https://codecov.io/gh/geodynamics/specfem3d/branch/devel/graph/badge.svg)](https://codecov.io/gh/geodynamics/specfem3d)
[![Documentation Status](https://readthedocs.org/projects/specfem3d/badge/?version=latest)](https://specfem3d.readthedocs.io/en/latest/?badge=latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE)

* Actions tests: [github actions specfem3d](https://github.com/geodynamics/specfem3d/actions)

* Travis tests: [travis-ci specfem3d](https://travis-ci.com/geodynamics/specfem3d/builds)


Development is hosted on GitHub in the
[geodynamics/specfem3d repository](https://github.com/geodynamics/specfem3d).

SPECFEM3D is a community project that lives by the participation of its
members — i.e., including you! It is our goal to build an inclusive and
participatory community so we are happy that you are interested in
participating! We have collected a set of guidelines and advice on how to get
involved in the community and keep them in the specfem3d github wiki:
[specfem3d wiki](https://github.com/geodynamics/specfem3d/wiki)


## Computational Infrastructure for Geodynamics (CIG)

SPECFEM3D is part of the software that is hosted by the Computational Infrastructure for Geodynamics (CIG). It is available on the CIG website [here (SPECFEM3D)](https://geodynamics.org/resources/specfem3dcartesian).

___

### Do not modify configure script

Never modify the "configure" script directly, it is better to modify the "configure.ac" file and then generate the "configure" script by typing:

```
autoreconf -i
```