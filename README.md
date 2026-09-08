# Wazuh Security Monitoring and Compliance 

## Executive Summary

This project focused on monitoring security events using Wazuh and evaluating their compliance significance.

The primary event analyzed involved the addition of a user account to a security-enabled local group on a Windows system. Such activity is important because privilege changes are frequently associated with privilege escalation, unauthorized access, and persistence techniques.


## Objectives

* Deploy and utilize Wazuh for security monitoring.
* Analyze Windows security events.
* Understand compliance implications of monitored activities.
* Demonstrate SIEM-based detection capabilities.


## Technologies Used

* Wazuh
* Windows Event Logs


## Monitoring Activity

### Event Observed

The monitored event corresponded to:

**Event ID 4732**

This event indicates that a user account was added to a security-enabled local group.


## Security Significance

Privilege-related changes are important because attackers often:

* Escalate privileges after initial access.
* Add accounts to privileged groups.
* Establish persistence mechanisms.
* Expand access to sensitive systems.

Monitoring such activities helps security teams identify potentially suspicious behavior.


## Wazuh Detection Capability

Wazuh successfully captured and displayed the event within the monitoring dashboard, demonstrating its usefulness for:

* Security monitoring
* Alert review
* Audit logging
* Incident investigation


## Compliance Analysis

Monitoring and logging privilege changes supports several compliance objectives, including:

### Access Control

Organizations must maintain visibility into changes affecting user privileges and access rights.

### Audit Logging

Security events should be recorded for investigation and accountability.

### User Accountability

Administrative actions should be traceable to individual users.


## Relevant Frameworks

The monitored activity aligns with requirements commonly found in:

* NIST
* ISO 27001
* PCI-DSS
* HIPAA


## Risk Assessment

### Risk

Unauthorized modification of privileged groups.

### Potential Impact

* Unauthorized access
* Elevated privileges
* Insider misuse
* Regulatory non-compliance

### Mitigation

* Continuous monitoring
* Alerting on privilege changes
* Least-privilege access controls
* Periodic audit reviews


## Lessons Learned

The project demonstrated that SIEM platforms can provide valuable visibility into security-sensitive administrative actions.

Even routine account-management events can become important indicators of compromise when viewed within a broader security context.


## Skills Demonstrated

* SIEM Operations
* Log Analysis
* Security Monitoring
* Compliance Awareness
* Event Investigation
* Threat Detection

