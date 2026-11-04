# Vihara-D-Sat — Documentation v0.0
**Foundation document | 4 November 2026**

## 1. Vision and boundaries
Build a Bihar-specific geospatial and agricultural intelligence platform by upgrading the existing three-season DCS analytics application rather than starting a new application. The primary goal is personal engineering mastery and a demonstrable technical portfolio, not immediate commercialization.

## 2. Name and identity
- Project: **Vihara-D-Sat**
- Working descriptor: **Bihar Digital Crop Survey & Satellite Intelligence Platform**
- Vihara: Bihar's historical/cultural association; D: Digital Crop Survey; Sat: satellite imagery.
- Branding is provisional; trademark clearance has not been completed.
- State-specific scope does not imply government endorsement or official deployment.

## 3. Existing assets — to verify after import
The previously developed Streamlit application reportedly includes seven pages:
| Page | Function | Planned evolution |
|---|---|---|
| 01 Download Status | Ingestion monitoring | Pipeline observability |
| 02 Data Quality | Validation and anomalies | Explainable quality scoring |
| 03 Crop Summary | Crop distribution | Seasonal crop intelligence |
| 04 Village Summary | Administrative aggregation | Spatial analytics |
| 05 Anaabaad / Government Land | Land category analysis | Evidence-based land monitoring |
| 06 Cropping Intensity | Multi-season measures | Satellite cross-validation |
| 07 Bihar Village Map | Geospatial display | Parcel/imagery overlays |

These modules are based on prior project discussions. Their present source code and runtime behavior have **not been inspected** in this repository.

## 4. Data scope
Initial focus: Kharif, Rabi and Garma seasons in crop year 2025–26. Define season identifiers, village/plot keys, coordinate reference systems, land-area units and data provenance during import. Do not assume crop observations prove legal title or ownership.

## 5. Architecture — evolutionary, not a rewrite
**Current foundation to recover:** Streamlit UI + Python processing + SQL Server + GIS layers.

**Potential additions, only after baseline verification:**
1. Satellite processing with reproducible Python workflows and documented image provenance.
2. ASP.NET Core service endpoints where they improve separation of concerns.
3. AI/ML for classification, change detection and anomaly explanation, with measurable validation.
4. Encryption in transit and at rest, role-based access and secure secrets management.
5. Signed audit records; optional blockchain anchoring only if a concrete multi-party trust requirement emerges.

## 6. Version milestones
- **v0.0 Foundation (current):** naming, project scope, inventory, migration plan and security rules.
- **v0.1 Baseline:** safely import existing source, establish reproducible setup, and verify all seven pages against authorized/synthetic data.
- **v0.2 Satellite:** demonstrate one validated imagery-to-plot analytical workflow.
- **v0.3 Services and security:** introduce appropriate APIs, authentication, encryption and auditability.
- **v0.4 AI and verification:** evaluate AI methods and, only if justified, decentralized evidence anchoring.

Milestones are proposals, not delivered functionality.

## 7. Immediate next action
Locate the original DCS Streamlit project directory. Review dependencies and secrets locally before importing sanitized source code into this private repository. Preserve the existing implementation and its history where feasible.

## 8. Acceptance criteria for v0.1
- Local setup documented and repeatable.
- All seven pages load without hard-coded secrets.
- Queries and spatial layers work against approved or synthetic fixtures.
- Seasonal summaries reconcile to documented input data.
- Known issues and next changes tracked explicitly.

## 9. Governance and licensing
Keep repository private until code ownership, data-use rights, licenses, and branding have been reviewed. Do not publish restricted Bihar government datasets or sensitive identifiers. Separate personal portfolio work from any employer/client-owned intellectual property.

## 10. Change log
| Date | Version | Change |
|---|---|---|
| 2026-11-04 | 0.0 | Adopted Vihara-D-Sat working name and documented migration from existing DCS analytics application |
