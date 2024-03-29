# Azure-Cloud-Detection-using-Sentinel


* What is a Detection?
Detection in cybersecurity is the practice of analyzing an environment for any anomalous activity that could possibly result in a network being compromised.

* Implementation Details: 
1. Configure and Deploy Azure Resources such as Log Analytics Workspace, 
Virtual Machines, and Azure Sentinel 
2. Implement Network and Virtual Machine Security Best Practices 
3. Utilize Data Connectors to bring data into Sentinel for Analysis 
4. Understand Windows Security Event logs 
5. Configure Windows Security Policies 
6. Utilize KQL to query Logs 
7. Write Custom Analytic Rules to detect Microsoft Security Events 
8. Utilize MITRE ATT&CK to map adversary tactics, techniques, detection, and 
mitigation procedures.

* Technology Used:
  1. Microsoft Sentinel
  2. Azure Log Analytics Workspace
  3. KQL
  4. MITRE ATT&CK

  * Steps for Implementation: 
Part 1: Setup Lab Resources 
Step 1: Create Free Azure Account. 
Step 2: Create a Resource Group. 
Step 3: Deploy a Virtual Machine. 
Step 4: Create Log Analytics Workspace and Deploy Sentinel. 
Part 2: Getting Data into Sentinel 
Part 3: Generating Security Events 
Part 4: Kusto Query Language 
Part 5: Writing Analytic Rule and Generating Scheduled Task 
Part 6: MITRE ATT&CK

* Detection: 
As observed. monitoring and logging of specific windows event id was used to  detect this activity. However, MITRE also has more recommendations for  detection.

* Mitigation: 
MITRE ID M1019 – User Account Management suggests that user account  privileges should be limited to only authorize admins to create scheduled tasks on remote systems. 

