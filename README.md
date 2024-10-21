# Active-Directory-Project
This project involves building and securing an Active Directory environment by setting up virtual machines, configuring Sysmon and Splunk for monitoring, and installing Active Directory. It also includes testing security with brute force attacks from Kali Linux, viewing telemetry in Splunk, and running atomic tests with ART.

# Step-1: Created a Logical Diagram using draw.io https://www.drawio.com/

![AD Project](https://github.com/user-attachments/assets/7c7c3952-39e0-43cb-be46-573c25a9c8eb)

# Step-2: Installed Virtual Machines 

![Virtual Machines](https://github.com/user-attachments/assets/351792a7-830d-4ce6-94b5-30d10e717ae8)

# Step-3: Install & Configure Sysmon, Splunk on both Windows target machine & Windows Server

![Splunk Forwarder   Sysmon](https://github.com/user-attachments/assets/3b619c66-d37e-4d59-a747-b192ad108c60)

# Rename Windows 10 to target-PC

![Rename](https://github.com/user-attachments/assets/88f19669-a4a1-4aa1-9ba3-1faa0f1cb249)

# Verified that SplunkForwarder is running on Host

![Splunk Forwarder](https://github.com/user-attachments/assets/bdd16c60-ba1a-4e4c-8999-0fb287674d9f)

# Verified endpoint is genterating events

![Endpoint](https://github.com/user-attachments/assets/39dda06c-910d-4766-9b3f-021ce2827eac)

# Step-4: Install and configure Windows server

# Created Active Directory karthik.domain 

![Added WIn server   Win 10](https://github.com/user-attachments/assets/e52f77a6-55ad-4805-a52e-d611ae6348d1)

# Created Active Directory karthik.domain

![Domain](https://github.com/user-attachments/assets/5b00ea26-9098-48d1-a944-632a1f3feaaf)

# Created Organizational Unit HR & IT and users vijayaA, sahanaA in karthik.domain

 Organizational Unit HR ![HR](https://github.com/user-attachments/assets/06834537-9eb4-498c-bb6e-ae00d89a776f)

 Organizational Unit IT ![IT](https://github.com/user-attachments/assets/bb01c6a6-0145-49b1-b304-32e089b992d7)

# Step-5: Installed Kali Linux for Brute Force Attack & View Telemetry in Splunk

![RDP Brute](https://github.com/user-attachments/assets/a42ada35-a4bf-4498-b8d3-4d901951ed45)

# Detection of Event Code 4625 (Failed Login Attempts)

![Failed login](https://github.com/user-attachments/assets/d40d3fca-b1a0-481e-952e-abc2fdeca483)

# Detection of Event Code 4624 (Successful Login Attempts)

![Successful login](https://github.com/user-attachments/assets/5f82705a-5e4e-475f-a03c-95dd9222feed)

# Count of Event Code 4625

![4625 Count](https://github.com/user-attachments/assets/ab1f6fb0-1cc1-4928-b8a8-b589aa2ec13d)

# Installing ART (Atomic Red Team) in Windows 10

![ART](https://github.com/user-attachments/assets/42424177-4197-4a10-a0a5-3515ed631c71)

# Splunk Events of Atomic Red Team

![ART Events](https://github.com/user-attachments/assets/6483d8ae-fa70-477b-9737-16016447d927)

# Splunk Events of NewLocalUser

![NewLocalUser](https://github.com/user-attachments/assets/c1def420-fe92-423d-aabd-1765d6c3adaa)

# Splunk Events of T1136.001 & T1059.001

![T1136 001](https://github.com/user-attachments/assets/c9013d1f-e0dd-4ef2-9414-a0f1f750aaff)

![T1059 001](https://github.com/user-attachments/assets/91c57db3-f7a2-4882-a01f-81dfa7a8621b)

# Splunk Events of Powershell

![Powershell](https://github.com/user-attachments/assets/dd312e15-f256-4f58-adfc-47a5ee9b5fde)
