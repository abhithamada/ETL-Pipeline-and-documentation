# ETL-Pipeline-and-documentation
# Healthcare Interoperability ETL Pipeline

**Link to Project Website**: [Project Website](https://pages.github.iu.edu/ajilla/group_2_project/)

## Introduction
This project focuses on the development and execution of an ETL (Extract, Transform, Load) pipeline to facilitate interoperability between two healthcare systems using FHIR (Fast Healthcare Interoperability Resources) standards. The pipeline enables efficient data exchange, transformation, and integration of patient and clinical data between OpenEMR and a Primary Care EHR system.

## Purpose
The ETL pipeline aims to streamline the process of accessing patient and clinical data, enriching it with terminology services, and ensuring seamless integration into target systems. By leveraging FHIR APIs, this project demonstrates how healthcare data can be standardized and shared across systems to enhance clinical workflows and healthcare interoperability.

## Tools and Technologies
- **Python**: Used for scripting, API interaction, and data transformation.
- **OAuth2.0**: Used for obtaining authorization, access tokens, and refresh tokens needed to access the OpenEMR FHIR API.
- **FHIR API**: Enables communication with OpenEMR and Primary Care EHR systems for resource management.
- **Hermes Terminology Server**: Facilitates terminology mapping for medical concepts like parent and child terms.
- **Postman**: Used for testing API endpoints and validating JSON structures.

## Summary of Deliverables
1. **ETL Pipeline**: 
   - Implementation of a pipeline that extracts data from OpenEMR, transforms it to meet the target system’s requirements, and loads it into the Primary Care EHR system.

2. **Patient and Condition Resources**:
   - Creation of patient records and associated conditions, with hierarchical term mappings for enhanced data semantics.

3. **Observation and Procedure Resources**:
   - Addition of vital signs and clinical procedures to enrich patient profiles.

4. **Documentation**:
   - Comprehensive documentation detailing the pipeline process, coding tasks, challenges, and solutions.

5. **Code Repository**:
   - A well-documented GitHub repository containing code snippets, JSON files, and project artifacts for easy reproducibility.

This project showcases the practical application of FHIR standards to enable robust and interoperable healthcare data systems.
