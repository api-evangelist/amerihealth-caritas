# AmeriHealth Caritas (amerihealth-caritas)

AmeriHealth Caritas is one of the largest Medicaid managed care organizations in the United States, serving roughly five million members across Medicaid, Children's Health Insurance Program (CHIP), dual-eligible Medicare-Medicaid (D-SNP), Medicare-Medicaid LTSS, and Marketplace lines of business across thirteen states plus the District of Columbia. The company is owned jointly by Independence Blue Cross (majority) and Blue Cross Blue Shield of Michigan, operates state health plans under brands such as Keystone First, Select Health of South Carolina, Blue Cross Complete of Michigan, AmeriHealth Caritas Next, AmeriHealth Caritas VIP Care, and PerformCare, and exposes a set of HL7 FHIR R4 APIs through its developer portal at developer.amerihealthcaritas.com to satisfy the CMS Interoperability and Patient Access final rule (CMS-9115-F).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amerihealth-caritas/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amerihealth-caritas/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Healthcare
- Health Insurance
- Managed Care
- Medicaid
- Medicare
- Dual Eligible
- CHIP
- LTSS
- Behavioral Health
- Pharmacy Benefits
- Interoperability
- FHIR
- CMS
- SMART On FHIR
- Patient Access
- Provider Directory

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-23

## APIs

### AmeriHealth Caritas Patient Access FHIR API

HL7 FHIR R4 (4.0.1) Patient Access API published to satisfy the CMS Interoperability and Patient Access final rule (CMS-9115-F). Provides member-authorized access to clinical, claims, encounter, coverage, medication, immunization, and demographic resources for the AmeriHealth Caritas family of Medicaid, CHIP, D-SNP, LTSS, and Marketplace health plans. Member data is protected by SMART on FHIR / OAuth 2.0 with PKCE; production access requires developer registration, app review, and member consent. Per-plan FHIR base URLs are exposed under api-ext.amerihealthcaritas.com keyed by a four-digit plan code (0100, 0500, 0900, 2400, 2600 confirmed public).

