# Vihara-D-Sat — Documentation v0.1
**27 November 2026 | Kharif | Cropping Year 2026–27**

## Scope
The current division-wise Digital Crop Survey analysis concerns Kharif of cropping year 2026–27 in Bihar, covering nine divisions and 38 districts. The earlier three-season 2025–26 application remains a historical foundation, not the reporting period for this analysis.

## Dashboard
The static HTML/CSS/JavaScript dashboard supports division selection, district comparisons, assigned/surveyed/approved plots, surveyor counts, raw and adjusted Unable to Survey counts, crop area distribution and CSV export. The public implementation uses synthetic demonstration data only; actual departmental analysis is not published or independently validated here.

## Calculation
Survey progress (%) = 100 × surveyed plots / (assigned plots − adjusted Unable to Survey plots).
For valid counts, adjusted Unable to Survey = min(raw Unable to Survey, assigned − surveyed). Preserve raw counts for audit. A zero denominator is not applicable; invalid source counts require review. Aggregate counts before calculating percentages.

## Next steps
Integrate authorized aggregated Kharif 2026–27 outputs from daily survey summary, surveyor summary and crop-village analysis; validate the selected crop area dataset; add geographic drill-down, surveyor rankings and crop anomaly review. Plot-level surveyor linkage is required for individual crop attribution.

## Governance
Independent personal project, not an official government product. Do not publish restricted data, personal identifiers, credentials or proprietary code. Use synthetic or explicitly authorized data. The historical Streamlit source migration remains pending.

## History
See [v0.0 foundation](DOCUMENTATION_v0.0.md).
