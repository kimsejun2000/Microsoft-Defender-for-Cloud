# Welcome to Microsoft Defender for Cloud Labs!

<p align="center">
<img src="./Images/asc-labs-logo.png?raw=true">
</p>

## Introduction
Our labs project help you get ramped up with Microsoft Defender for Cloud and provide hands-on practical experience for product features, capabilities, and scenarios. The labs are divided into 3 main tracks, a beginner (level 100/200) and an advanced (level 300+) track. The labs contain several modules cover different pillars such as Cloud Security Posture Management (CSPM) to Cloud Workload Protection  (CWP). To start using our labs, you will need to create Azure Trial Subscription which provides you all capabilities for 30 days – so you have to finish this lab at this point to take advantage of the free trial. We continually update the content to include the latest capabilities – please feel free to [submit issue](https://github.com/kimsejun2000/Azure-Security-Center/issues/new/choose) for any changes and suggestions.

<p align="center">
<img src="./Images/asc-labs-levels.png?raw=true">
</p>

Skill | Level | Description
----- | ----- | -----------
Beginner | 100 | You're starting out and want to learn the fundamentals of Microsoft Defender for Cloud
Intermediate | 200 | You have some experience with the product but want to learn more in-depth
Advanced | 300+ | You have lots of experience and are looking to learn about advanced capabilities

## Last release notes

* Version 1.0 - General availability of Microsoft Defender for Cloud labs
* Version 2.0 - General availability of Microsoft Defender for Cloud labs version 2 (November 2021)
* Version 3.0 - General availability of Microsoft Defender for Cloud labs version 3 (May 2024)

## Modules

[**Module 1 – Preparing the Environment (L100)**](./Modules/Module-01-Preparing-the-Environment.md)
- [Creating an Azure Trial Subscription](./Modules/Module-01-Preparing-the-Environment.md#exercise-1-creating-an-azure-trial-subscription)
- [Provisioning resources (automation)](./Modules/Module-01-Preparing-the-Environment.md#exercise-2-provisioning-resources)
- [Enabling Microsoft Defender for Cloud](./Modules/Module-01-Preparing-the-Environment.md#exercise-3-enabling-azure-defender)
 
[**Module 2 – Exploring Microsoft Defender for Cloud (L100)**](./Modules/Module-02-Exploring-Azure-Security-Center.md)
- [Understanding Microsoft Defender for Cloud dashboard](./Modules/Module-02-Exploring-Azure-Security-Center.md#exercise-1-understanding-azure-security-center-dashboard)
- [Exploring Secure Score and Recommendations](./Modules/Module-02-Exploring-Azure-Security-Center.md#exercise-2-exploring-secure-score-and-recommendations)
- [Exploring the Inventory capability](./Modules/Module-02-Exploring-Azure-Security-Center.md#exercise-3-exploring-the-inventory-capability)
 
[**Module 3 – Security Policy (L200)**](./Modules/Module-03-MDC-Security-Policy.md)
- [Overview of the security policy](./Modules/Module-03-MDC-Security-Policy.md#exercise-1-overview-of-the-asc-policy)
- [Explore Azure Policy](./Modules/Module-03-MDC-Security-Policy.md#exercise-2-explore-azure-policy)
- [Create resource exemption for a recommendation](./Modules/Module-03-MDC-Security-Policy.md#exercise-3-create-resource-exemption-for-a-recommendation)
- [Create a policy enforcement and deny](./Modules/Module-03-MDC-Security-Policy.md#exercise-4-create-a-policy-enforcement-and-deny)
- [Create a custom policy](./Modules/Module-03-MDC-Security-Policy.md#exercise-5-create-a-custom-policy)

[**Module 4 – Regulatory Compliance (L200)**](./Modules/Module-04-Regulatory-Compliance.md)
- [Understanding Regulatory Compliance dashboard](./Modules/Module-04-Regulatory-Compliance.md#exercise-1-understanding-regulatory-compliance-dashboard)
- [Adding new standards](./Modules/Module-04-Regulatory-Compliance.md#exercise-2-adding-new-standards)
- [Creating your own benchmark](./Modules/Module-04-Regulatory-Compliance.md#exercise-3-creating-your-own-benchmark)
 
[**Module 5 – Improving your Secure Posture (L300)**](./Modules/Module-05-Improving-your-Secure-Posture.md)
- [Vulnerability assessment for VMs](./Modules/Module-05-Improving-your-Secure-Posture.md#exercise-1-vulnerability-assessment-for-vms)
- [Vulnerability assessment for Containers](./Modules/Module-05-Improving-your-Secure-Posture.md#exercise-2-vulnerability-assessment-for-containers)
- [Automate recommendations with workflow automation](./Modules/Module-05-Improving-your-Secure-Posture.md#exercise-3-automate-recommendations-with-workflow-automation)
- [Accessing your secure score via ARG](./Modules/Module-05-Improving-your-Secure-Posture.md#exercise-4-accessing-your-secure-score-via-arg)
- [Creating Governance Rules and Assigning Owners](./Modules/Module-05-Improving-your-Secure-Posture.md#exercise-4-accessing-your-secure-score-via-arg)
 
[**Module 6 – Microsoft Defender Plans (L300)**](./Modules/Module-06-Workload-Protections.md)
- [Alert validation](./Modules/Module-06-Workload-Protections.md#exercise-1-alert-validation)
- [Alert suppression](./Modules/Module-06-Workload-Protections.md#exercise-2-alert-suppression)
- [Accessing Security Alerts using Graph Security API](./Modules/Module-06-Workload-Protections.md#exercise-3-accessing-security-alerts-using-graph-security-api)

[**Module 7 – Exporting Microsoft Defender for Cloud information to a SIEM (L200)**](./Modules/Module-07-Exporting-MDC-information-to-a-SIEM.md)
- [Using continuous export](./Modules/Module-07-Exporting-MDC-information-to-a-SIEM.md#exercise-1-using-continuous-export)
- [Integration with Microsoft Sentinel](./Modules/Module-07-Exporting-MDC-information-to-a-SIEM.md#exercise-2-integration-with-azure-sentinel)

[**Module 8 – Enhanced Security (L300)**](./Modules/Module-08-Enhanced-Security.md)
- [Enable Defender for Servers Plan 2](./Modules/Module-08-Enhanced-Security.md#exercise-1-enable-microsoft-defender-for-servers-plan-2)
- [Using JIT to reduce attack surface](./Modules/Module-08-Enhanced-Security.md#exercise-2-using-jit-to-reduce-attack-surface)
- [Adaptive Application Control](./Modules/Module-08-Enhanced-Security.md#exercise-3-adaptive-application-control)
- [Exercise 4: File Integrity Monitoring](./Modules/Module-08-Enhanced-Security.md#exercise-4-file-integrity-monitoring)

[**Module 9 – Defender for Containers (L300)**](./Modules/Module-09-Agentless-Container-Vulnerability-Assessment-Scanning.md)
- [Install Docker Desktop](./Modules/Module-09-Agentless-Container-Vulnerability-Assessment-Scanning.md#exercise-1-install-docker-desktop)
- [Download vulnerable image from Docker Hub into the Container Registry](./Modules/Module-09-Agentless-Container-Vulnerability-Assessment-Scanning.md#exercise-2-download-vulnerable-image-from-docker-hub-into-the-container-registry)
- [Investigate the recommendation for vulnerabilities in ACR](./Modules/Module-09-Agentless-Container-Vulnerability-Assessment-Scanning.md#exercise-3-investigate-the-recommendation-for-vulnerabilities-in-acr)

[**Module 10 – GCP (L300)**](./Modules/Module-10-GCP.md)
- [Create a GCP project](./Modules/Module-10-GCP.md#exercise-1-create-a-gcp-project)
- [Create the GCP connector in Microsoft Defender for Cloud](./Modules/Module-10-GCP.md#exercise-2-create-the-gcp-connector-in-microsoft-defender-for-cloud)
- [Investigate the GCP recommendations](./Modules/Module-10-GCP.md#exercise-3-investigate-the-gcp-recommendations)

[**Module 11 – AWS (L300)**](./Modules/Module-11-AWS.md)
- [Create an AWS account](./Modules/Module-11-AWS.md#exercise-1-create-an-aws-account)
- [Create an AWS connector for the new AWS account in Microsoft Defender for Cloud](./Modules/Module-11-AWS.md#exercise-2-create-an-aws-connector-for-the-new-aws-account-in-microsoft-defender-for-cloud)
- [investigate the AWS recommendations](./Modules/Module-11-AWS.md#exercise-3-investigate-the-aws-recommendations)

[**Module 12 – Database Protections (L300)**](./Modules/Module-12-MDC-database-protection.md)
- [Enable Defender for SQL servers on machines plan](./Modules/Module-12-MDC-database-protection.md#exercise-1-create-a-sql-server-on-an-azure-vm-enable-defender-for-sql-servers-on-machines-plan-and-validate-alerts)
- [Enable and protect your Azure SQL Databases using Microsoft Defender for Azure SQL Databases](./Modules/Module-12-MDC-database-protection.md#exercise-2-enable-and-protect-your-azure-sql-databases-using-microsoft-defender-for-azure-sql-databases)
- [Enable and protect your OSS RDBs using Microsoft Defender for Open-source relational databases](./Modules/Module-12-MDC-database-protection.md#exercise-3-enable-and-protect-your-oss-rdbs-using-microsoft-defender-for-open-source-relational-databases)
- [Enable and protect your Azure Cosmos DB accounts using Microsoft Defender for Azure Cosmos DB](./Modules/Module-12-MDC-database-protection.md#exercise-4-explore-defender-for-azure-cosmos-db)


[**Module 13 – Defender for APIs (L300)**](./Modules/Module-13-Defender-for-APIs.md)
- [Create Azure API Management Service](./Modules/Module-13-Defender-for-APIs.md#exercise-1-create-azure-api-management-service)
- [Publish an API within API Management](./Modules/Module-13-Defender-for-APIs.md#exercise-2-publish-an-api-within-api-management)
- [Enable Defender for API](./Modules/Module-13-Defender-for-APIs.md#exercise-3-enable-defender-for-api)
- [Onboard APIs to Defender for APIs](./Modules/Module-13-Defender-for-APIs.md#exercise-4-onboard-apis-to-defender-for-apis)
- [Explore the Defender for API tile and look at API recommendations in Defender for Cloud](./Modules/Module-13-Defender-for-APIs.md#exercise-5-explore-the-defender-for-api-tile-and-look-at-api-recommendations-in-defender-for-cloud)
- [Trigger an alert "Suspicious user agent detected"](./Modules/Module-13-Defender-for-APIs.md#exercise-6-trigger-an-alert-suspicious-user-agent-detected)

[**Module 14 – Configuring Azure DevOps Connector in Defender for Cloud (L200)**](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md)
- [Preparing the environment](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-1-preparing-the-environment)
- [Creating an Azure DevOps Trial Subscription](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-2-creating-an-azure-devops-trial-subscription)
- [Configuring Azure DevOps Connector](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-3-onboarding-an-azure-devops-connector)
- [Configure the Microsoft Security DevOps Azure DevOps Extension](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-4-configure-the-microsoft-security-devops-azure-devops-extension)
- [Install Free extension SARIF SAST Scans Tab](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-5-install-free-extension-sarif-sast-scans-tab)
- [Configure your pipeline using YAML](./Modules/Module-14-Onboarding-Azure-DevOps-to-MDC.md#exercise-6-configure-your-pipeline-using-yaml)

[**Module 15 – Configuring GitHub Connector in Defender for Cloud (L200)**](./Modules/Module-15-Onboarding-GitHub-to-MDC.md)
- [Preparing the environment](./Modules/Module-15-Onboarding-GitHub-to-MDC.md#exercise-1-preparing-the-environment)
- [Creating an GitHub Trial account](./Modules/Module-15-Onboarding-GitHub-to-MDC.md#exercise-2-creating-an-github-trial-account)
- [Obtain trial of GitHub Enterprise Cloud account](./Modules/Module-15-Onboarding-GitHub-to-MDC.md#exercise-3-obtain-trial-of-github-enterprise-cloud-account)
- [Connecting your GitHub organization](./Modules/Module-15-Onboarding-GitHub-to-MDC.md#exercise-4-connecting-your-github-organization)
- [Configure the Microsoft Security DevOps GitHub action](./Modules/Module-15-Onboarding-GitHub-to-MDC.md#exercise-5-configure-the-microsoft-security-devops-github-action)

[**Module 16 - Protecting On-Prem Servers in Defender for Cloud (L300)**](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md)
- [Install Hyper-V which will be used to create the server on your own machine](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-1-install-hyper-v-which-will-be-used-to-create-the-server-on-your-own-machine)
- [Using Hyper-V, confirm that there's a virtual switch already installed on your desktop](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-2-using-hyper-v-confirm-that-theres-a-virtual-switch-already-installed-on-your-desktop)
- [Using Hyper-V, create a VM (virtual machine) which will act as the virtual on-premises server that you will be protecting via Defender for DevOps](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-3-using-hyper-v-create-a-vm-virtual-machine-which-will-act-as-the-virtual-on-premises-server-that-you-will-be-protecting-via-defender-for-devops)
- [Install the operating system in your VM](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-4-install-the-operating-system-in-your-vm)
- [Setup the Azure Arc Rresource provider](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-5-setup-the-azure-arc-rp)
- [Connect to your VM](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-6-connect-to-your-vm)
- [Install Azure Arc on the VM so the VM will be protected by Micrsosoft Defender for Cloud](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-7-install-azure-arc-on-the-vm-so-the-vm-will-be-protected-by-micrsosoft-defender-for-cloud)
- [Confirm that the "on-prem" server we created is being detected by the Azure portal](./Modules/Module-16-Protecting-On-Prem-Servers-in-MDC.md#exercise-8-confirm-that-the-on-prem-server-we-created-is-being-detected-by-the-azure-portal)

[**Module 17 - Defender CSPM (L200)**](./Modules/Module-17-Defender-CSPM.md)
- [Preparing the Environment for DCSPM plan](./Modules/Module-17-Defender-CSPM.md#exercise-1-preparing-the-environment-for-dcspm-plan)
- [Enabling Defender CSPM plan](./Modules/Module-17-Defender-CSPM.md#exercise-2-enabling-defender-cspm-plan)
- [Analyzing and mitigating attack paths](./Modules/Module-17-Defender-CSPM.md#exercise-3-analyzing-and-mitigating-attack-paths)
- [Build query with Cloud Security Explorer](./Modules/Module-17-Defender-CSPM.md#exercise-4-build-query-with-cloud-security-explorer)
- [Assign Governance Rule](./Modules/Module-17-Defender-CSPM.md#exercise-5-assign-governance-rule)
- [Analyze security recommendations by risk level-risk prioritization](./Modules/Module-17-Defender-CSPM.md#exercise-6-analyze-security-recommendations-by-risk-level---risk-prioritization)
- [Leverage-cloud-identity entitlement management-permissions management](./Modules/Module-17-Defender-CSPM.md#exercise-7-leverage-cloud-identity-entitlement-management---permissions-management)

[**Module 18 - Agentless container posture through Defender CSPM (L200)**](./Modules/Module-18-Agentless-container-posture-through-Defender-DCSPM.md)
- [Prepare your environment](./Modules/Module-18-Agentless-container-posture-through-Defender-DCSPM.md#exercise-1-prepare-your-environment)
- [Investigate internet exposed Kubernetes pods through the Cloud Security Explorer](./Modules/Module-18-Agentless-container-posture-through-Defender-DCSPM.md#exercise-2-investigate-internet-exposed-kubernetes-pods-through-the-cloud-security-explorer)
- [Investigate attack paths](./Modules/Module-18-Agentless-container-posture-through-Defender-DCSPM.md#exercise-3-investigate-attack-paths)

[**Module 19 – Defender for Storage**](./Modules/Module-19-Defender-for-Storage.md)
- [Preparing the Environment for Defender for Storage plan](./Modules/Module-19-Defender-for-Storage.md#-exercise-1-preparing-the-environment-for-defender-for-storage-plan)
- [Create a Storage Account](./Modules/Module-19-Defender-for-Storage.md#-exercise-2-create-a-storage-account)
- [(Optional) Exclude folder in Windows Security](./Modules/Module-19-Defender-for-Storage.md#optional--exercise-3-exclude-folder-in-windows-security)
- [Create EICAR File](./Modules/Module-19-Defender-for-Storage.md#-exercise-4-create-eicar-file)
- [Upload Malware to a Storage Account](./Modules/Module-19-Defender-for-Storage.md#-exercise-5-upload-malware-to-a-storage-account)
- [Security Alert](./Modules/Module-19-Defender-for-Storage.md#️-exercise-6-security-alert)
- [Configure automation to delete the malicious file based on security alert](./Modules/Module-19-Defender-for-Storage.md#-exercise-7-configure-automation-to-delete-the-malicious-file-based-on-security-alert)
- [Code to upload files to storage account and monitor the blob index tag itself](./Modules/Module-19-Defender-for-Storage.md#-exercise-8-code-to-upload-files-to-storage-account-and-monitor-the-blob-index-tag-itself)
- [Set up "Send scan results to Log Analytics" and read it](./Modules/Module-19-Defender-for-Storage.md#-exercise-9-set-up-send-scan-results-to-log-analytics-and-read-it)
- [Function App based on Event Grid events](./Modules/Module-19-Defender-for-Storage.md#️-exercise-10-function-app-based-on-event-grid-events)
- [ABAC for users not to read malicious files](./Modules/Module-19-Defender-for-Storage.md#️-exercise-11-abac-for-users-not-to-read-malicious-files)
- [Test on-demand malware scanning](./Modules/Module-19-Defender-for-Storage.md#-exercise-12-test-on-demand-malware-scanning)
- [Built-in malware automated remediation](./Modules/Module-19-Defender-for-Storage.md#exercise-13-built-in-malware-automated-remediation)

[**Module 20 – Contextual Security capabilities for AWS using Defender CSPM**](./Modules/Module-20-Contextual-Security-capabilities-for-AWS-using-Defender-CSPM.md)
- [Preparing the AWS Environment for Defender CSPM plan](./Modules/Module-20-Contextual-Security-capabilities-for-AWS-using-Defender-CSPM.md#exercise-1-preparing-the-aws-environment-for-defender-cspm-plan)
- [Explore Attack Paths in your AWS Environment](./Modules/Module-20-Contextual-Security-capabilities-for-AWS-using-Defender-CSPM.md#exercise-2-explore-attack-paths-in-your-aws-environment)
- [Build query with Cloud Security Explorer](./Modules/Module-20-Contextual-Security-capabilities-for-AWS-using-Defender-CSPM.md#exercise-3-build-query-with-cloud-security-explorer)

[**Module 21 - Contextual Security capabilities for GCP using Defender CSPM**](./Modules/Module-21-Contextual-Security-capabilities-for-GCP-using-Defender-CSPM.md)
- [Preparing the GCP Environment for Defender CSPM plan](./Modules/Module-21-Contextual-Security-capabilities-for-GCP-using-Defender-CSPM.md#exercise-1-preparing-the-gcp-environment-for-defender-cspm-plan)
- [Explore Attack Paths in your AWS Environment](./Modules/Module-21-Contextual-Security-capabilities-for-GCP-using-Defender-CSPM.md#exercise-2-explore-attack-paths-in-your-aws-environment)
- [Build query with Cloud Security Explorer](./Modules/Module-21-Contextual-Security-capabilities-for-GCP-using-Defender-CSPM.md#exercise-3-build-query-with-cloud-security-explorer)

[**Module 22 - Integration with Microsoft Defender for Endpoint**](./Modules/Module-22-MDE-integration.md)
- [Enable the integration with Microsoft Defender for Endpoint](./Modules/Module-22-MDE-integration.md#exercise-1-enable-auto-deployment-of-and-integration-with-microsoft-defender-for-endpoint)
- [Connect your on-premises servers via direct onboarding](./Modules/Module-22-MDE-integration.md#exercise-2-connect-your-on-premises-servers-via-direct-onboarding)
- [Analyze vulnerability assessment findings in custom workbooks](./Modules/Module-22-MDE-integration.md#exercise-3-analyze-vulnerability-assessment-findings-in-custom-workbooks)

[**Module 23 - Data-aware security posture**](./Modules/Module-23-Data-security-posture-management.md)
- [Enabling sensitive data discovery](./Modules/Module-23-Data-security-posture-management.md#exercise-1-enabling-sensitive-data-discovery)
- [(Optional) Enabling sensitive data discovery for AWS and GCP](./Modules/Module-23-Data-security-posture-management.md#optional-exercise-2-enabling-sensitive-data-discovery-for-aws-and-gcp)
- [Configure sensitive data categories](./Modules/Module-23-Data-security-posture-management.md#exercise-3-configure-sensitive-data-categories)
- [(Optional) Import and configure custom sensitive info types and sensitivity labels](./Modules/Module-23-Data-security-posture-management.md#optional-exercise-4-import-and-configure-custom-sensitive-info-types-and-sensitivity-labels)
- [Upload sensitive data](./Modules/Module-23-Data-security-posture-management.md#exercise-5-upload-sensitive-data)
- [Explore risks with Cloud Security Explorer](./Modules/Module-23-Data-security-posture-management.md#exercise-6-explore-risks-with-cloud-security-explorer)
- [Identify sensitive resources in Inventory](./Modules/Module-23-Data-security-posture-management.md#exercise-7-identify-sensitive-resources-in-inventory)
- [(Optional) Explore risks through attack paths](./Modules/Module-23-Data-security-posture-management.md#optional-exercise-8-explore-risks-through-attack-paths)
- [(Optional) Explore sensitive data security alerts](./Modules/Module-23-Data-security-posture-management.md#optional-exercise-9-explore-sensitive-data-security-alerts)
- [(Optional) Data security dashboard investigation](./Modules/Module-23-Data-security-posture-management.md#optional-exercise-10-data-security-dashboard-investigation)

[**Module 24 - Security for AI Workloads**](./Modules/Module-24-AI-Workloads.md)
* [Enable AI Workloads](./Modules/Module-24-AI-Workloads.md#exercise-1-enable-ai-workloads)
* [Simulate Jailbreak Attacks](./Modules/Module-24-AI-Workloads.md#exercise-2-simulate-jailbreak-attacks)
* [Simulate a malicious url detection](./Modules/Module-24-AI-Workloads.md#exercise-3-simulate-a-malicious-url-detection)
* [Enable AI posture management](./Modules/Module-24-AI-Workloads.md#exercise-4-enable-ai-posture-management)

[**Module 25 - Defender XDR Integration**](./Modules/Module-25-Defender-XDR-Integration.md)
* [Setting Up the Environment](./Modules/Module-25-Defender-XDR-Integration.md#exercise-1-setting-up-the-environment)
* [Deploying the Attack Simulation](./Modules/Module-25-Defender-XDR-Integration.md#exercise-2-deploying-the-attack-simulation)
* [Running Individual and Combined Attack Scenarios](./Modules/Module-25-Defender-XDR-Integration.md#exercise-3-running-individual-and-combined-attack-scenarios)
* [Observing and Analyzing MDC Alerts](./Modules/Module-25-Defender-XDR-Integration.md#exercise-4-observing-and-analyzing-mdc-alerts)
* [Correlating and Responding to Incidents Using XDR](./Modules/Module-25-Defender-XDR-Integration.md#exercise-5-correlating-and-responding-to-incidents-using-xdr)

[**Module 26 - Code Reachability Vulnerabilities**](./Modules/Module-26-Code-Reachability-Vulnerabilities.md)
* [Azure DevOps Configuration](./Modules/Module-26-Code-Reachability-Vulnerabilities.md#exercise-1-azure-devops-configuration)
* [GitHub Configuration](./Modules/Module-26-Code-Reachability-Vulnerabilities.md#exercise-2-github-configuration)

[**Begin the labs here >**](./Modules/Module-01-Preparing-the-Environment.md)

## Acronyms

Acronym | Meaning | Description
------- | --- | -----------
MDFC | Microsoft Defender for Cloud | Built-in free service which offer limited security for your Azure resources only
CSPM | Cloud Security Posture Management | Automates the identification and remediation of risks across cloud infrastructures. CSPM in Microsoft Defender for Cloud is available for free to all Azure users. The free experience includes CSPM features such as secure score, detection of security misconfigurations in your Azure machines, asset inventory, and more.
CWP | Cloud Workload Protection | Provides workload-centric security protection solutions such as servers, app service, storage, database and more. All CWP capabilities are covered under Microsoft Defender for Cloud.
JIT | Just-in-time | Feature to reduce exposure to attacks while providing easy access when you need to connect to a VM
ARM | Azure Resource Manager | Deployment and management layer that enables you to create, update, and delete resources in your Azure account.
RBAC | Role-based access control | Authorization system built on Azure Resource Manager that provides fine-grained access management of Azure resources.
VA | Vulnerability Assessment | Provides vulnerability scanning for your virtual machines and container registries.
SIEM | Security information and event management | Tool to provide a central place to collect events and alerts, that aggregates data from multiple systems and analyze that data to catch abnormal behavior or potential cyberattacks. For example, Microsoft Sentinel.


[**Begin the labs here >**](./Modules/Module-01-Preparing-the-Environment.md)