- **Human URL:** [https://developer.amerihealthcaritas.com/](https://developer.amerihealthcaritas.com/)
- **Base URL:** `https://api-ext.amerihealthcaritas.com/0500/patient-api`

#### Tags

- Patient Access
- FHIR
- SMART On FHIR
- Medicaid
- CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Capability Statement](https://api-ext.amerihealthcaritas.com/0500/patient-api/metadata)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0100/patient-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0500/patient-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0900/patient-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/2400/patient-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/2600/patient-api)
- [Authorize U R L](https://member.amerihealthcaritas.com/patientaccesssvc/oauth2/v1/authorize)
- [Token U R L](https://eapics.amerihealthcaritas.com/oauth2/v1/token)
- [OpenAPI](openapi/amerihealth-caritas-patient-access-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amerihealth-caritas-patient-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-patient-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/amerihealth-caritas-rules.yml)
- [JSON Schema](json-schema/amerihealth-caritas-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amerihealth-caritas-coverage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amerihealth-caritas-explanation-of-benefit-schema.json) — [JSON Schema](https://json-schema.org/specification)

### AmeriHealth Caritas Provider Directory FHIR API

HL7 FHIR R4 (4.0.1) Provider Directory API satisfying the CMS Provider Directory requirements of the Interoperability and Patient Access final rule. Publishes Practitioner, PractitionerRole, Organization, OrganizationAffiliation, Location, and InsurancePlan resources for the AmeriHealth Caritas family of plans. No authentication is required; the directory is publicly queryable. Per-plan endpoints are exposed at api-ext.amerihealthcaritas.com under plan codes including 0100, 0500, 0900, 1200, 2100, 2400, and 2600.

- **Human URL:** [https://developer.amerihealthcaritas.com/](https://developer.amerihealthcaritas.com/)
- **Base URL:** `https://api-ext.amerihealthcaritas.com/1200/provider-api`

#### Tags

- Provider Directory
- FHIR
- Healthcare
- CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Capability Statement](https://api-ext.amerihealthcaritas.com/1200/provider-api/metadata)
- [Swagger U I](https://api-ext.amerihealthcaritas.com/1200/provider-api/swagger-ui/?page=All)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0100/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0500/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/0900/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/1200/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/2100/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/2400/provider-api)
- [Base U R L](https://api-ext.amerihealthcaritas.com/2600/provider-api)
- [OpenAPI](openapi/amerihealth-caritas-provider-directory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amerihealth-caritas-provider-directory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-provider-directory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/amerihealth-caritas-rules.yml)
- [JSON Schema](json-schema/amerihealth-caritas-practitioner-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amerihealth-caritas-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amerihealth-caritas-location-schema.json) — [JSON Schema](https://json-schema.org/specification)

### AmeriHealth Caritas Formulary FHIR API

HL7 FHIR R4 Formulary API published to satisfy CMS-9115-F drug formulary publication requirements for Medicaid managed care and D-SNP populations. Covered drug lists, tier information, and prior authorization indicators are exposed through FHIR MedicationKnowledge and List resources. Documented at developer.amerihealthcaritas.com as a public, no-authentication surface; the canonical public base URL is not separately published at api-ext.amerihealthcaritas.com and formulary resources are currently surfaced inside the Patient Access API under MedicationKnowledge / List.

- **Human URL:** [https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- **Base URL:** `https://api-ext.amerihealthcaritas.com/0500/patient-api`

#### Tags

- Formulary
- Drug Formulary
- FHIR
- Pharmacy Benefits
- CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Postman Collection](collections/amerihealth-caritas-patient-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-patient-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amerihealth-caritas-provider-directory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-provider-directory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AmeriHealth Caritas Corporate Website

Public corporate website for AmeriHealth Caritas, hosting the family-of-plans health plan finder, solutions overview, careers, member and provider portals for the federated state plans, and pointers to the CMS Interoperability developer portal.

- **Human URL:** [https://www.amerihealthcaritas.com](https://www.amerihealthcaritas.com)
- **Base URL:** `https://www.amerihealthcaritas.com`

#### Tags

- Website
- Corporate

#### Properties

- [Website](https://www.amerihealthcaritas.com)
- [Health Plan Finder](https://www.amerihealthcaritas.com/find-a-health-plan)
- [Solutions](https://www.amerihealthcaritas.com/health-care-solutions)
- [Careers](https://careers.amerihealthcaritas.com/us/en)
- [Developer Portal](https://developer.amerihealthcaritas.com/)
- [Postman Collection](collections/amerihealth-caritas-patient-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-patient-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amerihealth-caritas-provider-directory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amerihealth-caritas-provider-directory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Website](https://www.amerihealthcaritas.com)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Getting Started](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Authentication](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [C M S Final Rule](https://www.cms.gov/priorities/key-initiatives/burden-reduction/interoperability)
- [C A R I N Blue Button](https://hl7.org/fhir/us/carin-bb/history.html)
- [Da Vinci P Dex](https://hl7.org/fhir/us/davinci-pdex/history.html)
- [U S C D I](https://www.healthit.gov/isp/united-states-core-data-interoperability-uscdi#uscdi-v1)
- [S M A R T App Launch](https://hl7.org/fhir/smart-app-launch/1.0.0/)
- [Health Plan Finder](https://www.amerihealthcaritas.com/find-a-health-plan)
- [Contact Us](https://www.amerihealthcaritas.com/contact-us)
- [Careers](https://careers.amerihealthcaritas.com/us/en)
- [News Blog](https://www.amerihealthcaritas.com/newsroom)
- [Transparency In Coverage](https://www.amerihealthcaritas.com/about-us/transparency-in-coverage.aspx)
- [Git Hub](https://github.com/amerihealth)
- [Plans](plans/amerihealth-caritas-plans-pricing.yml)
- [Rate Limits](rate-limits/amerihealth-caritas-rate-limits.yml)
- [Fin Ops](finops/amerihealth-caritas-finops.yml)
- [Vocabulary](vocabulary/amerihealth-caritas-vocabulary.yml)
- [J S O N L D Context](json-ld/amerihealth-caritas-context.jsonld)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [L L Ms Txt](https://developer.amerihealthcaritas.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
