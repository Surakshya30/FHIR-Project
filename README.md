# FHIR-Based Postnatal Care (PNC) Digitalization Project – Nepal

This project aims to develop a structured, HL7 FHIR-compliant digital model for documenting **Postnatal Care (PNC)** services in Nepal, enabling better data collection, interoperability, and integration with national health systems.

---

## Objective

To map Nepal’s paper-based PNC records to standardized **FHIR resources**, enabling the digital transformation of maternal and child health documentation across the country.

---

##  Project Components

### 1.FHIR Resource JSON Files
- **Oservation_Profile_Validated.json**: Validated FHIR Observation profile for postnatal health indicators.
- **Patient Resource**: Captures demographic data for mother and child.
- **Questionnaire Resource**: Structured data entry form grouped into demographics, maternal status, newborn assessments, advice, and referrals.

### 2.Excel Data Dictionary
- `PNC PATIENT PROFILE.xlsx` provides:
  - Mapping of PNC fields to FHIR resource paths
  - Data types, cardinality, constraints
  - Required vs optional fields
  - Terminology bindings (e.g., SNOMED CT)

### 3.Documentation
- Explanation of methodology, tools used, challenges, and validation steps.
- Scans of official HMIS forms used as references for mapping.

---

## Tools & Technologies

- **FHIR Standard (R4)** by HL7
- **Excel**: For data dictionary design
- **JSON**: To represent FHIR resources
- **FHIR Validator**: For resource validation
- **GitHub**: Version control and collaboration

---

## Reference Materials

- Official **PNC HMIS forms** (Nepal)
- WHO guidelines on postnatal care
- HL7 FHIR documentation

---

## Outcomes

- Digitally structured, FHIR-compliant PNC documentation system
- Standardized data entry using `Questionnaire` resource
- Validated and reusable data model for maternal and newborn care
- Open-source repository for reuse and scale-up

---



