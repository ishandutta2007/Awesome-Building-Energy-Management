# Awesome-Building-Energy-Management

## Top Building Energy Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Energy Analytics, Fault Detection & Automated Building Optimization*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Building Energy Management**. These tools monitor, analyze, and optimize building energy consumption, HVAC performance, and grid interactivity for commercial buildings, campuses, and industrial facilities.



**Examples** include BrainBox AI, GridPoint, Facilio, BuildingIQ, Clockworks Analytics, Switch Automation, Verdigris, 75F, Enertiv, and C3 AI Energy Management (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom energy analytics, and transparent building data management — ideal for facility managers, building engineers, researchers, and developers building vendor-independent energy optimization solutions. The open-source ecosystem offers production-grade Energy Management Systems (EMS), fault detection frameworks, and control platforms from national laboratories and research institutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[BrainBox AI](https://www.brainboxai.com/)**  

  AI-powered HVAC optimization platform using deep learning to reduce energy consumption and carbon emissions in commercial buildings.



- **[GridPoint](https://www.gridpoint.com/)**  

  Energy management platform for commercial buildings with demand response, backup power, and sustainability reporting.



- **[Facilio](https://facilio.com/)**  

  Connected building operations platform with energy management, maintenance, and sustainability tools for portfolios.



- **[BuildingIQ](https://www.buildingiq.com/)**  

  AI-driven energy optimization platform using predictive analytics to reduce HVAC energy consumption.



- **[Clockworks Analytics](https://www.clockworksanalytics.com/)**  

  Automated fault detection and diagnostics platform for building HVAC systems, identifying energy waste and equipment issues.



- **[Switch Automation](https://www.switchautomation.com/)**  

  Smart building platform for energy management, ESG reporting, and building system integration.



- **[Verdigris](https://verdigris.co/)**  

  AI-powered energy management platform using circuit-level metering and machine learning for building optimization.



- **[75F](https://www.75f.io/)**  

  IoT-based building management system focused on HVAC, lighting, and energy optimization for commercial buildings.



- **[Enertiv](https://www.enertiv.com/)**  

  Building operations platform with energy monitoring, equipment health, and work order management.



- **[C3 AI Energy Management](https://c3.ai/)**  

  Enterprise AI application for energy management, covering building portfolios with predictive analytics and optimization.



## Open-Source GitHub Projects



- **[VOLTTRON](https://github.com/VOLTTRON/volttron)**  

  The leading open-source distributed control and sensing platform for buildings, developed at Pacific Northwest National Laboratory (PNNL) and now under the Eclipse Foundation. Python-based, lightweight, and runs on low-cost hardware including Raspberry Pi. Features a central message bus with pub-sub architecture, drivers for BACnet and Modbus, and applications written as "agents" including automated fault detection diagnostics (AFDD), intelligent load control, demand response, and autonomous control of rooftop units. Built-in cybersecurity features include authentication, authorization, and secure application transport. Deployed by Transformative Wave, Intellimation, New City Energy, and SkyCentrics. The aems-app repository provides a full Docker-based deployment with historian, backup, and replication capabilities .



- **[ZandrEA](https://github.com/usnistgov/ZandrEA)**  

  Open-source software framework from NIST supporting research into automated, real-time detection and diagnostics of operational faults in HVAC systems of large commercial buildings. Combines benefits of rules-based and data-driven (process history-based) AFDD approaches. Five Docker containers: computational engine (C++ with REST API), React-based GUI dashboard, live data collection script polling BACnet devices, reverse proxy, and a container for research on novel AFDD algorithms in Python/JS. Designed to free researchers from implementing data distribution and real-time display, allowing focus on novel algorithm exploration. BSD 3-Clause licensed .



- **[MyEMS](https://github.com/MyEMS/myems)**  

  Industry-leading open-source Energy Management System with nearly a thousand project cases and CMA testing certification. Follows ISO 50001 energy management standard (GB/T 23331-2020). Suitable for buildings, factories, shopping malls, hospitals, and parks. Features electricity, water, gas, cooling, and heating data collection, analysis, and reporting. Enterprise version adds photovoltaics, energy storage, charging piles, microgrids, virtual power plants, equipment control, fault diagnosis, work order management, and AI optimization. Python/React/AngularJS stack with MySQL database. Maintained by a professional company with monthly releases. Community edition is MIT licensed with permanent open-source commitment .



- **[BEMServer](https://github.com/BEMServer/bemserver)**  

  Open-source platform designed to support building energy management through integration, organization, and utilization of data from multiple sources. Acts as an intermediary layer centralizing heterogeneous information including BMS data, sensors, weather services, and occupancy monitoring. Incorporates a semantic model for consistent, interoperable data representation. Provides API interfaces supporting monitoring, analytics, forecasting, anomaly detection, and energy performance indicator generation. Modular and scalable architecture. Originally developed within the European HIT2GAP project with contributions from NOBATEK/INEF4 and other partners. First release in December 2019 .



- **[Open-FDD](https://github.com/bbartling/open-fdd)**  

  Free, open-source building-to-cloud pipeline for HVAC analytics and fault detection. Same stack runs on-premises or in the cloud using high-performance Apache Arrow storage and DataFusion SQL, a Rust central service, React operator UI, Mosquitto MQTTS ingest, and fieldbus edge agents for BACnet, Modbus, and Haystack. Includes REST APIs and CSV/zip import for offline data. MIT licensed with GHCR images available. Roadmap includes ML and clustering on the same foundation. PyPI package `open-fdd` provides rule-based FDD equations with Pandas as reference implementation .



- **[City Energy Analyst (CEA)](https://github.com/architecture-building-systems/CityEnergyAnalyst)**  

  Open-source urban building energy modeling (UBEM) platform and computation tool for the design of low-carbon and highly efficient cities. Combines urban planning and energy systems engineering knowledge in an integrated simulation platform to study effects, trade-offs, and synergies of urban design scenarios and energy infrastructure plans. Version 3.39.4 released 2025. Empowers practitioners and researchers to plan future low-carbon cities .



- **[BEMOSS](https://github.com/bemoss)**  

  Building Energy Management Open-Source Software platform providing a unified communication platform that integrates information from disparate sources and provides one control hierarchy. Low-cost, open-source software platform that monitors and controls major electrical loads including HVAC, lighting, and plug loads, as well as solar PV, energy storage, and IoT sensors. Provides new or legacy buildings with a building automation system (BAS) or connects with existing BASs. Leverages machine learning algorithms using historical operating data and occupant preferences for energy savings. Supports OpenADR demand response protocols .



- **[ACTIVE (Automated Control Testbed for Integration, Verification, and Emulation)](https://github.com/SmithRWORNL/ACTIVE)**  

  Open-source framework from Oak Ridge National Laboratory (BSD 3-Clause) supporting optimized operation and management of diverse building types. Enables development, testing, and validation of diverse control strategies including AI-based, rule-based, and model-based approaches. Facilitates seamless transition from simulation-based evaluation to real-world field validation and deployment. Supports full building management lifecycle: data acquisition, system monitoring, optimized control, adaptive learning, device dispatch, and advanced analytics. Python-based, version 2.0.9 released 2025. Sponsored by DOE Building Technologies Office .



- **[CEAM (Climate and Energy Assessment for Museums)](https://github.com/Climate2Preserv)**  

  Open-source, data-driven tool for comprehensive multicriteria analysis of heritage buildings. Considers heritage preservation, indoor climate management, and energy efficiency improvement. Uses raw input data (measured energy consumption and indoor/outdoor climate conditions) to provide insights. Employs AI-based optimization methods to evaluate potential energy savings through short-term management strategies, with predicted savings of 10-50% depending on scenario. Python-based with standalone Windows app. Developed by KU Leuven, KIK-IRPA, and ULiège as part of the Climate2Preserv project funded by Belgian Science Policy Office .



### Additional Strong Open-Source Options



- **BOPTEST** — Building Optimization Performance Tests framework for benchmarking HVAC control strategies. Containerized emulators with standardized KPIs for fair comparison of control algorithms. Modelica-based .

- **NexMesh** — Field-configurable open-source Wi-Fi mesh node for scalable building energy management systems. Addresses hardware complexity and rigid firmware architectures in WSN deployment for BEMS. Demonstrates x7.7 to x12.5 reduction in configuration time compared to traditional methods .

- **openbms-io/bms-apps** — Open-source BMS applications including Designer with Zod schema validation and IoT app. pnpm monorepo with SQLite/Turso database support .



**Frameworks for building custom building energy management solutions**: Combine **VOLTTRON** for a production-grade distributed control platform with agent-based architecture and security features . Use **ZandrEA** for research-oriented AFDD development combining rules-based and data-driven approaches . Deploy **MyEMS** for a comprehensive ISO 50001-aligned EMS with enterprise features . Leverage **Open-FDD** for a modern cloud-native fault detection pipeline with Rust and DataFusion . Use **ACTIVE** for testing and validation of control strategies before field deployment . For urban-scale energy modeling, **City Energy Analyst** provides district-level simulation capabilities .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Building energy management tools must comply with local building codes, energy regulations, and grid interconnection standards.

- Self-hosted open-source solutions require proper infrastructure, expertise in building automation protocols (BACnet, Modbus, MQTT), and ongoing maintenance. Integration with existing building systems requires specialized knowledge.

- The open-source ecosystem provides strong EMS platforms, fault detection frameworks, and control testbeds from national laboratories and research institutions, but full commercial energy management with automated fault detection, portfolio analytics, and utility bill management remains primarily a commercial offering.



---



**Made for facility managers, building engineers, energy analysts, and smart building developers.**  

Let's make building energy management more open, transparent, and efficient.
