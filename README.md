# OSINT-TESTING-LAB

This repository documents a network reconnaissance laboratory focused on **host discovery** and **network mapping**. It covers the methodology for identifying active nodes within a specific range and performing service enumeration to define the network's attack surface.

---

## SpiderFoot Integration

### Overview
**SpiderFoot** is a comprehensive OSINT automation framework designed for footprinting and threat intelligence. It integrates with over **200 modules** to automate:

* **Data Collection:** Crawling engines and databases for target information.
* **Intelligence Correlation:** Linking assets like IPs, netblocks, and DNS records.
* **Data Visualization:** Providing a graphical overview of the attack surface.

It is the industry-standard tool for scaling reconnaissance beyond manual scanning.

---

## Initializing SpiderFoot

To begin, we start the connection on the main IP and port to establish the working environment:

<img width="473" height="108" alt="SpiderFoot Initialization" src="https://github.com/user-attachments/assets/c799b529-7574-4437-b291-4acf0543f411" />  

Once the service is active, users can access the **web-based interface** via a browser. This dashboard allows for the configuration of reconnaissance modules and the precise definition of the target server or network range for the scan.

---

## Target Selection & Scan Execution

In this laboratory, we are scanning `h4cker.org` to detect its digital footprint across the internet. 

The process involves defining the target as a "seed" and selecting the appropriate modules to correlate public data with the infrastructure.

<img width="953" height="908" alt="SpiderFoot Scan Configuration" src="https://github.com/user-attachments/assets/fa8c0060-ae9d-4d0c-a540-944617f881ba" />

---

### Project Notes
* **Focus:** Passive and Active Reconnaissance.
* **Tools:** SpiderFoot (Web UI), Python-based backend.
* **Goal:** Map the external visibility of the target domain.
