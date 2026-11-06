# BacancyCare EHR Overview

BacancyCare EHR covers the full patient journey in one system: symptom check, booking, insurance check, consultation, lab and pharmacy orders, follow-up and payment. It runs on the customer's own servers or private cloud, so Bacancy holds no patient records.

## The 5 portals
| Portal | Who uses it | What it covers |
|---|---|---|
| Patient Portal | Patients | Sign-up, symptom check, find a doctor, book in person / video / phone, insurance and prior auth status, cost estimates, payments, pharmacy orders |
| Doctor Portal | Doctors | Schedule and queue across all their clinics, consultation workspace with history and vitals, prescriptions, video visits, slots and leave, earnings |
| Laboratory Portal | Partner labs | Verified onboarding, incoming orders from consultations, home sample collection |
| Pharmacy Portal | Partner pharmacies | Licence-verified onboarding, inventory, order tracking, pickup and delivery |
| Super Admin Panel | Clinic operations | Finance, claims, revenue, quality, triage, AI escalations, lab and pharmacy approvals |

Patients can also book as a guest. The account is created during booking.

## The patient journey
1. **Symptom check:** the patient describes symptoms and is matched to a doctor.
2. **Book and verify:** insurance is checked, a cost estimate is shown, and the patient pays online, in cash or by insurance.
3. **Consultation:** in person, video or phone.
4. **Orders fulfilled:** lab and pharmacy orders go out. Pharmacy orders move through New → Accepted → Preparing → Ready → Out for delivery → Completed.
5. **Follow-up and pay:** a prescription PDF is issued when the visit closes.

## AI capabilities
| Capability | What it does |
|---|---|
| Symptom check and doctor matching | Matches the patient to the right specialist |
| AI photo review | Flags urgency from a photo. Labelled in the app as not a diagnosis. |
| Patient assistant | Answers questions on fees, hours, insurance and rescheduling |
| Doctor assistant | Handles emergency schedule changes |
| AI receptionist and scheduling | Books by voice, chat and SMS, without double booking |
| Consultation transcripts | Saved only with patient consent |
| AI escalations and triage | Sends urgent cases to staff |

The AI layer is model-agnostic, so the language model can be swapped without rebuilding the platform.

## Who it's for
Single clinics, multi-provider and multi-location groups, health systems and hospital networks, telemedicine providers, and labs and pharmacies that join as verified partners. The platform can be white-labelled with the client's brand.

Full product details: [bacancycare.com/ehr](https://bacancycare.com/ehr?utm_source=github&utm_medium=readme&utm_campaign=ehr&utm_content=overview)
