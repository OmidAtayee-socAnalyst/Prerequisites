# Prerequisites:
For this project, we need to have the following prerequisites accomplished:
1. A VirtualBox setup with Kali & Windows VMs installed
2. VMs configured so they can talk to each other
3. Splunk & Sysmon installed on the target machine (We want to make sure to look at the telemetry)
# VirtualBox Setup:
<img width="1282" height="799" alt="vbox-kali win" src="https://github.com/user-attachments/assets/827c0430-5a0d-4b81-bd6c-d9cb4dcc2b29" />

# Configuring VMs:

Network configuration for Kali VM
<img width="1186" height="801" alt="conifgVms1" src="https://github.com/user-attachments/assets/12d6c231-cce1-48b3-98b3-0c10115cfb1d" />

Network Configuration for Win10
_It is just the same as configuring Kali!_

# Installing Splunk and enabling it to ingest logs from Sysmon

<img width="986" height="720" alt="addingendpointindex" src="https://github.com/user-attachments/assets/f31b0124-6650-4e41-82c4-cbff852e6052" />
<img width="1009" height="764" alt="addingDataToSplunk" src="https://github.com/user-attachments/assets/747640b4-a81a-49c3-9618-7acf6a7d9a8b" />
<img width="986" height="720" alt="addingendpointindex" src="https://github.com/user-attachments/assets/15bcbd8f-d30e-4d1d-8b67-5d4e52a3ce4a" />


# Assigning static IPs to both VMs:
<img width="698" height="550" alt="ipassignmentforKali" src="https://github.com/user-attachments/assets/b7d807bb-bb52-4f06-837d-3c0999c7349f" />
<img width="847" height="890" alt="confirmingtheIP" src="https://github.com/user-attachments/assets/48735a98-ee48-4170-88d4-39dbe58c51ad" />
<img width="1022" height="830" alt="changeadapter options" src="https://github.com/user-attachments/assets/7003e0ea-f1b5-499d-af56-80645eb47f90" />
<img width="1023" height="834" alt="internetprotocolVer4" src="https://github.com/user-attachments/assets/99e5441b-89b2-4999-9cbb-fa29f1f21f07" />
<img width="1021" height="834" alt="internetprotocolVer4IPassignment" src="https://github.com/user-attachments/assets/0bc9b3e5-7d98-43f9-b8e6-fc28c858a92b" />
<img width="1023" height="834" alt="ipconfig" src="https://github.com/user-attachments/assets/e7ec1e51-ac9e-44d3-9428-a7460f2cb673" />
