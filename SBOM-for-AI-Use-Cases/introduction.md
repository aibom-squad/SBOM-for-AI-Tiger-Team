# Introduction

## What is an SBOM for AI?

An SBOM for AI (Software Bill of Materials for (Artificial Intelligence) is an extension of a traditional SBOM—defined in resources such as [CISA’s “Framing Software Component Transparency: Establishing a Common Software Bill of Materials (SBOM)” (2024)](https://www.cisa.gov/sites/default/files/2024-10/SBOM%20Framing%20Software%20Component%20Transparency%202024.pdf)—designed to provide transparency, security, and compliance for AI systems. It is machine-readable (e.g., JSON, XML formats) and aligns with existing SBOM frameworks, incorporating AI-specific fields such as model metadata, training data, and inference behaviors.

An SBOM for AI includes detailed information such as the type and provenance of training data, model architecture and versioning, base or parent models, hyperparameters, dependencies on external libraries or APIs, model inference characteristics, and deployment configurations. Crucially, an SBOM for AI is not a new standalone standard; rather, it integrates seamlessly with established, open, and globally recognized standards such as SPDX (Software Product Data eXchange, including AI and Dataset Profiles) and CycloneDX (including ML-BOM extensions).

The need for AI component traceability and transparency, which SBOM for AIs aim to address, is increasingly reflected in leading AI security and governance frameworks, including [NIST’s AI Risk Management Framework](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf), [OWASP Top 10 for LLM security](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/), [CISA\'s Secure AI guidance for critical infrastructure](https://www.dhs.gov/sites/default/files/2024-04/24_0426_dhs_ai-ci-safety-security-guidelines-508c.pdf), and [National Cyber Security Centre (NCSC) secure AI development code of practice implementation guidance](https://assets.publishing.service.gov.uk/media/679cae441d14e76535afb630/Implementation_Guide_for_the_AI_Cyber_Security_Code_of_Practice.pdf). While \'SBOM for AI\' as a term is still emerging, the underlying principles are gaining traction and are actively being explored by initiatives like CISA’s SBOM for AI Tiger Team.
<br><br>

## Out of scope of SBOMs for AI

SBOMs for AI are not intended to capture every detail about an AI system. Just like traditional SBOMs, they do not include vulnerabilities, risk assessments, or mitigations. Their purpose is to provide a structured view of model or dataset metadata, while security analysis and risk scanning should be handled by separate tools.

This document focuses on the use cases for SBOMs for AI and does not cover implementation details, nor does it explore whether or how to incorporate additional data or capabilities beyond the core SBOM concept.
