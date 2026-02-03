# Communication Interface

- **End-User to Frontend:** Standard HTTPS communication.
- **Frontend to LLM Orchestrator:** Secure API calls (e.g., REST, GraphQL) within the enterprise network.
- **LLM Orchestrator to F5 BIG-IP:** Internal network traffic routed through the F5 BIG-IP as a gateway.
- **F5 BIG-IP to External Services (LLMaaS, Embedding Models):** Secure, encrypted traffic over HTTPS. The F5 BIG-IP applies security policies and data anonymization before forwarding requests.
- **LLM Orchestrator to VectorDB:** Standard database connection protocols. The F5 BIG-IP may intercept this traffic if the VectorDB is an external SaaS offering.
