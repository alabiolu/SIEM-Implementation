# SIEM Implementation and Log Analysis

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Elastic Stack SIEM Configuration and Management.
- Security Event Simulation and Analysis.
- Visualization and Alerting in SIEM.

### Tools Used

- Elastic SIEM
- Linux Command Line.


## Steps
Set up a Linux based system using VirtualBox.

Install Java using the command sudo apt install openjdk-11-jdk as this is a requirement to install ElasticSearch


![Screenshot 2024-08-02 220500](https://github.com/user-attachments/assets/f1db5150-b2ef-40bf-8df9-84b286abe624)

*Ref 1: SIEM Diagram*

The above code was used to install ElasticSearch on the Linux for connecting Elastic SIEM to read logs from the Linux machine

Confirm if the Elastic SIEM is running on the Linux machine after installation.

![Screenshot 2024-08-02 220929](https://github.com/user-attachments/assets/2477b3f9-dd58-40a3-af0e-ed74206de2e2)

*Ref 2: SIEM Diagram*
The first line of command from the above is to confirm that the elastic SIEM is working on the machine.

After making sure that Elastic is running I run some couple on NMAP command so that the SIEM dashboard can capture some logs so as to be able to create a dashboard.

![Screenshot 2024-08-02 221318](https://github.com/user-attachments/assets/f94d08df-b7aa-4206-af50-d142dfb62f47)

*Ref 2: SIEM Diagram*

Viewing the dashboard on Elastics in the last 24 hours display the below image.

![Screenshot 2024-08-03 111513](https://github.com/user-attachments/assets/3a1b0e0b-6f8d-441f-92de-80be4a203d0d)

*Ref 3: SIEM Diagram*
