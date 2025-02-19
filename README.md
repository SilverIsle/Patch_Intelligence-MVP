# Patch Intelligence

---

## Overview
Patch Intelligence is a research-driven project aimed at improving modern-day patch management. The project addresses key issues such as the disconnect between vulnerabilities and patches, lack of critical IT Service Management (ITSM) information on patches, and the need for a structured intelligence system to enhance vulnerability and patch management.

## Features
- **Patch Information Collection**: Gathers patch details for top application libraries (npm, Maven, PyPi, Linux, NuGet).
- **Knowledge Graph Construction**: Establishes relationships between CVEs (Common Vulnerability Enumeration), CPEs (Common Product Enumeration), and patches.
- **Risk and Crash Intelligence**: Collects data on patch failure rates, known issues, and operational impact.
- **Automation**: Periodic updates of the collected data to ensure accuracy.
- **Web Interface**: A user-friendly web page for visualization and interaction with patch intelligence data.

## Project Status
- **Data Collection**: Completed.
- **Database Correlation**: Completed.
- **Knowledge Graph Implementation**: Completed.
- **Graph Visualization**: Implemented.
- **Web Interface**: Developed.
- **Automation**: In Progress.

# Installation
To run the project locally, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/patch-intelligence.git
   cd patch-intelligence-mvp
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Description - 
Patch Intelligence helps IT teams by:
- **Providing confidence scores** for patches based on crash likelihood, performance issues, and other metadata.
- **Identifying critical vulnerabilities** and linking them with available patches.
- **Presenting a comprehensive overview** of patch risks, crash data, and mitigation strategies.

## Correlation Database
The project features a graph database that links:
- **CVEs (Common Vulnerabilities and Exposures)**
- **CPEs (Common Product Enumeration)**
- **Patch Metadata** (Vendor, Product, Fixed Version, Known Issues, Security Fixes, etc.)

Supported libraries:
- npm
- Maven
- PyPi
- Linux
- NuGet

The graph database allows users to explore relationships between vulnerabilities and available patches dynamically.

## Graph Visualization - 
A directed knowledge graph is implemented to visualize:
- The relationship between CVEs, CPEs, and patches.
- The impact of vulnerabilities on different software versions.
- The metadata associated with patches, including risk assessment and supersedence information.

## Patch Overview Data - 
The system includes an interactive dashboard showcasing:
- **Security Issues**: CVE/Non-CVE vulnerabilities and their impacted versions.
- **Patch Status**: Whether a vulnerability has an available fix.
- **Known Issues**: Performance concerns, reboot requirements, and crash likelihood.
- **Lifecycle Information**: End-of-life data for patches and software versions.

## Sample Video
https://github.com/user-attachments/assets/037ad1f6-25a0-4eb9-af64-a78c663fb834

## Project Snaps - 
![pg1](https://github.com/user-attachments/assets/7389da55-6856-4090-8b84-087d682e1437)
![pg2](https://github.com/user-attachments/assets/9ccf070e-5c74-4401-b3e5-ac8b9e4a3fbf)
![pg3](https://github.com/user-attachments/assets/a97bcf6f-84bd-4755-88c9-2e03c724f925)
![Screenshot 2025-02-12 095642](https://github.com/user-attachments/assets/3f73f3fd-09e9-48ec-92b7-737a5d60fa2c)
![Screenshot 2025-02-12 100148](https://github.com/user-attachments/assets/bb6d8d28-a7dd-40e9-b66f-906906b0399c)
![Screenshot 2025-02-12 095806](https://github.com/user-attachments/assets/433c65a0-1e6b-4b05-8c4f-d3978e5e63da)


## Technologies Used -
- **Backend**: Python, Flask
- **Database**: SQLite (Graph Database)
- **Frontend**: HTML, CSS, JavaScript
- **Data Processing**: BeautifulSoup, Pandas
- **Visualization**: D3.js for graph representation

## Contributors - 
- [Samuel Kiruba](https://github.com/lokeshwar) +91 7200754446 .
- [Jonnalagadda Sri Harsha](https://github.com/HarshaHharros) +91 8122182899.
- [Prithvi v](https://github.com/lokeshwar)
- [Lokeshwar Yemulwar](https://github.com/lokeshwar)
- [Dev S](https://github.com/lokeshwar)
- [Trinisha](https://github.com/lokeshwar)
- [Dhanush](https://github.com/lokeshwar)
- [Jothiarunachalam](https://github.com/lokeshwar)
For more details, please refer to the documentation or contact the contributors.
