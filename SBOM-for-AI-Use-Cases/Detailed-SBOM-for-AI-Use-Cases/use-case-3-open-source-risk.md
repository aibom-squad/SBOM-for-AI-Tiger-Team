# Use Case 3: Assessing Risk in Open-Source Models & Datasets

[Back to Table of Contents](../../README.md#table-of-contents)

## Problem Statement

Organizations are increasingly incorporating open-source AI models and datasets to accelerate development and reduce costs. These assets, much like third-party software, become part of the organization’s supply chain and must be properly vetted and managed.

However, open-source models and datasets often lack transparency about their provenance, composition, licensing, and training data, introducing serious risks—including regulatory non-compliance, bias propagation, legal exposure, and supply chain vulnerabilities. Current practices such as manual documentation reviews, limited testing, and community-based reputation checks are time-consuming, inconsistent, and fail to provide a complete picture.

To effectively assess and manage these risks, organizations need a standardized, machine-readable way to capture and evaluate critical metadata. An SBOM for AI enables this by offering structured transparency into the origins, modifications, and risks associated with AI assets—empowering security, legal, and compliance teams to make informed decisions and strengthen trust in the AI ecosystem.
<br><br>

## Benefits

*   **Holistic Transparency** – Delivers structured insights into where AI models and datasets come from, how they were built, and what risks may be involved.

*   **Better Risk Control** – Enables early detection of vulnerabilities, unauthorized components, or problematic licenses before models are used in production.

*   **Streamlined Workflows** – Reduces manual review and improves consistency in assessments by integrating SBOM data into automated risk, security, and governance processes.

*   **Simplified Compliance** – Supports alignment with regulatory frameworks and internal data governance policies by providing clear audit trails.

*   **Stronger Stakeholder Confidence** – Demonstrates diligence in how open-source AI assets are evaluated, boosting trust across internal and external stakeholders.
<br><br>

## Example Scenarios

**Scenario 1: Preventing License Violations**

A development team plans to integrate an open-source language model into its product. By consulting the SBOM for AI, the team discovers the model is trained on datasets with conflicting licenses that are incompatible with its product’s commercial use. The team opts to use a different model, avoiding potential legal disputes and product launch delays.

**Scenario 2: Mitigating Supply Chain Risk**

An AI developer intends to incorporate an open-source model into the developer’s application. The SBOM for AI identifies the model’s owner or author, which can then be used for trust analyses and model integrity checks to detect any tampering.  Armed with this information, the developer decides to choose a different/more secure model, thereby preventing potential  supply chain risk.

**Scenario 3: Model Lineage and Model Provenance** 

A financial institution considers using an open-source model as a base for a credit scoring system. The SBOM for AI reveals the model’s lineage—it is a fine-tuned version of another base model—and also its provenance, including the origin and development path of both models. This information highlights that the base model violates the institution’s internal risk policies, preventing its adoption.

