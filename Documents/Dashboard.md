# 1. Last Log Received 
The Workbook provides a comprehensive visualization of the logging activity for Azure resources connected to your Azure Sentinel workspace. It enables administrators and security teams to monitor the health of data connectors, track the timeliness of logs, and quickly identify resources that are not sending logs as expected

### Last Log Received
To determine the last log received for all Azure resources in Azure Sentinel, you can query the logs to check the most recent log entries for each resource type or data connector. We can show the visualiazation like Computer name, Source, Last log recived and Time. We can increase or decrease Thershold of last log recived by default it set to 30min.



![image](https://github.com/user-attachments/assets/984aef93-70fe-45d6-8aa5-aab0003f99c7)


### Last Heartbeat Received
To determine the last log received for Heartbeat in Azure Sentinel, you can query the logs to check the most recent log entries for each computer. We can increase or decrease Thershold of last log recived by default it set to 30min.


![image](https://github.com/user-attachments/assets/e8a681e6-65f2-4f70-9c52-9b7e3ad97122)


Similar to the previous example, we can also design distinct views for various data sources so that analysts may see a clear picture of their environment. for example. Last SQL Log Received,Last Oracle Log Received etc.


# 2. VM Summary 

The VM Summary Workbook in Azure Sentinel provides an extensive overview of your virtual machines (VMs) and their operational status. It is designed to give security analysts and administrators real-time visibility into the state of virtual machines, their environments, and the associated telemetry data. This workbook ensures that all critical VMs are monitored effectively and highlights potential issues like disconnected agents or inactive systems.

### Virtual Machine View
Displays detailed information about each virtual machine, such as name, OSTyoe and associated environment.

![image](https://github.com/user-attachments/assets/ac25e156-39f2-4f21-bbf8-62ef6390dcd9)


### Computers by Computer Environment
Categorizes machines by their environment (e.g., Azure, on-premises, or hybrid environments) in pie chart.

![image](https://github.com/user-attachments/assets/f44bb0a0-28aa-4936-a161-187190a25a25)


### VMs Online
Shows which virtual machines are online and actively sending telemetry.

![image](https://github.com/user-attachments/assets/3aa47683-7f0f-4cab-a7da-408ff99bcc51)


### Last 24 Hours: Agent Heartbeat Data
Tracks the health and connectivity of the Azure Monitor Agent (AMA) or Log Analytics Agent for all VMs within the last 24 hours.

![image](https://github.com/user-attachments/assets/321d7436-bb1c-4425-bcda-7ed128495f35)


# 3. VM Summary 

