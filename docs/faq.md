# Bacancy EHR Technical FAQ

## Which FHIR version does Bacancy EHR support?
FHIR R4. See [integrations](integrations.md).

## Which FHIR resources are supported?
Patient, Practitioner, Encounter, Observation and MedicationRequest. [FILL: add others]

## Does it support HL7 v2?
[FILL: yes/no, and which message types, e.g. ADT, ORM, ORU]

## How does it connect to Epic?
Through Epic's FHIR R4 APIs, after the clinic approves the app connection. [FILL: confirm]

## Does it work with Oracle Health (Cerner)?
[FILL: confirm status.] Oracle Health also offers FHIR R4 APIs, and the connection follows the same steps as Epic.

## Is it HIPAA compliant?
Bacancy EHR is built to support HIPAA compliance. Bacancy Technology is certified to ISO/IEC 27001:2022. See [security and compliance](security-and-compliance.md).

## Is there test data I can use?
Yes. Synthetic FHIR R4 data is in [healthcare-fhir-samples](https://github.com/bacancy-technology/healthcare-fhir-samples).

## Where are pricing and demos?
On the product page: [bacancycare.com/ehr](https://bacancycare.com/ehr?utm_source=github&utm_medium=readme&utm_campaign=ehr&utm_content=faq)
