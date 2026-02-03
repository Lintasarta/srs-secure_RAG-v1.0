# Scope

This document outlines the boundaries for the initial release of Deka Secure RAG. It specifies the features and capabilities that will be included in Version 1.0.

**In-Scope:**

- A data anonymization and de-anonymization engine powered by F5 BIG-IP to intercept and protect data in transit to external services.
- Support for configurable data patterns for anonymization (e.g., SSN, Credit Card Numbers, Custom Regex).
- A comprehensive security stack providing protection against OWASP Top 10 vulnerabilities for Web Apps, APIs, and LLMs.
- Secure Multi-Cloud Networking (MCN) for secure connectivity.
- Integration with Lintasarta DekaLLM and compatibility with standard RAG orchestration frameworks like LangChain and LlamaIndex.
- Deployment within an enterprise Data Center or Private Cloud environment.
- Monitoring and logging capabilities for security events and anonymization process performance.
- Three distinct tiered packages (Advance, AI-Enhanced, Ultimate Privacy) with defined features and token limits.

**Out-of-Scope:**

- A self-service user interface for creating and managing custom anonymization patterns in real-time.
- Direct integration with third-party SIEM systems beyond providing logs for manual integration.
- Automated billing and subscription management portal.
- Support for deployment on public cloud infrastructure as a fully managed service.
