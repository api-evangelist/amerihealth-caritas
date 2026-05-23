# AmeriHealth Caritas (amerihealth-caritas)

AmeriHealth Caritas is one of the largest Medicaid managed care organizations in the United States, serving roughly five million members across Medicaid, CHIP, dual-eligible Medicare-Medicaid (D-SNP), LTSS, and Marketplace lines of business across thirteen states plus the District of Columbia. The company is owned jointly by Independence Blue Cross (majority) and Blue Cross Blue Shield of Michigan, operates state health plans under brands such as Keystone First, Select Health of South Carolina, Blue Cross Complete of Michigan, AmeriHealth Caritas Next, AmeriHealth Caritas VIP Care, and PerformCare, and exposes a set of HL7 FHIR R4 APIs through its developer portal at developer.amerihealthcaritas.com to satisfy the CMS Interoperability and Patient Access final rule (CMS-9115-F).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amerihealth-caritas/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Healthcare, Health Insurance, Managed Care, Medicaid, Medicare, Dual Eligible, CHIP, LTSS, Behavioral Health, Pharmacy Benefits, Interoperability, FHIR, CMS, SMART On FHIR, Patient Access, Provider Directory

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-23

## APIs

### AmeriHealth Caritas Patient Access FHIR API

HL7 FHIR R4 (4.0.1) Patient Access API published to satisfy the CMS Interoperability and Patient Access final rule (CMS-9115-F). SMART on FHIR / OAuth 2.0 secured; per-plan FHIR base URLs are exposed under `api-ext.amerihealthcaritas.com` keyed by a four-digit plan code (0100, 0500, 0900, 2400, 2600 confirmed public).

