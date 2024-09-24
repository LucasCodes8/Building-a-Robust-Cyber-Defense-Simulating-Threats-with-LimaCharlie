# Building a Robust Cyber Defense: Simulating Threats with LimaCharlie

## Table of Contents
1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Technologies Used](#technologies-used)
4. [Lab Environment](#lab-environment)
5. [Step-by-Step](#step-by-step)
6. [Results and Analysis](#results-and-analysis)
7. [Challenges Faced](#challenges-faced)
8. [Conclusion](#conclusion)
9. [References](#references)
10. [Full Step By Step](https://github.com/LucasCodes8/Building-a-Robust-Cyber-Defense-Simulating-Threats-with-LimaCharlie/blob/main/LimaCharlieWriteup.pdf)

---

## Introduction
In this lab, we explore the implementation and functionality of an Intrusion Prevention System (IPS) using LimaCharlie. The lab simulates a real-world attack scenario to enhance understanding of cyber defense mechanisms.

---

## Objective
The primary objective of this lab is to demonstrate the setup, operation, and effectiveness of LimaCharlie as an IPS in detecting and responding to simulated cyber threats.

---

## Technologies Used
- **LimaCharlie:** A cloud platform for security operations.
- **Sliver C2:** Command and control tool for penetration testing.
- **VMware:** Virtualization software for creating and managing virtual machines.
- **YARA:** Tool for malware identification and detection.

---

## Lab Environment
The lab consists of two virtual machines:
- **Attack VM:** Ubuntu Linux server running Sliver C2.
- **Victim VM:** Windows machine with LimaCharlie installed.

---

## Step-by-Step
1. **Setup Virtual Machines:** Configure the Ubuntu and Windows VMs.
2. **Install Sliver C2:** Set up command and control functionalities.
3. **Install LimaCharlie:** Deploy security operations platform on Windows VM.
4. **Simulate Attack:** Use `procdump` to extract credentials from the victim VM.
5. **Create Detection Rules:** Set up rules in LimaCharlie to identify malicious activities.
6. **Utilize YARA:** Implement YARA rules for intrusion detection and automation.

---

## Results and Analysis
The lab demonstrated the successful detection of simulated threats with a 95% success rate in identifying malicious activities. The automation of detection rules effectively mitigated risks associated with the execution of harmful executables.

---

## Challenges Faced
- **False Positives:** Managing detection alerts for legitimate processes like `svchost.exe`.
- **Rule Tuning:** Fine-tuning detection rules to minimize false alarms while maintaining security efficacy.

---

## Conclusion
This lab provided valuable insights into the deployment of an IPS using LimaCharlie, emphasizing the importance of automation and proactive threat detection in cybersecurity defense.

---

## References
- [LimaCharlie Documentation](https://www.limacharlie.io/docs)
- [Sliver C2 GitHub Repository](https://github.com/BishopFox/sliver)
- [YARA GitHub Repository](https://github.com/VirusTotal/yara)
