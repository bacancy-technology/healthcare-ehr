# BacancyCare EHR Technical FAQ

## Which interoperability standards are supported?
FHIR R4 with USCDI v3, HL7v2 (ADT, ORU, ORM, SIU, DFT, MDM, VXU) and REST APIs. See [integrations](integrations.md).

## Can it work alongside our current EHR?
Yes. It connects to Epic, Oracle Health (Cerner), eClinicalWorks, athenahealth, Meditech, Allscripts, DrChrono, NextGen, Kareo, AdvancedMD and specialty EMRs.

## Where is it hosted?
On your own servers or a private cloud account in your name. Bacancy holds no patient records.

## How is a video visit kept secure?
Video is end-to-end encrypted with SRTP/DTLS, and no PHI is stored on the video provider's systems.

## How long does implementation take?
2–4 weeks for a single clinic, 4–8 weeks for a multi-provider group, and 10–16 weeks for a health system.

## Can we put our own brand on it?
Yes. The platform can be white-labelled.

## Which AI model does it use?
The AI layer is model-agnostic, so the language model can be changed without rebuilding the platform.

## What happens to our data if we stop using it?
You keep your data, because it runs on your servers.

## Is there test data I can use?
Yes. Synthetic FHIR R4 data is in [healthcare-fhir-samples](https://github.com/bacancy-technology/healthcare-fhir-samples).

## Where are pricing and demos?
Product page: [bacancycare.com/ehr](https://bacancycare.com/ehr?utm_source=github&utm_medium=readme&utm_campaign=ehr&utm_content=faq) · Live demo: [healthsolution.gobacancy.com](https://healthsolution.gobacancy.com/)
