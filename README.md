# open-source-siem-walkthrough

## Project Overview
This project documents the design and implementation of a simple, scalable,
open-source SIEM/SOAR platform using Wazuh, the Elastic Stack, and Shuffle SOAR.

The goal is to provide:
- A learning-focused walkthrough
- A reproducible lab environment
- A foundation that can scale into a full SOC-style SIEM

## Target Audience
- SOC Analysts
- Blue Teamers
- Security Engineers in training
- Anyone interested in detection engineering and SIEM design

## Project Goals
- Collect endpoint telemetry from one or more hosts
- Normalize logs using Elastic Common Schema (ECS)
- Query data using KQL
- Create, store, and tune detection rules
- Map detections to MITRE ATT&CK
- Automate alert handling using SOAR playbooks

## Non-Goals (For Now)
- Full enterprise-scale HA deployment
- Paid tooling or licenses
- Advanced EDR replacement

## High-Level Architecture
(To be added)

## Project Phases
1. Environment and architecture design
2. SIEM core installation
3. Endpoint telemetry collection
4. Log normalization and schema design
5. Detection engineering with KQL
6. MITRE ATT&CK mapping
7. SOAR automation
