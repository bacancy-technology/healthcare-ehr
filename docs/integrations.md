# BacancyCare EHR Integrations

BacancyCare EHR connects through FHIR R4 (USCDI v3), HL7v2 messaging and REST APIs. The Bacancy team sets up integrations during implementation.

## Standards
| Standard | Details |
|---|---|
| FHIR R4, USCDI v3 | Resources include Patient, Encounter, Observation, Coverage |
| HL7v2 | ADT, ORU, ORM, SIU, DFT, MDM, VXU messages |
| REST APIs | For systems without FHIR or HL7 support |
| Da Vinci PAS | Prior authorization, ready for CMS-0057-F |
| TEFCA | Ready for QHIN participation |

## EHR and EMR systems
| System | How it connects |
|---|---|
| Epic | Interconnect, FHIR, Care Everywhere, App Orchard |
| Oracle Health (Cerner) | Millennium APIs, HL7v2, FHIR R4 |
| eClinicalWorks | HL7v2, FHIR R4 |
| athenahealth | athenaOne REST API |
| Meditech, Allscripts | HL7v2, FHIR R4 |
| DrChrono, NextGen, Kareo, AdvancedMD | Supported. Method set during implementation. |
| Specialty EMRs | Dentrix, Open Dental, WebPT, SimplePractice |

## Other connections
| Area | Systems |
|---|---|
| Clearinghouses | Availity, Change Healthcare, Office Ally |
| E-prescribing | Surescripts, with standard SIG routing |
| Payments | Stripe, Adyen and other PCI-DSS gateways |
| Labs and pharmacies | Join the network through the Laboratory and Pharmacy portals, after admin approval |

## How an integration project runs
1. **Scope:** list the systems and the data that needs to move.
2. **Map:** match fields between BacancyCare EHR and the other system.
3. **Build and test:** connect in a test environment using synthetic data.
4. **Go live:** switch to production after sign-off.

| Setup | Typical timeline |
|---|---|
| Single clinic | 2–4 weeks |
| Multi-provider group | 4–8 weeks |
| Health system | 10–16 weeks (pilot available) |

## For developers
Synthetic FHIR R4 examples and API calls: [healthcare-fhir-samples](https://github.com/bacancy-technology/healthcare-fhir-samples)
