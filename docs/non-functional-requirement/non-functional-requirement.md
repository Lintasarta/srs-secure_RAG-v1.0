# Non-Functional Requirements

| ID     | Requirements      | Needs |
|--------|-------------------|-------|
| NF-001 | Availability      | The system security components must be highly available, designed for 24/7 operation to prevent service disruption. |
| NF-002 | Languages         | All user-facing text in applications and documentation must be in English. |
| NF-003 | Security          | The system must provide robust, multi-layered security, protecting against OWASP Top 10 risks for Web, API, and LLMs. All data in transit outside the enterprise network must be encrypted. |
| NF-004 | Performance       | The anonymization and de-anonymization processes must introduce minimal and predictable latency to the overall RAG query lifecycle to ensure a smooth user experience. |
| NF-005 | Compliance        | The system must enable organizations to comply with data privacy regulations, specifically Indonesia's PDP law (UU No. 27 Tahun 2022), by preventing sensitive data from leaving the enterprise boundary. |
| NF-006 | Data Sovereignty  | The system must ensure that original, sensitive data and the cryptographic keys used for anonymization remain within the enterprise's controlled environment at all times. |
| NF-007 | Scalability       | The solution must be scalable to handle varying loads, with performance and capacity defined by the selected tiered package (Advance, AI-Enhanced, Ultimate Privacy). |
| NF-008 | Auditability      | The system must generate audit logs for all configuration changes related to security policies and anonymization rules. |
