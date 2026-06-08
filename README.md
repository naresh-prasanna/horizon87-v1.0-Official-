# HORIZON 87

**Solar System Visualization, Observer Guidance & Mission Analysis Suite**

Horizon 87 is a browser-based astronomy and preliminary mission-analysis project. It combines solar system visualization, observer-aware sky-event guidance, validation against NASA/JPL Horizons reference data, and Lambert-solver-based transfer-window analysis.

The live project is available at:

**https://horizon87.com**

## What Horizon 87 Does

Horizon 87 provides:

* 2D solar system visualization with geocentric and heliocentric views
* 3D telemetry mode for spatial interpretation
* planet parade and sky-event scanning
* lunar phase and eclipse geometry tools
* ZENITH validation against NASA/JPL Horizons reference vectors
* preliminary Mission Lab transfer-window and porkchop analysis
* local precision-asset storage through the Orion Private File System layer

## Project Status

Horizon 87 v1.0 is a desktop web application. Mobile browsers are not the primary target for this release.

The public repository contains documentation, screenshots, validation samples, and project materials. The full production source code and runtime package are not distributed from this repository.

## Documentation

The documentation suite is organized into four main documents:

1. **Technical Operations Manual**
   General architecture, trust bands, mathematical modules, ephemeris engines, storage, and limitations.

2. **Validation & Accuracy Report**
   Residual summaries, Horizons comparison setup, fixture results, and validation boundaries.

3. **Developer Architecture Guide**
   Module map, worker architecture, storage pipeline, rendering path, validation path, and implementation notes.

4. **User Guide**
   Screenshot-based instructions for using Horizon 87.

## Accuracy Claim

In selected matched validation comparisons, Horizon 87’s ZENITH runtime has demonstrated micrometer-scale residual agreement against NASA/JPL Horizons reference vectors.

This is a run-specific validation result under matched target, observer, frame, time scale, and correction conventions. It is not a universal promise for every object, date, display mode, or scanner feature.

## Trust Boundaries

Horizon 87 separates its features into different trust bands:

* **Survey-grade** for fast exploration and visual discovery
* **Observer-grade** for sky-event guidance
* **Validation-grade** for matched Horizons residual comparisons
* **Mission-screening** for preliminary Lambert transfer analysis

Horizon 87 is not affiliated with, endorsed by, or certified by NASA, JPL, NAIF, or any space agency.

## Repository Contents

This public repository may include:

* project documentation
* screenshots
* validation exports
* public release notes
* non-production excerpts or diagrams

This public repository does not include:

* full production source code
* private deployment configuration
* private runtime package logic
* large precision kernel package files

## Author

Created by **Naresh Prasanna**
Mintbyte Cognitive Systems Limited

© 2026 Naresh Prasanna / Mintbyte Cognitive Systems Limited. All rights reserved.
