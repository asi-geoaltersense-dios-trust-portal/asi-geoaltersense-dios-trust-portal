# GeoAlterSense — DIOS Trust Portal

**Data Integrity, Oversight and Stewardship (DIOS)**

A geospatial decision-support initiative for environmental evidence management, investigation prioritization, and accountable human-led oversight in mining-affected communities.

[![Repository](https://img.shields.io/badge/GitHub-Public-blue?logo=github)](https://github.com/asi-geoaltersense-dios-trust-portal/asi-geoaltersense-dios-trust-portal)
[![Status](https://img.shields.io/badge/Release-Not%20Production%20Accepted-orange)](#release-status)

🌍 **Live Portal:** https://asi-geoaltersense-dios-trust-portal.arybit.co.ke/

---

## 1. Project Overview

GeoAlterSense is a proposed geospatial intelligence and environmental decision-support platform designed to organize environmental evidence and help prioritize field investigations in mining-affected areas.

The initial pilot concept focuses on mercury-related environmental investigation in Kenyan artisanal and small-scale mining (ASM) contexts.

The DIOS Trust Portal introduces a governance-oriented approach to:

- Environmental evidence organization.
- Geospatial investigation planning.
- Data provenance and integrity.
- Human-led review and oversight.
- Transparent decision workflows.
- Responsible environmental intelligence.

The platform is intended to support accountable investigation, not replace scientific testing or qualified human judgment.

## 2. Project Objectives

1. Improve organization and traceability of environmental evidence.
2. Support identification of candidate areas for field investigation.
3. Integrate authorized geospatial and environmental datasets.
4. Promote transparent review and approval workflows.
5. Support independent scientific validation.
6. Strengthen responsible data stewardship and governance.

## 3. System Architecture

The referenced application architecture consists of four separately maintained components:

| Component | Responsibility |
|---|---|
| DIOS Trust Portal | Browser-based user interface |
| PHP Gateway | Authenticated API gateway |
| Authentication API | Identity and user authentication |
| Geospatial API | Geospatial processing and mission operations |

The browser Portal communicates with the PHP Gateway, which coordinates authentication and geospatial API requests.

Production geospatial mission processing depends on Redis/RQ infrastructure and a compatible worker.

## 4. Environmental Evidence Framework

GeoAlterSense distinguishes between different evidence categories.

### Direct environmental observations
Authorized soil, sediment and water measurements with appropriate provenance and quality assurance.

### Remote sensing and mining context
Satellite imagery, surface changes and mining-related contextual information.

### Terrain and hydrology
Digital elevation models, drainage networks and catchment information.

### Population and service context
Aggregated demographic and public-service information, subject to privacy protections.

### Exploratory model outputs
Transparent, preliminary indicators used to support investigation planning.

**Important:** Exploratory scores are not calibrated contamination probabilities or measurements of human exposure.

## 5. Mercury Exposure-Risk Intelligence

The Mercury pilot concept explores how geospatial information can support environmental investigation planning in mining-affected communities.

The platform does not:

- Detect mercury directly from satellite imagery.
- Confirm environmental contamination.
- Measure individual human exposure.
- Diagnose mercury poisoning or other diseases.
- Establish causal relationships between mining and health outcomes.

Environmental measurements, laboratory confirmation and qualified human interpretation remain essential.

## 6. DIOS Governance Principles

The Data Integrity, Oversight and Stewardship framework emphasizes:

- Evidence provenance and traceability.
- Authorized access and review responsibilities.
- Jurisdiction-aware governance.
- Separation of duties.
- Evidence lifecycle management.
- Privacy and retention controls.
- Auditable human decisions.
- Independent validation and accountability.

Historical DIOS workflow concepts are retained for product discovery. Their presence does not establish that a production DIOS review, evidence-upload or audit service is currently deployed.

## 7. Technology and Infrastructure

The referenced system architecture includes:

- Browser-based Portal.
- PHP Gateway API.
- Authentication API.
- Python Geospatial API.
- Redis.
- RQ asynchronous job processing.
- External geospatial data providers.

External provider integrations depend on configuration, credentials, licensing, authorization and network availability.

## 8. Security and Data Stewardship

Production deployment requires appropriate controls for:

- Authentication and authorization.
- Tenant and jurisdiction isolation.
- Credential protection.
- Database and backup security.
- Evidence access and retention.
- API authorization.
- Audit assurance.
- Operational monitoring.

Provider credentials do not independently establish permission to access or use external datasets.

## 9. Proposed Pilot Evaluation

Before operational deployment, the project requires:

1. Agreement on the pilot geography.
2. Environmental evidence availability assessment.
3. Dataset licensing and rights review.
4. Independent field and laboratory reference measurements.
5. Defined scientific validation protocols.
6. Spatial and temporal holdout evaluation.
7. Uncertainty and geographic bias assessment.
8. Approved operational thresholds and stop/go criteria.

Any proposed pilot schedule or performance target must be evaluated rather than treated as an achieved result.

## 10. Maternal and Environmental Health Considerations

Environmental information may support broader public-health planning.

However, geographic proxies cannot establish pregnancy status, individual exposure, diagnosis or clinical risk.

Health-related applications require separate scientific, privacy and institutional review.

## 11. Release Status

**NOT PRODUCTION ACCEPTED**

The referenced source architecture requires further verification, including:

- Production API contract testing.
- Tenant-isolation testing.
- Worker lifecycle verification.
- Database and secrets-management controls.
- Deployment and rollback exercises.
- Provider licensing and rights review.
- Scientific validation.
- Privacy and security sign-off.

Source-code availability must not be interpreted as proof that every service or integration is operational.

## 12. Project Vision

GeoAlterSense aims to contribute to more transparent, evidence-driven and accountable environmental investigation.

Through geospatial intelligence, responsible data stewardship and independent scientific validation, the initiative seeks to support better-informed environmental decisions in mining-affected communities.

---

**Project:** GeoAlterSense  
**Governance Framework:** DIOS — Data Integrity, Oversight and Stewardship  
**Initial Focus:** Mercury-related environmental investigation  
**Geographic Focus:** Kenya  
**Repository:** asi-geoaltersense-dios-trust-portal

*Building responsible environmental intelligence through evidence, transparency and human accountability.*