**Human URL:** [https://developer.amerihealthcaritas.com/](https://developer.amerihealthcaritas.com/)

**Base URL:** `https://api-ext.amerihealthcaritas.com/0500/patient-api`

#### Tags

- Patient Access, FHIR, SMART On FHIR, Medicaid, CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [CapabilityStatement](https://api-ext.amerihealthcaritas.com/0500/patient-api/metadata)
- [Authorize URL](https://member.amerihealthcaritas.com/patientaccesssvc/oauth2/v1/authorize)
- [Token URL](https://eapics.amerihealthcaritas.com/oauth2/v1/token)
- [OpenAPI](openapi/amerihealth-caritas-patient-access-openapi.yml)
- [Spectral Rules](rules/amerihealth-caritas-rules.yml)
- [Naftiko Capability — Patient Access](capabilities/amerihealth-caritas-patient-access.yaml)
- [Naftiko Capability — Claims & EOB](capabilities/amerihealth-caritas-claims-and-eob.yaml)
- [Naftiko Capability — Medications & Formulary](capabilities/amerihealth-caritas-medications-and-formulary.yaml)

### AmeriHealth Caritas Provider Directory FHIR API

HL7 FHIR R4 (4.0.1) public Provider Directory API. Practitioner, PractitionerRole, Organization, OrganizationAffiliation, Location, and InsurancePlan resources are exposed without authentication. Per-plan endpoints include 0100, 0500, 0900, 1200, 2100, 2400, 2600.

**Human URL:** [https://developer.amerihealthcaritas.com/](https://developer.amerihealthcaritas.com/)

**Base URL:** `https://api-ext.amerihealthcaritas.com/1200/provider-api`

#### Tags

- Provider Directory, FHIR, Healthcare, CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [CapabilityStatement](https://api-ext.amerihealthcaritas.com/1200/provider-api/metadata)
- [Swagger UI](https://api-ext.amerihealthcaritas.com/1200/provider-api/swagger-ui/?page=All)
- [OpenAPI](openapi/amerihealth-caritas-provider-directory-openapi.yml)
- [Spectral Rules](rules/amerihealth-caritas-rules.yml)
- [Naftiko Capability — Provider Directory](capabilities/amerihealth-caritas-provider-directory.yaml)

### AmeriHealth Caritas Formulary FHIR API

HL7 FHIR R4 Drug Formulary surface satisfying CMS-9115-F drug-formulary publication requirements for Medicaid managed care and D-SNP populations. Public, no authentication required; formulary content is currently navigable through FHIR MedicationKnowledge and List resources.

**Human URL:** [https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)

**Base URL:** `https://api-ext.amerihealthcaritas.com/0500/patient-api`

#### Tags

- Formulary, Drug Formulary, FHIR, Pharmacy Benefits, CMS

#### Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Naftiko Capability — Medications & Formulary](capabilities/amerihealth-caritas-medications-and-formulary.yaml)

### AmeriHealth Caritas Corporate Website

Public corporate website hosting the family-of-plans health plan finder, solutions overview, careers, member and provider portals for the federated state plans, and pointers to the CMS Interoperability developer portal.

**Human URL:** [https://www.amerihealthcaritas.com](https://www.amerihealthcaritas.com)

**Base URL:** `https://www.amerihealthcaritas.com`

#### Properties

- [Website](https://www.amerihealthcaritas.com)
- [Find a Health Plan](https://www.amerihealthcaritas.com/find-a-health-plan)
- [Solutions](https://www.amerihealthcaritas.com/health-care-solutions)
- [Careers](https://careers.amerihealthcaritas.com/us/en)
- [Developer Portal](https://developer.amerihealthcaritas.com/)

## Family of Health Plans

| State | Brand | Line of Business | URL |
|---|---|---|---|
| Delaware | AmeriHealth Caritas Delaware | Medicaid Managed Care | amerihealthcaritasde.com |
| Delaware | AmeriHealth Caritas Next | Marketplace | amerihealthcaritasnext.com/de |
| Delaware | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/de |
| Delaware | AmeriHealth Caritas VIP Care Choice | D-SNP | amerihealthcaritasvipcare.com/de |
| Florida | AmeriHealth Caritas Next | Marketplace | amerihealthcaritasnext.com/fl |
| Florida | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/fl |
| Louisiana | AmeriHealth Caritas Louisiana | Medicaid Managed Care | amerihealthcaritasla.com |
| Louisiana | AmeriHealth Caritas Next | Marketplace | amerihealthcaritasnext.com/la |
| Louisiana | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/la |
| Michigan | Blue Cross Complete of Michigan | Medicaid Managed Care | mibluecrosscomplete.com |
| Michigan | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/mi |
| New Hampshire | AmeriHealth Caritas New Hampshire | Medicaid Managed Care | amerihealthcaritasnh.com |
| New Jersey | PerformCare | Behavioral Health | performcarenj.org |
| North Carolina | AmeriHealth Caritas North Carolina | Medicaid Managed Care | amerihealthcaritasnc.com |
| North Carolina | AmeriHealth Caritas Next | Marketplace | amerihealthcaritasnext.com/nc |
| North Carolina | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/nc |
| Ohio | AmeriHealth Caritas Ohio | Medicaid Managed Care | amerihealthcaritasoh.com |
| Pennsylvania | AmeriHealth Caritas Pennsylvania | Medicaid Managed Care | amerihealthcaritaspa.com |
| Pennsylvania | AmeriHealth Caritas Pennsylvania CHC | LTSS Managed Care | amerihealthcaritaschc.com |
| Pennsylvania | AmeriHealth Caritas VIP Care | D-SNP | amerihealthcaritasvipcare.com/pa |
| Pennsylvania | PerformCare | Behavioral Health | performcare.org |
| Pennsylvania (SE) | Keystone First | Medicaid Managed Care | keystonefirstpa.com |
| Pennsylvania (SE) | Keystone First CHIP | CHIP | keystonefirstchip.com |
| Pennsylvania (SE) | Keystone First VIP Choice | D-SNP | keystonefirstvipchoice.com |
| Pennsylvania (SE) | Keystone First Community HealthChoices | LTSS Managed Care | keystonefirstchc.com |
| South Carolina | First Choice by Select Health | Medicaid Managed Care | selecthealthofsc.com |
| South Carolina | First Choice Next | Marketplace | firstchoicenext.com |
| South Carolina | First Choice VIP Care | D-SNP | firstchoicevipcare.com |
| Washington, D.C. | AmeriHealth Caritas District of Columbia | Medicaid Managed Care | amerihealthcaritasdc.com |

## Per-Plan FHIR Endpoint Codes

Observed via live HTTP probing of `https://api-ext.amerihealthcaritas.com/{code}/{patient-api|provider-api}/metadata`.

| Plan Code | Patient Access | Provider Directory |
|---|---|---|
| 0100 | yes | yes |
| 0500 | yes | yes |
| 0900 | yes | yes |
| 1200 | (no) | yes |
| 2100 | (no) | yes |
| 2400 | yes | yes |
| 2600 | yes | yes |

The mapping between plan code and state plan brand is not publicly documented on the developer portal; the canonical list of brands and states is in the table above.

## Common Properties

- [Portal](https://developer.amerihealthcaritas.com/)
- [Website](https://www.amerihealthcaritas.com)
- [Documentation](https://developer.amerihealthcaritas.com/dvp/v1/apiadditionaldocsinfo/)
- [Find a Health Plan](https://www.amerihealthcaritas.com/find-a-health-plan)
- [Careers](https://careers.amerihealthcaritas.com/us/en)
- [Transparency in Coverage](https://www.amerihealthcaritas.com/about-us/transparency-in-coverage.aspx)
- [GitHub Org (amerihealth)](https://github.com/amerihealth)
- [CMS Interoperability Final Rule](https://www.cms.gov/priorities/key-initiatives/burden-reduction/interoperability)
- [CARIN Blue Button IG](https://hl7.org/fhir/us/carin-bb/history.html)
- [Da Vinci PDex IG](https://hl7.org/fhir/us/davinci-pdex/history.html)
- [USCDI v1](https://www.healthit.gov/isp/united-states-core-data-interoperability-uscdi#uscdi-v1)
- [SMART App Launch 1.0.0](https://hl7.org/fhir/smart-app-launch/1.0.0/)
- [Plans](plans/amerihealth-caritas-plans-pricing.yml)
- [Rate Limits](rate-limits/amerihealth-caritas-rate-limits.yml)
- [FinOps](finops/amerihealth-caritas-finops.yml)
- [Vocabulary](vocabulary/amerihealth-caritas-vocabulary.yml)
- [JSON-LD Context](json-ld/amerihealth-caritas-context.jsonld)
- [Spectral Rules](rules/amerihealth-caritas-rules.yml)

## Artifacts in this repo

- **OpenAPI:** `openapi/amerihealth-caritas-patient-access-openapi.yml`, `openapi/amerihealth-caritas-provider-directory-openapi.yml`
- **Capabilities:** `capabilities/amerihealth-caritas-patient-access.yaml`, `capabilities/amerihealth-caritas-claims-and-eob.yaml`, `capabilities/amerihealth-caritas-medications-and-formulary.yaml`, `capabilities/amerihealth-caritas-provider-directory.yaml`
- **JSON Schema:** `json-schema/amerihealth-caritas-patient-schema.json`, `coverage`, `explanation-of-benefit`, `practitioner`, `organization`, `location`
- **JSON Structure:** `json-structure/amerihealth-caritas-health-plan-structure.json`
- **JSON-LD:** `json-ld/amerihealth-caritas-context.jsonld`
- **Examples:** `examples/amerihealth-caritas-patient-read-example.json`, `coverage-search`, `explanation-of-benefit-search`, `practitioner-search`, `organization-search`, `medication-knowledge-search`
- **Spectral Rules:** `rules/amerihealth-caritas-rules.yml`
- **Vocabulary:** `vocabulary/amerihealth-caritas-vocabulary.yml`
- **Plans / Rate Limits / FinOps:** `plans/`, `rate-limits/`, `finops/`

## Notable Findings

- AmeriHealth Caritas runs three CMS-mandated FHIR R4 APIs (Patient Access, Provider Directory, Drug Formulary) routed per state plan through a four-digit plan code (0100, 0500, 0900, 1200, 2100, 2400, 2600 confirmed live)
- The Patient Access OpenAPI spec is the same 557 KB document shared across plan codes, exposing 22 FHIR resource types and full read / search / vread / history / `$validate` / `$expunge` / `$graphql` operations per resource
- The Provider Directory spec is a 157 KB document covering InsurancePlan, Location, Organization, OrganizationAffiliation, Practitioner, and PractitionerRole, identical across plan codes except for the `servers[].url` value
- AmeriHealth Caritas accounts for $20.2 billion of Independence Blue Cross's $27.4 billion in 2022 revenue and ~9,500 of its ~14,000 employees, per Independence Health Group's January 2024 CEO announcement
- 29 distinct member-facing plan brands map across 10 states plus the District of Columbia, covering Medicaid managed care, CHIP, D-SNP, LTSS, behavioral health, and Marketplace lines of business

## Notable Absences

- No public mapping between the four-digit plan code and the state-plan brand is published on `developer.amerihealthcaritas.com`
- The Drug Formulary API has no separate `formulary-api` path live at `api-ext.amerihealthcaritas.com`; formulary content is currently surfaced via MedicationKnowledge and List inside the Patient Access surface
- No numeric rate limits, no published SLA, no status page, no public changelog, and no RSS feed
- No first-party developer SDKs, CLIs, or Postman collections; the `amerihealth` GitHub org contains a single provider-portal repository
- No public newsroom or blog index at `amerihealthcaritas.com/newsroom`

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
