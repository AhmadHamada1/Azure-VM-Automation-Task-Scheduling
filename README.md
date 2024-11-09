**Overview**
This project automates the startup process of an Azure Virtual Machine using Azure Automation and schedules recurring tasks with Automate. Notifications are sent to a Microsoft Teams channel to keep track of the task status.

**Features**
Automated VM Startup: Starts the Azure VM using an Azure Automation runbook script.
Task Scheduling: Automates task scheduling with Automate for recurring VM starts.
Microsoft Teams Integration: Sends task status notifications to a Teams channel.
Azure VM Management: Ensures smooth operation and management of virtual machines.

**Technologies**
Azure Automation: For automating the VM startup process.
Automate: To schedule and automate tasks.
Microsoft Teams API: To send notifications to a Teams channel.
PowerShell: For scripting automation in Azure.
Azure VM: Cloud-based virtual machine for deployment.


**Azure Automation Setup:**
Create a new runbook in Azure Automation.
Paste the PowerShell script from the repository.

**Automate Configuration:**
Configure Automate to schedule the VM startup task.
Microsoft Teams Integration:

Set up the Teams webhook for task status notifications.
Usage
The script automatically starts the VM based on the defined schedule.
Notifications are sent to the Teams channel when the task completes.
