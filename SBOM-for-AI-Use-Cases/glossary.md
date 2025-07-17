# Appendix A – SBOM for AI Glossary and Terminology

[Back to Table of Contents](../README.md#table-of-contents)

The SBOM for AI Use Cases White Paper is intended for readers from diverse backgrounds and disciplines. To ensure clarity and consistency, this glossary defines key terms that may have varying interpretations across different fields, providing a common reference point for understanding SBOM for AI concepts.

For general cybersecurity terms, readers should consult established references such as [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final); this glossary does not attempt to redefine well-established cybersecurity terminology.
<br><br>

| Term | Definition |
|---|---|
| AI System | From 15 USC 9401(3)(e): Any data system, software, hardware, application, tool, or utility that operates in whole or in part using AI. From EU AI Act (2024/1689) Article 3: A machine-based system that is designed to operate with varying levels of autonomy and that may exhibit adaptiveness after deployment, and that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments. |
| Artificial Intelligence (AI) | From 15 USC 9401(3)(b): A machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations, or decisions influencing real or virtual environments. AI systems use machine and human-based inputs to: (A) perceive real and virtual environments; (B) abstract such perceptions into models through analysis in an automated manner; (C) use model inference to formulate options for information or action. Commentary: The SBOM for AI project focuses specifically on statistical machine learning systems. These generate and use statistical models based on large quantities of training data (e.g., deep neural networks). SBOM for AI may also apply to other AI techniques such as planning, logic, and optimization. Alternative Definitions: ISO/IEC 22989:2022 - A technical and scientific field devoted to the engineered system that generates outputs such as content, forecasts, recommendations, or decisions. |
| Bias | From OECD: An effect which deprives a statistical result of representativeness by systematically distorting it, as distinct from a random error which may distort on any one occasion but balances out on average. Commentary: Bias can refer to datasets, models, or AI system outputs that unfairly advantage or disadvantage a group. It may be difficult to define unbiased data in different contexts. Alternative Definitions: Inductive Bias - The set of assumptions that a learning system uses to interpolate and extrapolate from training data. |
| Bill of Materials (BOM) | Adapted from DHS-CISA SBOM FAQ: A formal record containing details and supply chain relationships of various components used in building a system, including libraries, modules, models, training data, and knowledge sources. |
| HDO | Healthcare Delivery Organization (such as Hospital or Clinic). |
| Machine Learning | From 15 USC 9401(11): An application of artificial intelligence that provides systems with the ability to automatically learn and improve on the basis of data or experience, without being explicitly programmed. |
| Model lineage | Tracks the full chain of derivation — how the model has been modified, fine-tuned, retrained, or otherwise transformed over time, including its dependencies on other models. Consider this as a model’s “family tree” or evolution over time. |
| Model provenance | Refers to the origin and history of the model itself — who created it, when, under what conditions, with what datasets and licenses. Consider this as a model’s “birth certificate.” |
| Policy | In SBOM for AI, policy refers to the rules, guidelines, and best practices governing the behavior of an organization and its AI-related activities. The policy may or may not be codified. Alternative Definitions: Management Policy - Rules that govern an organization\'s behavior. IT Policy - Rules for accessing and using IT resources. ML/AI System Policy - Strategies defining an agent’s decision-making process. |
| Vulnerability | From NIST SP 800-53 Rev. 5: A weakness in an information system, security procedures, internal controls, or implementation that could be exploited by a threat source. |


