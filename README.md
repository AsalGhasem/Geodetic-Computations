# Computational Geodesy

A computational study of fundamental problems in geodesy involving reference ellipsoids, numerical methods, curvature analysis, and coordinate transformations.

This repository presents implementations and analyses of mathematical models used in modern geodetic computation. The projects focus on the numerical representation of Earth's shape, geometric properties of reference ellipsoids, and transformations between different geodetic coordinate systems.

The implementations combine theoretical derivations with numerical experiments and visualization to investigate the behavior and accuracy of different computational approaches.

---

# Overview

The repository covers three major areas of computational geodesy:

* Numerical computation on reference ellipsoids
* Geometric analysis of ellipsoid properties
* Coordinate system transformations

Each module explores a fundamental component of geodetic science and demonstrates its implementation through Python and MATLAB environments.

---

# Repository Structure

```
Computational-Geodesy/
│
├── Ellipsoid_Arc_Length/
│   └── ellipsoid_arc_length.ipynb
│
├── Ellipsoid_Geometry/
│   └── curvature_and_radius_analysis.ipynb
│
├── Coordinate_Transformations/
│   └── ecef_geodetic_transformations.ipynb
│
├── MATLAB_Implementations/
│   └── geodesy_calculations.mlx
│
└── README.md
```

---

# 1. Numerical Methods for Ellipsoidal Arc Computation

## Description

This module investigates numerical techniques for computing quantities related to Earth's reference ellipsoid.

The main objective is to implement and compare different numerical approaches for solving geodetic integrals and evaluating their accuracy.

## Implemented Methods

* Trapezoidal numerical integration
* Simpson's numerical integration
* Runge-Kutta numerical methods:

  * RK1
  * RK2
  * RK4

## Analysis

The numerical results are compared with analytical approximations to evaluate:

* Accuracy
* Convergence behavior
* Computational efficiency
* Error propagation

This section demonstrates how numerical algorithms can be applied to geodetic distance and arc-length problems.

---

# 2. Reference Ellipsoid Geometry and Curvature Analysis

## Description

This module explores the geometric properties of Earth's reference ellipsoid and investigates how curvature varies across the ellipsoid surface.

The reference ellipsoid is the fundamental mathematical approximation used for representing Earth's shape in geodesy.

## Studied Parameters

The implementation includes calculations and visualization of:

* Semi-major axis
* Semi-minor axis
* First eccentricity
* Second eccentricity
* Flattening
* Meridian radius of curvature
* Prime vertical radius of curvature
* Directional radius of curvature
* Gaussian curvature

## Visualization

The notebook provides graphical analysis of:

* Variation of curvature parameters with latitude
* Differences between spherical and ellipsoidal models
* Geometric behavior from equator to pole

---

# 3. Geodetic Coordinate Transformations

## Description

Coordinate transformation is one of the fundamental computational problems in geodesy.

This module implements transformations between:

### Geodetic Coordinates

* Latitude
* Longitude
* Ellipsoidal height

and

### Earth-Centered Earth-Fixed (ECEF) Coordinates

* X
* Y
* Z

## Implemented Transformations

* Geodetic → ECEF conversion
* ECEF → Geodetic conversion

## Evaluation

The implementation includes:

* Numerical validation
* Coordinate comparison
* Visualization of transformation results

These transformations are essential in GNSS positioning, satellite navigation, and geospatial applications.

---

# Mathematical Model

The computations are based on the WGS84 reference ellipsoid.

Parameters:

| Parameter          |             Value |
| ------------------ | ----------------: |
| Semi-major axis    |         6378137 m |
| Flattening         | 1 / 298.257223563 |
| First eccentricity |   0.0818191908426 |

---

# Software and Libraries

## Python

* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## MATLAB

* MATLAB Live Script (`.mlx`)

---

# Objectives

The main objectives of this repository are:

* Implementing mathematical models used in geodesy
* Studying numerical methods for geodetic computation
* Understanding reference ellipsoid geometry
* Developing coordinate transformation algorithms
* Visualizing geophysical and geometric concepts

---

# Applications

The concepts implemented in this repository are directly related to:

* GNSS positioning
* Satellite geodesy
* Geographic information systems (GIS)
* Earth observation
* Spatial reference systems
* Geodetic surveying

---

# Author

Computational geodesy implementations developed for studying mathematical modeling, numerical analysis, and geospatial computation.
