### Container Scanning POC Evaluation Criteria

Attribute |  Importance (Moscow) |  Assessed by: Security Leads; DTC Devops Rating; Demonstrator etc. |  Success Criteria |  Aqua |  Twistlock
---  |  ---  |  ---  |  ---  |  ---  |  ---
Container Defender  |  Must  |  Demonstrator  |  Defenders deployed and communicating with console (not Openshift)  |    |  
Host Defender |  Should |  Demonstrator |  Defender functionality running as a service  |   |  
Ability to detect and block vulnerabilities in containers |  Must |  Demonstrator |  Alerts raised and containers prevented from running |   |  
Ability to detect and block vulnerabilities in containers |  Must |  Security leads |  Overall assessment of CVE detection |   |  
Monitor and enforce compliance settings across the container environment |  Could |  Demonstrator |  Ability to define a governance policy and enforce it |   |  
Registry Scanning |  Should |  Demonstrator |  Registry connected and current state of image shown in console |   |  
Trusted Images |  Must |  Demonstrator |  Restrict deployment using whitelist |   |  
Runtime - Detection and Blocking |  Must |  Demonstrator - if we can create anomalous behaviour in a test container |  Alert raised when anomalous behaviour detected. Ability to isolate containers. |   |  
Incident Explorer Forensics |  Should |  Demonstrator |  View forensic data which consists of additional supplemental container runtime events that complement the events (audits) captured by scanner's runtime sensors. |   |  
Radar |  Could |  Demonstrator - Sock Shop Demo App |  Ability to view toplogy of application |   |  
Cloud Native Network Firewall - blocking |  Could |  Demonstrator  |  Ability to put a block in place between two services |   |  
Cloud Native Application Firewall - blocking |  Could |  Demonstrator  |  Ability to put a block in place in front of a container |   |  
Reporting |  Must |  Demonstrator |  View vulnerability, compliance, runtime, firewall and access data through dashboards |   |  
CI Pipeline Integration and Blocking |  Must |  Demonstrator |  Successfully see the vulnerability state of images using Jenkins  |   |  
Secrets Injection |  Could? |  Demonstrator |  Secrets are successfully injected in the container |   |  
Ease of configuration (set-up and administer (e.g policies)) |  Should |  Dev Ops Engineer  rating of demonstrator |  Positive feedback from Dev Ops Eng. |   |  
Ease of Use |  Should |  Dev Ops Engineer  rating of demonstrator |  Positive feedback from Dev Ops Eng. |   |  
Quality of documentation |  Should |  Dev Ops Engineer  rating of demonstrator |  Positive feedback from Dev Ops Eng. |   |  
Disconnected environment |  Must |  Demonstrator |  Run scans and drill into threat information without needing to access Internet |   |  
Update the scanning tools without internet connection  |  Must |  Demonstrator |  Update CVE information in an automated way |   |  
