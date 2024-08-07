# LAW-Configuration

## Objective
The objective of this lab project is to configure a central log repository using Azure's Log Analytics Workspace (LAW). The goal is to centralize log data from various sources, enhancing visibility and facilitating comprehensive security monitoring and analysis.

## Technologies Employed
- Microsoft Azure: Cloud computing platform for hosting and managing resources.
- Log Analytics Workspace (LAW): Central repository for collecting and analyzing log data.
- Microsoft Sentinel: SIEM tool integrated with LAW for advanced security analytics.
- Microsoft Defender for Cloud: Security management tool for protecting Azure resources.
- NSG Flow Logs: Network Security Group flow logs for traffic analysis.
- Azure Monitor: Service for collecting, analyzing, and acting on telemetry from cloud and on-premises environments.
- Entra ID: Identity management service for authentication and audit logging.
- Blob Storage: Azure storage service for storing and managing data.
- Key Vault: Service for securely storing and accessing secrets, keys, and certificates.

## Methodologies And Execution
### Connecting Microsoft Sentinel to the LAW:

Integrate Microsoft Sentinel with the created Log Analytics Workspace.
Ensure seamless data collection and security event monitoring through Sentinel.

### Enabling Microsoft Defender for Cloud and Forwarding Logs to LAW:

Enable Microsoft Defender for Cloud for the relevant resources.
Configure it to forward appropriate types of logs (e.g., security alerts, recommendations) to LAW.
Set up continuous export to ensure ongoing log forwarding.

### Creation of NSG Flow Logs and Forwarding to LAW:

Enable NSG Flow logs to capture network traffic data.
Configure the flow logs to be forwarded to LAW for centralized analysis.

### Creating Diagnostic Settings for Entra ID Audit and Sign-In Logs:

Set up diagnostic settings for Entra ID to capture audit and sign-in logs.
Forward these logs to LAW for monitoring and security analysis.

### Creating Diagnostic Settings for Azure Monitor Activity Logs:

Configure diagnostic settings to capture Azure Monitor activity logs.
Forward these logs to LAW to track changes and monitor resource activity.

### Creating Diagnostic Settings for Blob Storage and Forwarding Logs to LAW:

Set up diagnostic settings for Blob Storage to capture access and activity logs.
Forward these logs to LAW for centralized storage and analysis.

### Creating Diagnostic Settings for Key Vault and Forwarding Logs to LAW:

Enable diagnostic settings for Key Vault to capture audit logs.
Forward these logs to LAW to monitor access and operations on secrets, keys, and certificates.

### Configuring Data Collection Rules from Honeypots:

Set up data collection rules to capture logs from honeypot (vulnerable virtual machines) deployments.
Forward these logs to LAW to analyze attacker behavior and activity.

## Conclusion
The configuration of the central log repository in Azure's Log Analytics Workspace provided several key insights: it centralized log data from multiple sources, offering a unified view of the security posture; enhanced visibility and monitoring of security events through logs from NSG Flow, Entra ID, Azure Monitor, Blob Storage, Key Vault, and honeypots; facilitated proactive threat detection and response with Microsoft Sentinel and Microsoft Defender for Cloud; and improved the capability for comprehensive security analysis and incident investigation. This setup significantly bolstered the overall security posture, enabling more effective threat detection and incident response, while providing valuable hands-on experience with configuring and managing Azure services for security monitoring.
