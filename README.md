## Final-Engagement
Attack, Defense and Analysis of a Vulnerable Network


### Unit Description

In this project, I will be working as a Security Engineer for X-CORP, supporting the organization's SOC infrastructure. The SOC analysts have noticed some discrepancies with alerting in the Kibana system and the manager has asked the security engineering team to investigate and confirm that newly created alerts are working.

To start, my team needs to confirm that newly created alerts are working. Once the alerts are working, I will then monitor live traffic on the wire to detect any abnormalities that aren't reflected in the alerting system. Then, I will report back all of my findings to both the SOC manager and the Engineering Manager with appropriate analysis.


### Unit Objectives 

<details>
    <summary>Click here to view the unit objectives.</summary>

  <br>

- Alert and Attacking Target 1

    - Configure alerts in Kibana 
    - Attack a machine on the network.
    - Capture the flag on the victim machine.

- Wireshark Strikes Back

    - Capture network traffic
    - Investigate a number of suspicious activities
    - Collect corporate misuse evidence
    - Work in groups to create a presentation

- Final Group Presentations

    - Complete and submit group presentations
    - Submit an offensive red team analysis
    - Submit a defensive blue team analysis
    - Submit a network forensic analysis. 

</details>


### Lab Environment


<details><summary>Lab Details</summary>
<br>

In this unit, you will be using a new Web Vulns lab environment located in Windows Azure Lab Services. RDP into the **Windows RDP host machine** using the following credentials:

  - Username: `azadmin`
  - Password: `p4ssw0rd*`

This is a diagram of the network and the machines that will be used in this lab:

![](https://github.com/raospiratory/Final-Engagement/blob/main/Images/final-project-setup.png)

Open the Hyper-V Manager to access the nested machines:

**ELK machine credentials:** The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
- Username: `vagrant`
- Password: `vagrant`
- IP Address: `192.168.1.100`

**Kali:** A standard Kali Linux machine for use in the penetration test on Day 1. 
- Username: `root`
- Password: `toor`
- IP Address: `192.168.1.90`

**Capstone:** Filebeat and Metricbeat are installed and will forward logs to the ELK machine. 
- IP Address: `192.168.1.105`
   - Please note that this VM is in the network solely for the purpose of testing alerts.

**Target 1:** Exposes a vulnerable WordPress server.
- IP Address: `192.168.1.110`

**Target 2:** Students should ignore Target 2 until they have completed all other parts of the project.

</details>  

---

![Network Diagram](https://github.com/raospiratory/Final-Engagement/blob/main/Diagram/NetworkDiagram.png)

### Description of the Topology

The main purpose of this network is to expose an attack within a vulnerable VM within your environment. After, we will be collecting logs and data from the attack and analyzing the extracted data and visualize the results. We will be using Azure Lab Services. RDP into the Windows RDP host machine and then opening the Hyper-V Manager to access the nested machines: 
- Kali VM - Attacker Machine
- Capstone VM - Targeting Machine
- ELK VM - Network monitoring with Kibana to use the logs to extract data and visualizations 
- Target 1 VM - Targeting Machine
- Target 2 VM - Targeting Machine

---


### Reports
- To view the Offensive Report Analysis for this project please click [here](https://github.com/raospiratory/Final-Engagement/blob/main/Presentation/RedTeamReport.pdf).

- To view the Defensive Report Analysis for this project please click [here](https://github.com/raospiratory/Final-Engagement/blob/main/Presentation/BlueTeamReport.pdf).

- To view the Network Report Analysis for this project please click [here](https://github.com/raospiratory/Final-Engagement/blob/main/Presentation/NetworkAnalysis.pdf).

---


### Presentation
To view the Presentation for this project please click [here](https://github.com/raospiratory/Final-Engagement/blob/main/Presentation/FinalPresentation.pdf).

---


### Additional Reading and Resources

<details> 
<summary> Click here to view additional reading materials and resources. </summary>
</br>

These resources are provided as optional, recommended resources to supplement the concepts covered in this unit.

- [SANS Pentesting Cheatsheet](https://www.sans.org/blog/sans-poster-building-a-better-pen-tester-pdf-download/)


</details>

---
