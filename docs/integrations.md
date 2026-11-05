# Bacancy EHR Integrations

| System | Standard | What moves between systems | Status |
|---|---|---|---|
| Any FHIR server | FHIR R4 | Patients, practitioners, encounters, observations, medication requests | [FILL] |
| HL7 v2 systems | HL7 v2 | Admissions, orders, results | [FILL] |
| Epic | FHIR R4 | Patient records and clinical data | [FILL] |
| Oracle Health (Cerner) | FHIR R4 | Patient records and clinical data | [FILL] |
| Laboratories | HL7 v2 / FHIR R4 | Lab orders and results | [FILL] |
| Pharmacies | [FILL] | Prescriptions | [FILL] |

## How an integration project runs
1. **Scope:** list the systems and the data that needs to move.
2. **Map:** match fields between Bacancy EHR and the other system.
3. **Build and test:** connect in a test environment using synthetic data.
4. **Go live:** switch to production after sign-off.

## For developers
Synthetic FHIR R4 examples and API calls: [healthcare-fhir-samples](https://github.com/bacancy-technology/healthcare-fhir-samples)
