# Rahul Bhattad

**Location:** Canada (Permanent Resident — Authorized to work without sponsorship)  
**Mobile:** (647) 393-7415  
**Email:** [rahulbhattad2003@gmail.com](mailto:rahulbhattad2003@gmail.com)  
**LinkedIn:** [linkedin.com/in/rahul-bhattad](https://www.linkedin.com/in/rahul-bhattad/)  
**Live Portfolio:** [rb3123.github.io/myresume](https://rb3123.github.io/myresume)  

---

## Professional Summary

**Lead Solutions Architect & Forward Deployed Engineer** *(Corporate Title: Lead Consultant)*  
*CCIE #37708 (Alumni / Inactive)*

High-impact Solutions Architect, Forward Deployed Engineer, and NetDevOps Practitioner with 15+ years of enterprise infrastructure experience, including 7+ years pioneering network automation, GitOps pipelines, big data analytical architectures, and modern SDLC governance. Operating as an embedded Forward Deployed Engineer directly inside Fortune 100 enterprise network operations—diagnosing operational friction on the front lines and translating complex operational challenges into production software, resilient microservices, and automated workflows.

Proven track record delivering **$1.6M+ in hard cost savings**, automating **300,000+ global network interfaces**, and saving **1.25 million engineering hours** across global enterprise environments. Demonstrated technical leadership authoring foundational **Architecture Decision Records (ADRs)**, establishing organizational SDLC standards, and serving as Technical Lead & Squad Architect for a 6-engineer full-stack team. Expert in bridging enterprise networking (Cisco, Fortinet, Palo Alto, Zscaler, Aruba, Infoblox) with modern cloud and data engineering (Python, AWS Serverless, DuckDB-WASM, Parquet, Terraform, Spacelift, Docker, CI/CD).

---

## Core Competencies & Technical Skills

- **Architecture, SDLC & Governance:** Architecture Decision Records (ADRs), Enterprise SDLC Frameworks, Gitflow Governance, Systems Design, Cost/Performance Optimization, Value Stream Assessment.
- **Cloud, Data & Distributed Systems:** AWS (Lambda, Step Functions, Batch, API Gateway, CloudFront, DynamoDB, S3, Athena), Parquet, Client-Side DuckDB-WASM, Terraform, Spacelift Stacks, AWS Account Factory for Terraform (AFT), Docker.
- **Network as Code (NaC) & GitOps:** Declarative Configuration Management, Cisco IOS-XE Parsing into Vendor-Agnostic YAML Data Models, Jinja2 Templating, Configuration Drift Scoring (`ciscoconfparse2`), Property-Based Testing (`Hypothesis`, `pytest`).
- **Applied AI & Emerging Tech (R&D):** Model Context Protocol (MCP), Autonomous AI Agents for Infrastructure Telemetry, Context-Aware Closed-Loop Remediation Prototypes, Local LLM Integration (Ollama), Context Engineering.
- **Enterprise Networking & Security:** Cisco Catalyst & Nexus Switches, IOS-XE/AireOS Wireless, Cisco ISE, Cisco DNA Center (DNAC), Fortinet (FortiGate, FortiManager, FortiAnalyzer), Palo Alto Networks, Zscaler (ZIA/ZPA), Aruba Edge Connect SD-WAN, Infoblox BloxOne DDI, PAC Files, TCP/IP.
- **Software Engineering & Scripting:** Python (FastAPI, Flask, Django, Multiprocessing), REST APIs, JSON-RPC, Netmiko, Nornir, NAPALM, TextFSM, Netconf, Restconf, gRPC, React.js, TypeScript, Tailwind CSS.
- **ITSM, Observability & Asset Lifecycle:** ServiceNow (SNOW) API Integration, Cisco Smart Net Total Care (SNTC) EoX Lifecycle Scraping, SolarWinds, Splunk, LogScale, SNMP, Syslog.
- **Technical Leadership:** Squad Architect & Technical Lead for 6 full-stack engineers; enterprise trainer and coach for 40+ network engineers transitioning to software-defined infrastructure.

---

## High-Impact Project Highlights

- **Big Data Audit Analytics & Storage Architecture (ADR 0001):**  
  Authored the approved Architecture Decision Record (ADR) re-architecting the enterprise network audit data platform. Replaced legacy on-prem runners and relational databases with an AWS serverless architecture (Step Functions, Batch, S3, Athena, DynamoDB). Benchmarked and implemented **175x data compression** (199 MB JSON $\rightarrow$ 1.14 MB zstd Parquet) across 665,000+ device-KPI evaluations per run, delivering zero-latency dashboard analytics via **client-side DuckDB-WASM** directly in the browser.

- **Enterprise SDLC & Engineering Governance Framework:**  
  Architected and institutionalized a comprehensive, end-to-end SDLC framework across the network automation organization. Established structured requirement intake models, GitHub Projects governance, standard ADR templates, engineering guidelines, and automated release validation workflows.

- **Enterprise Network Compliance & Automated Remediation Engine:**  
  Engineered an automated audit platform evaluating daily configurations across **3,000+ switches, 10,000+ WAPs, 30+ WLCs, and 200+ firewalls** across 200+ compliance KPIs. Proactively identified security vulnerabilities, **saving 1.25 million hours** of senior engineering time. Designed automated remediation compilers (`auto-kpi-fix`) that generate executable remediation scripts to bring non-compliant devices back to baseline.

- **Global NAC Rollout Automation (One-Click Port Provisioning):**  
  Built a centralized automation engine executing **300,000+ switch interface reconfigurations** globally. Reduced project delivery timeline from 20 months to 3 months (30x acceleration), eliminated human error during cutovers, and achieved **$500K in direct cost savings**.

- **Network GitOps & Configuration Normalization Engine:**  
  Developed a high-performance multiprocessing Python engine parsing raw Cisco running configurations into vendor-agnostic YAML data models. Integrated Jinja2 templating for standard configuration rendering, drift analysis engines using `ciscoconfparse2`, and property-based test suites using `Hypothesis` and `pytest`.

- **Automated Firewall Policy Validator & Orchestrator:**  
  Created an automated validation tool resolving firewall change requests against zone topologies and policy matrices. Implemented a two-phase architecture: Phase 1 evaluates rule overlap and compiles action plans with exact JSON-RPC payloads; Phase 2 executes automated policy updates via FortiManager APIs.

- **Network Configuration Builder & Zero-Touch Provisioning (ZTP):**  
  Created an end-to-end web provisioning platform integrating Infoblox DDI, CMDB, and SolarWinds with Jinja2 templates, establishing Day-0/Day-1 Zero-Touch Provisioning for enterprise switches. Achieved **$470K in cost savings**.

- **Peer-to-Peer (P2P) Patch Management System:**  
  Designed a distributed peer-to-peer binary distribution system for WAN/LAN network firmware and patch distribution, boosting rollout speed 20x while saving critical WAN bandwidth. Generated **$660K in operational savings**.

- **Autonomous AI Network Agent (Applied AI R&D):**  
  Engineered an applied prototype exploring agentic network operations using the **Model Context Protocol (MCP)**. Demonstrated closed-loop, context-aware remediation by correlating live interface telemetry with administrative intent to eliminate false-positive operational alerts.

---

## Professional Experience

### HCLTech (Client: Mondelēz International)
**Lead Solutions Architect & Forward Deployed Engineer** *(Corporate Title: Lead Consultant)* | *Sep 2013 – Present*

*Operating as an embedded Forward Deployed Engineer directly inside Mondelēz International’s global network operations, partnering with cross-functional network, cloud, security, and enterprise infrastructure teams across three global chapters:*

- **HCLTech Canada** | *Aug 2023 – Present*
- **HCLTech Australia** | *Sep 2014 – Aug 2023*
- **HCLTech India** | *Sep 2013 – Sep 2014*

**Key Contributions & Responsibilities:**
- **Forward-Deployed Engineering:** Embedded directly on the operational front lines to identify chronic systemic bottlenecks, translating operational pain points into production software tools, microservices, and automation pipelines.
- **Technical Leadership & SDLC Governance:** Act as Squad Architect and Technical Lead for 6 full-stack engineers (React, TypeScript, Python, AWS, Terraform). Instituted the team's SDLC standards, sprint ceremonies, architecture reviews, and formal ADR workflows.
- **Enterprise Cloud & Infrastructure as Code:** Architected and deployed AWS cloud infrastructure using Terraform, Spacelift stacks, and AWS Account Factory for Terraform (AFT), enforcing Gitflow compliance and zero-drift infrastructure governance.
- **Enterprise Network Architecture:** Led multi-vendor network designs encompassing Cisco Catalyst/Nexus, Fortinet enterprise firewalls, Zscaler cloud security (ZIA/ZPA), Infoblox DDI, and Aruba Edge Connect SD-WAN.
- **Enterprise Asset Lifecycle & Observability:** Engineered automated collectors scraping Cisco Smart Net Total Care (SNTC) EoX APIs, cross-referencing global hardware inventories against obsolescence roadmaps to mitigate enterprise technical debt.
- **Enterprise API Orchestration:** Designed custom REST API endpoints and middleware integrating ServiceNow (SNOW), SolarWinds, Infoblox BloxOne, Cisco DNA Center, and FortiManager for automated incident resolution and zero-touch fulfillment.
- **Network Programmability:** Implemented Netconf, Restconf, and gRPC integrations to stream network telemetry and automate configuration state enforcement.

---

### Networkers Guru
**Vice President – Technical and Training Operations** | *May 2012 – Sep 2013*

- Designed, standardized, and directed technical training programs for enterprise network engineers and corporate clients.
- Engineered automated, multi-vendor lab environments for hands-on routing, switching, and security certification simulations.
- Managed a team of instructors and coached hundreds of engineers in advanced enterprise networking protocols.

---

### Network Infotech
**Network Engineer** | *May 2011 – May 2012*

- Designed, implemented, and maintained multi-site network infrastructure for enterprise clients.
- Managed end-to-end configuration and troubleshooting for routers, switches, firewalls, wireless access points, and VPN gateways.

---

### HCL Technologies Ltd.
**Technical Support Officer** | *Jan 2011 – May 2011*

- Provided L1/L2 network infrastructure support for a major British telecom service provider, troubleshooting complex WAN circuits, switches, routers, and customer premises equipment (CPE).

---

### Networkers Guru
**Technical Trainer** | *Apr 2009 – Jan 2011*

- Developed curriculum and delivered advanced training in Cisco routing and switching architectures.

---

## Education & Certifications

- **Cisco Certified Internetwork Expert (CCIE #37708 — Alumni / Inactive)** — Routing & Switching (Achieved lab certification; transitioned focus to Cloud Architecture, NetDevOps & Software Engineering)
- **Bachelor of Engineering (Computer Engineering)** — University of Pune (2006 – 2010)
