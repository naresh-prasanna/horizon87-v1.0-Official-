# Horizon 87

**Solar System Visualization, Observer Guidance & Preliminary Mission Analysis Suite**

Horizon 87 is a browser-based astronomy and preliminary mission-analysis project built to make solar system geometry, sky-event guidance, and transfer-window exploration more accessible.

Unlike a basic planet visualizer, Horizon 87 includes a validation layer that compares local state-vector calculations against NASA/JPL Horizons reference data under matched target, observer, frame, time scale, and correction conventions.

Live project:

https://horizon87.com

---

## What Horizon 87 Does

Horizon 87 provides:

* 2D solar system visualization with geocentric and heliocentric views
* 3D telemetry mode for spatial interpretation
* planet parade and sky-event scanning
* lunar phase and eclipse geometry tools
* ZENITH validation against NASA/JPL Horizons reference vectors
* preliminary Mission Lab transfer-window and porkchop analysis
* local precision-asset storage through the Orion Private File System layer

---

## Why This Project Matters

Most student astronomy projects focus on visualization. Horizon 87 is designed around both visualization and verification.

The project separates fast exploratory features from higher-trust validation workflows, making clear which outputs are for visual discovery, observer guidance, validation comparison, or preliminary mission screening.

---

## Project Status

Horizon 87 v1.0 is a desktop web application. Mobile browsers are not the primary target for this release.

This public repository is a documentation, validation, and project-materials repository. The full production source code and private runtime package are not distributed here.

---

## Documentation

The documentation suite is organized into four main documents:

### Technical Operations Manual

Covers system architecture, trust bands, mathematical modules, ephemeris engines, local storage, and known limitations.

### Validation & Accuracy Report

Covers residual summaries, NASA/JPL Horizons comparison setup, validation fixtures, and claim boundaries.

### Developer Architecture Guide

Covers module structure, worker architecture, storage pipeline, rendering path, validation path, and implementation notes.

### User Guide

Provides screenshot-based instructions for using Horizon 87.

---

## Accuracy Claim

In selected matched validation comparisons, Horizon 87’s ZENITH runtime has demonstrated micrometer-scale residual agreement against NASA/JPL Horizons reference vectors.

This is a run-specific validation result under matched target, observer, frame, time scale, and correction conventions. It is not a universal promise for every object, date, display mode, scanner feature, or mission-analysis output.

Exact validation claims should be read together with the exported validation dossier, including timestamp, kernel version, frame, observer, correction convention, fixture count, and maximum residual.

---

## Trust Boundaries

Horizon 87 separates its features into different trust bands:

* **Survey-grade** -fast exploration and visual discovery
* **Observer-grade** - sky-event and visibility guidance
* **Validation-grade** - matched NASA/JPL Horizons residual comparisons
* **Mission-screening** - preliminary Lambert transfer-window analysis

Horizon 87 is not affiliated with, endorsed by, or certified by NASA, JPL, NAIF, or any space agency.

---

## Repository Contents

This public repository may include:

* project documentation
* screenshots
* validation exports
* release notes
* diagrams
* non-production excerpts

This public repository does not include:

* full production source code
* private deployment configuration
* private runtime package logic
* large precision kernel package files

---

## Author

Created by **Naresh Prasanna**.

© 2026 Naresh Prasanna. All rights reserved.
