# Vihara-D-Sat
**Bihar Digital Crop Survey & Satellite Intelligence Platform**

**Documentation version:** 0.1 · **Updated:** 27 November 2026 · **Current analysis:** Kharif, Cropping Year 2026–27

Vihara-D-Sat is a personal engineering mastery project intended to evolve an existing multi-page Digital Crop Survey (DCS) analytics application for Bihar, covering the three agricultural seasons of crop year 2025–26. This repository is the new home for the project; the existing application source has **not yet been imported or verified**.

## Purpose
Combine multi-season crop survey analytics, geospatial analysis, satellite imagery, secure application engineering and eventually AI-based interpretation in a single maintainable system. Bihar is the initial deployment context, not an assertion of government affiliation.

## Existing application modules (reported; awaiting source-code verification)
1. Download Status
2. Data Quality
3. Crop Summary
4. Village Summary
5. Anaabaad / Government Land
6. Cropping Intensity
7. Bihar Village Map

## Technology direction
- **Existing foundation:** Python, Streamlit, SQL Server, GIS and GeoJSON.
- **Planned extensions:** satellite imagery analysis, ASP.NET Core APIs, AI/ML, encryption, signed audit trails, and blockchain anchoring only if justified.

## Current dashboard — v0.1
The division-wise analysis is for **Kharif, cropping year 2026–27**, covering nine divisions and 38 districts of Bihar. The public dashboard currently displays synthetic demonstration data, not official survey results. [Open dashboard](https://manasvinabhishek.github.io/Vihara-D-Sat/).

## Pending migration of historical application
Import and safely run the existing application, document its dependencies and data model, confirm each page works with authorized or synthetic data, and establish a reproducible local setup. No rewrite until the existing implementation is assessed.

## Security and provenance
Do not commit government datasets, personally identifiable records, credentials, access tokens, restricted API endpoints, or proprietary source code without authorization. Public demos should use synthetic or explicitly licensed data. Satellite-derived estimates must not be presented as verified land ownership or official crop-survey findings.

## Naming
*Vihara* refers to the historical cultural association with Bihar; **D** represents Digital Crop Survey; **Sat** represents satellite observation. The name is provisional pending trademark, phonetic similarity and domain checks. This is an independent personal project, not an official Bihar Government product.

See [Documentation v0.1](docs/DOCUMENTATION_v0.1.md) and [historical foundation v0.0](docs/DOCUMENTATION_v0.0.md).
