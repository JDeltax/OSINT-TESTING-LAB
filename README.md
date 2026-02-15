# OSINT & Network Reconnaissance Lab: h4cker.org & hackxor.net

**Author:** Computer Systems Engineer Juan Pablo Vega Villamil  
**Date:** February 2026  
**Focus:** Ethical Hacking - Reconnaissance Phase

---

## Project Overview
This laboratory documents a professional reconnaissance workflow focused on **Host Discovery**, **Subdomain Enumeration**, and **Digital Footprinting**. The objective is to map the external attack surface of target domains using industry-standard OSINT frameworks to identify infrastructure exposure and potential vectors for security assessments.

## Tech Stack & Tooling
* **SpiderFoot v4.0.0**: Used for high-level footprinting and automated correlation of global data sources.
* **Recon-ng v5.1.2**: A modular web reconnaissance framework used for targeted domain enumeration and sensitive file discovery.
* **Kali Linux**: Primary operating environment for tool execution and data management.
* **Recon-web**: Browser-based analytics engine for visualizing OSINT databases.

## Methodology
The reconnaissance followed a structured, non-intrusive workflow:
1. **Environment Deployment**: Initializing local backends on port 5001 (SpiderFoot) and 5000 (Recon-web).
2. **Passive Enumeration**: Utilizing modules like `HackerTarget` to query third-party APIs for subdomains without direct target interaction.
3. **Asset Correlation**: Linking discovered IP addresses (e.g., `185.199.108.153`) to network blocks and providers.
4. **Sensitive Directory Discovery**: Using `interesting_files` to identify critical system files like `robots.txt`.

## Key Findings & Deliverables

### 1. Infrastructure Mapping (SpiderFoot)
Analyzed `h4cker.org` to understand its digital footprint:
* **Unique Elements**: Identified 57 unique data points across 64 total findings.
* **Network Topology**: Resolved 4 distinct IP addresses associated with the target infrastructure via `sfp_dnsresolve`.
* **Data Distribution**: Categorized findings into Internet Names, DNS SPF/TXT records, and Open TCP Ports.

### 2. Domain Discovery (Recon-ng)
Focused on `hackxor.net` to demonstrate modular reconnaissance:
* **Host Identification**: Successfully enumerated 5 distinct subdomains including `analytics`, `dreaded`, and `phonecorp`.
* **IP Resolution**: Mapped all discovered hosts to the `138.68.117.124` address block.
* **File Analysis**: Identified sensitive directories and exported results to a `.csv` database located in the `recon-ng/data` directory.

## Lab Documentation
The full technical reports (IEEE Format) include:
* **Initial Setup**: Terminal deployment and GUI initialization logs.
* **Execution Logs**: CLI commands for module loading, source setting, and scan execution.
* **Data Visualization**: Statistical graphs and relationship nodes representing the identified infrastructure.

---
**Disclaimer:** *This project is strictly for educational and portfolio purposes. All data was gathered through passive OSINT techniques. No intrusive actions or unauthorized scans were performed against the target infrastructure.*
