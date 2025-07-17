# Use Case 1: Compliance

[Back to Table of Contents](../../README.md#table-of-contents)

## Problem Statement

AI systems are complex, dynamic, and often opaque. Regulators, auditors, and other stakeholders are increasingly demanding greater transparency into how AI models are built, trained, and maintained. Compliance with SBOM and AI-specific regulations—such as the [Federal Acquisition Regulation (FAR)](https://www.federalregister.gov/documents/2023/10/03/2023-21328/federal-acquisition-regulation-cyber-threat-and-incident-reporting-and-information-sharing), the [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai), [U.S. Food and Drug Administration (FDA) Guidance](https://www.fda.gov/medical-devices/software-medical-device-samd/transparency-machine-learning-enabled-medical-devices-guiding-principles), and industry-specific guidelines (e.g., [HHS ONC HTI-1 in healthcare](https://www.healthit.gov/topic/laws-regulation-and-policy/health-data-technology-and-interoperability-certification-program)—requires a clear, traceable record of every component used throughout AI development and deployment.

Without a comprehensive SBOM for AI, organizations face several challenges:

- **Limited Transparency** – Difficulty tracking the origin, purpose, and dependencies of AI components used in production systems.
- **Compliance Gaps** – Inability to demonstrate adherence to regulatory requirements related to accountability, explainability, and fairness.
- **Audit Complexity** – Responding to audits becomes a manual and time-consuming task due to the lack of structured AI documentation.
- **Regulatory Risk** – Non-compliance can lead to legal penalties, reputational damage, and operational disruptions.
- **Manual Overhead** – Tracing AI system components without automation consumes significant resources and expertise.
<br><br>

## Benefits

SBOM for AI provides a structured, machine-readable inventory of AI components—enabling compliance, auditability, and operational control.

Key benefits include:

- **Compliance Assurance** – Demonstrates adherence to traceability, fairness, and transparency requirements across evolving regulatory frameworks.
- **Streamlined Audits** – Reduces time, effort, and cost in responding to regulatory and internal audits.
- **Improved Risk Management** – Helps identify non-compliant or unauthorized components before they enter production.
- **Efficiency Gains** – Supports automation of documentation, monitoring, and reporting workflows.
- **Trust and Accountability** – Builds confidence with regulators, partners, and customers through clear, verifiable records of AI system components.
<br><br>

## Example Scenarios

### Scenario 1: Ensuring Compliance for AI-enabled Medical Wearable Devices

A medical technology company develops an AI-powered wearable device that monitors heart activity to detect early signs of arrhythmia. This device, classified as a medical device by the US Food and Drug Administration (FDA), must comply with the agency’s stringent guidelines regarding software safety, efficacy, and security.
<br><br>

### Software Validation and Verification

FDA regulations require rigorous validation and verification of software used in medical devices to ensure their safety and efficacy. By using an SBOM for AI, the company documents every software component, library, and model used in the device’s AI system.
<br><br>

### Regulatory Submissions and Documentation

For FDA approval, the company must submit comprehensive documentation, including details of the AI algorithms and software architecture of every component. While an SBOM for AI does not replace this documentation, it provides a machine-readable inventory of components, simplifying the regulatory submission process by supporting software traceability and ensuring visibility into dependencies and provenance. 

The SBOM helps the company adhere to the FDA’s Premarket Approval (PMA) or 510(k) pathways, providing information that allows the company to review the list of included components and ensure such components meet regulatory requirements.
<br><br>

### Post-Market Surveillance and Updates

FDA regulations require ongoing monitoring and updates for medical devices after they are launched. If the AI-powered wearable device requires a software update (e.g., to improve algorithm performance or address a vulnerability), the SBOM for AI ensures that the changes are clearly documented and that the updated components remain compliant with FDA regulations.
<br><br>

### Third-Party Vendor Compliance

The wearable device uses third-party components and libraries for its AI functions. The SBOM for AI makes it possible to check third-party AI software used for compliance with FDA regulations, and the company can verify that its suppliers are following best practices for medical device software security and quality.
<br><br>

## Outcome

By ensuring that the elements in the SBOM for AI meet the appropriate compliance requirements, a company can confidently demonstrate to the FDA that the AI-powered wearable device aligns with regulatory standards for software safety, security, and efficacy. This transparency can streamline the approval process, reduce associated costs, and support patient safety by enabling effective processes for identifying and managing risks related to AI components.
