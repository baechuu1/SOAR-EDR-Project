# SOAR-EDR-Project
<img width="250" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/7b8c96d9-8f8c-470c-b3e2-1fbd147361647">
<img width="250" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/f0efc934-dac8-41a4-9ece-1d8f33d45624">
<img width="250" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/212d5e89-80e7-4495-a770-1b2929d12a41">

## PROJECT OBJECTIVE
To gain hands-on experience in implementing and integrating various security tools within a SOAR-EDR framework to improve threat detection, analysis, and response. By leveraging Tines, the project focuses on developing a playbook that automates threat detection, generates alerts, and sends notifications to both Slack and email for SOC analysts. This initiative aims to enhance overall security operations by configuring and utilizing tools such as LimaCharlie and Tines, and creating rules to drive more effective and efficient threat management.

## TOOlS

- Vultr: A cloud infrastructure provider offering scalable virtual machines and storage solutions for deploying and managing applications and services.
- Tines: An automation platform designed to orchestrate and streamline security operations by creating workflows for automating tasks and integrating with various security tools.
- Slack: A messaging and collaboration platform that facilitates real-time communication and coordination among team members through channels, direct messages, and integrations.
- Lazagne: An open-source tool used for discovering and recovering passwords stored by various applications and browsers, aiding in credential management during security investigations.
- LimaCharlie: A comprehensive security platform offering endpoint detection and response (EDR), threat intelligence, and automation tools to enhance visibility, detection, and response capabilities across diverse IT environments.

## SKILLS GAINED

- SOAR & EDR: Workflow Automation: Expertise in designing and implementing automated workflows for Security Orchestration, Automation, and Response (SOAR) and Endpoint Detection and Response (EDR) to enhance security operations and incident management.
- Cloud Infrastructure Management: Expertise in deploying, configuring, and managing virtual machines and cloud resources to support various applications.
- Credential Discovery: Experience in recovering and managing credentials from various applications to assist in security investigations.
- Real-Time Communication and Collaboration: Proficiency in facilitating effective team communication and coordination through messaging and collaboration platforms.


## OUTCOME

##### 1. SOAR EDR Project diagram
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/6df0e245-8933-473e-af2b-fd435f6a96f7">


##### 2. Successfully deployed cloud window server using Vultr and using RDP to connect to the server
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/93b22f0b-b21b-4cbb-ad28-98c78b8fe4f5">


##### 3. Linking the cloud instance to LimaCharlie for EDR
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/557aa369-b2e2-4a13-afc3-eb76753f654f">


##### 4. Running LaZagne.exe on window server to create alerts on LimaCharlie
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/70f3b0d0-92c0-457d-9c59-f742cb1d4997">


##### 5.Alerts generated from LimaCharlie detecting the use of LaZagne on window server
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/0233492b-399f-407f-bb1b-64c8879e0b50">


##### 6.Creating Detection&Respond rules to detect LaZagne and with descriptions to ehance alert sensor
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/93fad807-9362-44b2-aa79-c1a6e2652869">


##### 7.Developed a Tines playbook to automate sending alerts to Slack and email and to isolate the machine if the user confirms with a "Yes" prompt.
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/383d1e53-86c0-40f7-ac21-857890060d45">


##### 8.User is prompted Yes or No. Whether to isolate the machine when LaZagne has been deteced.
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/a26ebf81-3c4e-41b9-8dfb-6efb77ea546e">


##### 9.Messages is sent to Slack with the details of the alert
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/4aa87ba6-7581-4008-9e11-8e66ad426a90">


##### 10.Email is sent with the same description 
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/f5772a29-24f9-4845-9d53-d00a67dc1346">


##### 11.LimaCharlie successfully isolated the machine
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/a1601594-fc7d-435f-a261-5d4a091649da">


##### 12.No connection to the window server. 
<img width="850" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/f9758b05-5f97-4d48-b9d2-5294a994425e">


