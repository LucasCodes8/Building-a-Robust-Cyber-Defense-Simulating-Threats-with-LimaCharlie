# Building-a-Robust-Cyber-Defense-Simulating-Threats-with-LimaCharlie

## Table of Contents
1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Technologies Used](#technologies-used)
4. [Lab Environment](#lab-environment)
5. [Step-by-Step Procedure](#step-by-step-procedure)
6. [Results and Analysis](#results-and-analysis)
7. [Challenges Faced](#challenges-faced)
8. [Conclusion](#conclusion)
9. [References](#references)
10. [Full Write-Up](https://github.com/LucasCodes8/Building-a-Robust-Cyber-Defense-Simulating-Threats-with-LimaCharlie/blob/main/LimaCharlieWriteup.pdf)

---

## Introduction
In the contemporary landscape of cybersecurity, Intrusion Prevention Systems (IPS) play a pivotal role in safeguarding networks from an array of threats. This lab provides an in-depth exploration of LimaCharlie, a robust cloud-based security operations platform. Through a simulated attack scenario, participants will gain hands-on experience in implementing security measures and responding to potential threats, thereby enhancing their understanding of proactive cyber defense strategies.

---

## Objective
The primary objective of this lab is to elucidate the functionalities of LimaCharlie as an IPS, emphasizing its capabilities in threat detection and response. Participants will learn to deploy detection rules, automate responses to security incidents, and evaluate the effectiveness of these measures in a controlled environment. By the end of the lab, participants should be equipped with the foundational skills necessary for effective cybersecurity defense.

---

## Technologies Used
- **LimaCharlie:** A comprehensive cloud platform that facilitates security operations, offering features such as host intrusion detection (HID), host intrusion prevention (HIP), and advanced log analysis.
- **Sliver C2:** An open-source command and control tool designed for penetration testing, enabling remote exploitation of vulnerabilities.
- **VMware:** A virtualization solution that allows for the creation and management of virtual machines, providing a flexible testing environment.
- **YARA:** A powerful tool used for the identification and classification of malware, enabling the creation of custom detection rules.

---

## Lab Environment
The lab is structured around two distinct virtual machines:
- **Attack Virtual Machine (VM):** An Ubuntu Linux server configured as the attack platform, where Sliver C2 is installed to simulate malicious activities.
- **Victim Virtual Machine (VM):** A Windows operating system configured with LimaCharlie, serving as the target for simulated attacks and the focal point for defense strategies.

---

## Step-by-Step Procedure
1. **Setup Virtual Machines:** Configure the Ubuntu and Windows VMs in VMware to establish a secure and isolated testing environment.
2. **Install Sliver C2:** Deploy Sliver C2 on the Ubuntu server to enable command and control functionalities for penetration testing.
3. **Install LimaCharlie:** Set up LimaCharlie on the Windows VM, configuring it to monitor and manage security operations effectively.
4. **Simulate Attack:** Execute the `procdump` command to extract credentials from the victim VM, demonstrating a typical attack scenario.
5. **Create Detection Rules:** Develop and implement tailored detection rules within LimaCharlie to identify and alert on malicious activities associated with the simulated attack.
6. **Utilize YARA:** Implement YARA rules for automated intrusion detection, showcasing the integration of signature-based detection in a proactive security posture.

---

## Results and Analysis
The lab successfully demonstrated LimaCharlie’s capabilities in identifying and mitigating simulated threats. A rigorous evaluation revealed a 95% success rate in detecting malicious activities, underscoring the effectiveness of automated detection and response mechanisms. The integration of YARA rules further enhanced the system's ability to recognize and respond to emerging threats in real-time.

---

## Challenges Faced
- **False Positives:** The detection of legitimate processes, such as `svchost.exe`, generated numerous false positive alerts, necessitating careful tuning of detection rules to differentiate between benign and malicious activities.
- **Rule Tuning:** The process of refining detection and response rules required iterative testing to balance sensitivity and specificity, minimizing disruptions to normal operations while maintaining security vigilance.

---

## Conclusion
This lab provided a comprehensive examination of the deployment and functionality of an Intrusion Prevention System using LimaCharlie. Participants engaged in practical exercises that highlighted the importance of automation, proactive threat detection, and continuous monitoring in effective cybersecurity defense. The hands-on experience gained through the simulation of attack scenarios and the development of detection rules solidified key concepts essential for aspiring cybersecurity professionals.

---

## References
- [LimaCharlie Documentation](https://www.limacharlie.io/docs)
- [Sliver C2 GitHub Repository](https://github.com/BishopFox/sliver)
- [YARA GitHub Repository](https://github.com/VirusTotal/yara)
