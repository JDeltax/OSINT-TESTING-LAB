# OSINT & Network Reconnaissance Lab: h4cker.org

## Project Overview
This laboratory documents a professional reconnaissance workflow focused on **Host Discovery** and **Digital Footprinting**. The objective is to map the external attack surface of the target domain `h4cker.org` using automated OSINT frameworks.

## Methodology
The reconnaissance was conducted using a hybrid approach of passive and active enumeration:
* **Infrastructure Mapping:** Identification of IP addresses, netblocks, and DNS hierarchy.
* **Asset Correlation:** Linking subdomains, mail servers, and web properties.
* **Service Fingerprinting:** Analyzing exposed services and technologies without direct exploitation.

## Tech Stack & Tooling
* **SpiderFoot:** Primary OSINT automation framework used for footprinting and threat intelligence.
* **Python-based Backend:** For data processing and module execution.
* **Web UI:** Centralized dashboard for scan management and data visualization.

## Key Findings (Summary)
The scan identified the core infrastructure of `h4cker.org`, including:
* **DNS Records:** A, MX, NS, and TXT records.
* **Network Topology:** Associated IP ranges and hosting providers.
* **Affiliates & Subdomains:** Discovery of secondary assets linked to the main domain.

---
*Note: This repository is for educational and portfolio purposes. No intrusive actions were performed.*
