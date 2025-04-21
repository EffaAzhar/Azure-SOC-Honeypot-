# Azure Honeypot and Centralized Logging Analysis
This project demonstrates the implementation of a basic Security Operations Center (SOC) and a honeypot environment within Microsoft Azure. 

# Lab Architecture: 

* Create a Resource Group and inside the resource group create Virtual Network. 
* Create a Virtual Machine 'CORP-NET-EAST-2' and attach it to Virtual Network. 
* Create Network Security Group and change the configuration so that VM is widely open to public internet. 
* Create log Analytic Workspace and connect it to both Microsoft Sentinel(SIEM) and Virtual Machine. This diagram illustrates the flow of logs from the Azure Virtual Machine (including the honeypot logs) into Azure Monitor Logs and subsequently into Microsoft Sentinel for analysis and alerting. 

# Lab Objectives: 

The key objectives of this lab were to gain practical experience in: 

* Creating and configuring Azure Virtual Machines for a honeypot. 
* Managing Network Security Group rules for network access. 
* Inspecting Windows Event Logs for security-related events. 
* Setting up an Azure Log Analytics Workspace for centralized log storage. 
* Deploying and connecting Microsoft Sentinel to the Log Analytics Workspace. 
* Configuring log connectors to ingest Windows Security Events. 
* Querying and analyzing logs using Kusto Query Language (KQL). 
* Enriching logs with geographic location data using Sentinel Watchlists. 
* Creating a basic attack map visualization in Sentinel Workbooks. 
* Understanding the process of setting up a basic honeypot in Azure. 
* Gaining experience with Azure Log Analytics Workspace as a central log repository. 
* Learning how to deploy and connect Microsoft Sentinel to a Log Analytics Workspace. 
* Practical application of configuring log connectors for ingesting security events. 
* Developing skills in querying and analyzing logs using Kusto Query Language (KQL). 
* Understanding the concept of log enrichment using Sentinel Watchlists to add valuable context (like geographic location).
 This project was inspired by a YouTube tutorial [https://youtu.be/g5JL2RIbThM].

# Technologies Used:

* **Microsoft Azure:** 
* Azure Virtual Machines 
* Microsoft Sentinel 
* Azure Monitor Logs 
* **Scripting:** Kusto Query Language (KQL)

# Project Parts:
* **Part 1:** Azure Subscription Setup
* **Part 2:** Resource Group
* **Part 3:** Creating the Honey Pot (Azure Virtual Machine)
* **Part 4:** Logging into the VM and Inspecting Logs
* **Part 5:** Log Analytics Workspace (LAW) Creation
* **Part 6:** Microsoft Sentinel Instance Creation and Connection
* **Part 7:** Querying Logs within the LAW
* **Part 8:** Sentinel Watchlist Creation (GeoId Database Import)
* **Part 9:** Log Enrichment Query
* **Part 10:** Sentinel Workbook Creation
* All parts have been explained in the Lab_Explanation file--> https://github.com/EffaAzhar/Azure-SOC-Honeypot-/blob/main/Lab_Explanation
and along with that all Screenshot references are given in Lab_Screenshots folder--> https://github.com/EffaAzhar/Azure-SOC-Honeypot-/tree/main/Lab_Screenshots

  
## Skills Demonstrated:

This project demonstrates proficiency in the following areas:

* **Cloud Computing (Microsoft Azure):** Virtual machine deployment and network configuration.
* **Security Information and Event Management (SIEM):** Microsoft Sentinel setup and configuration.
* **Log Management and Analysis:** Utilizing Azure Log Analytics Workspace for centralized logging.
* **Data Connectors:** Configuring data ingestion from Windows VMs into Sentinel.
* **Kusto Query Language (KQL):** Writing and executing queries for log analysis and enrichment.
* **Threat Intelligence:** Integrating and utilizing IP-based geographic data for enrichment..
* **Understanding of Security Concepts:** Honeypots, failed login analysis, and basic threat detection.

## Potential Improvements:

* Implement more sophisticated honeypot techniques and tools.
* Integrate additional data sources into Sentinel for broader security monitoring.
* Develop more advanced KQL queries for detecting various attack patterns.
* Automate incident response based on detected anomalies.

## Conclusion:

This project provides a foundational understanding of building a basic threat detection and analysis pipeline in a cloud environment. By setting up a honeypot, centralizing logs, and enriching data this project highlights key skills relevant to Security Operations roles.
