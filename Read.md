Convert2RHEL Automation Playbook

 About This Project

Welcome to Convert2RHEL Automation! 
This Ansible playbook automates the conversion of CentOS to RHEL (Red Hat Enterprise Linux) using the official Convert2RHEL tool. No more manual steps—just sit back and let Ansible do its magic! 

Features

🛠️ Pre-checks to ensure a smooth conversion process
🔄 Automatically downloads and configures the Convert2RHEL repository
🖥️ Handles package updates and GPG key management
🔐 Securely configures authentication for Red Hat Subscription Manager
🚀 Runs Convert2RHEL and reboots the system post-conversion
✅ Post-checks to verify successful migration to RHEL
📜 Prerequisites

---------------------------------------
Before you begin, ensure you have:
    - Ansible installed on your control machine 
    - A CentOS machine ready to be converted (preferably a fresh install) 
    - A Red Hat Subscription with an Activation Key 


Kennytoro 