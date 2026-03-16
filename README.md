# Matthew Brunsdon

Senior developer specialising in **Dynamics 365, Power Platform, Power Pages and Azure integration architectures**.

I design and build enterprise systems that expose **Dataverse and Dynamics 365 data through secure portals, APIs and event-driven cloud architectures**.

Currently delivering Dynamics solutions in government environments and building reusable resources for the Power Platform developer community.

---

## Technologies

![Dynamics](https://img.shields.io/badge/Dynamics%20365-0F6CBD?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Platform](https://img.shields.io/badge/Power%20Platform-742774?style=for-the-badge&logo=powerapps&logoColor=white)
![Power Pages](https://img.shields.io/badge/Power%20Pages-742774?style=for-the-badge&logo=microsoft&logoColor=white)
![Dataverse](https://img.shields.io/badge/Dataverse-0F6CBD?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

---

# Focus Areas

• **Power Pages portal architecture**  
• **Dynamics 365 / Dataverse development**  
• **Power Platform integrations**  
• **Azure event-driven architectures**  
• **Enterprise CRM and government systems**

---

# Featured Repositories

### Pinned repositories

These are my currently highlighted/pinned projects on GitHub — useful starting points if you're working with Power Pages, Dataverse or integrations.

 - [power-pages-cheat-sheet](https://github.com/brunsdon/power-pages-cheat-sheet) — Practical guidance for developers building portals with Power Pages and Dataverse.  
 - [power-pages-liquid-examples](https://github.com/brunsdon/power-pages-liquid-examples) — A collection of Liquid snippets and examples for Power Pages templating.
 - [dynamics365-developer-cheat-sheet](https://github.com/brunsdon/dynamics365-developer-cheat-sheet) — Quick reference for Dynamics 365 development including plugins, Web API and solution management.
 - [power-platform-integration-patterns](https://github.com/brunsdon/power-platform-integration-patterns) — Architecture patterns for integrating Power Platform with Azure services and external systems.
 - [dataverse-query-examples](https://github.com/brunsdon/dataverse-query-examples) — Practical Dataverse Web API query examples including filtering, expands and CRUD operations.
 - [dataverse-schema-design-guide](https://github.com/brunsdon/dataverse-schema-design-guide) — Guidance for designing scalable Dataverse schemas for Dynamics and Power Platform systems.

### Power Platform

- **power-pages-cheat-sheet**  
  Practical guidance for developers building portals with Power Pages and Dataverse.

- **dynamics365-developer-cheat-sheet**  
  Quick reference for Dynamics 365 development including plugins, Web API and solution management.

- **power-platform-integration-patterns**  
  Architecture patterns for integrating Power Platform with Azure services and external systems.

---

### Dataverse

- **dataverse-query-examples**  
  Practical Dataverse Web API query examples including filtering, expands and CRUD operations.

- **dataverse-schema-design-guide**  
  Guidance for designing scalable Dataverse schemas for Dynamics and Power Platform systems.

---

# Architecture Interests

I am particularly interested in architectures combining:

```mermaid
flowchart TD
  %% Nodes (top-down)
  PP["Power Pages<br/>(Portal)"]:::portal
  DV["Dataverse<br/>(Datastore)"]:::datastore
  ASB["Azure Service Bus<br/>(Messaging)"]:::messaging
  AF["Azure Functions<br/>(Compute)"]:::compute
  ES["External enterprise systems<br/>(API / ERP)"]:::external

  %% Edges with labels
  PP -->|Writes data| DV
  DV -->|Publishes message| ASB
  ASB -->|Queue / Topic trigger| AF
  AF -->|Calls / Integrates with| ES

  %% Styling
  classDef portal fill:#742774,stroke:#333,color:#fff,stroke-width:1px;
  classDef datastore fill:#0F6CBD,stroke:#333,color:#fff,stroke-width:1px;
  classDef messaging fill:#F6A623,stroke:#333,color:#000,stroke-width:1px;
  classDef compute fill:#512BD4,stroke:#333,color:#fff,stroke-width:1px;
  classDef external fill:#94A3B8,stroke:#333,color:#000,stroke-width:1px;
```

---

# Current Focus

Building resources and tools for developers working with:

- Power Pages
- Dataverse
- Dynamics 365
- Power Platform integration architectures

---

# Availability

Open to **remote contract engagements** involving:

• Dynamics 365  
• Power Platform  
• Power Pages portals  
• Dataverse integrations  
• Azure-based architectures