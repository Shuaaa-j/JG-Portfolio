# JG Master Portfolio: Cybersecurity, Artificial Intelligence & IT Fundamentals

## Executive Summary
* This repository serves as a centralized portfolio consolidating my complete work across GRC, cyber offense, defense, digital forensics, IoT security, AI,  and full-stack software engineering. 
---

## Core Competencies & Academics | Courses taken (Overall Weighted Grade 4.0)
* **Fundamentals:** Introduction to Computing, Fundamentals of Cyber Security, Codelab I & II, Web Dev 1, Databases, Software Engineering, Network Administration
* **Blue Team & Defensive Security:** Digital Forensics, Cyber Resilience, Intrusion Analysis and Response, Cyber Defence, Securing the Internet of Things, Critical Infrastructure
* **Red Team & Offensive Security:** Cyber Offence
* **GRC (Governance, Risk, and Compliance):** Cyber Crime, Law and Ethics
* **Advanced Technologies & Research:** Artificial Intelligence, Research Project

---

## 📁 01 | Governance, Risk, Compliance (GRC) & Strategy
*This layer establishes the threat context, user awareness standards, and the operational recovery playbooks mandated by enterprise compliance frameworks.*

*   **The Paradox of Digital Literacy: The Role of the Cyber Hygiene Gap in Increasing Social Engineering Susceptibility Among Young Adults in the UAE:** 
A quantitative multi-phase study ($N=113$) authored by Joshua Renzo Gofulco. Grounded in Protection Motivation Theory (PMT), the research maps how technical proficiency induces an overconfidence bias that collapses threat appraisals under psychological levers of Authority and Urgency
    *   [View Research Paper](./01-Governance-Risk-Compliance-and-Law/Research_Paper_Phishing.pdf)
*   **Evaluating Risk and Resilience: A Risk Management Framework for the Pingu Acquisition:** 
Analyzes a post-acquisition "Compliance Paradox" to transition an organization from a flat-network topology to a structured Zero Trust Architecture (ZTA) and Defense-in-Depth (DiD) posture using a tri-framework baseline (ISO/IEC 27001, NIST CSF, and Cyber Essentials Plus).
    *   [View Risk Management Framework](./01-Governance-Risk-Compliance-and-Law/Risk_Management_Framework_Pingu_Acquisition.pdf)

---

## 📁 02 | Offensive Operations & Defensive Analytics
*This hands-on technical validation layer demonstrates how simulated attacks are executed to test GRC policies, paired with active defensive tools used to monitor and assess infrastructure safety.*

*   **Cyber Offence Simulations Portfolio:** A technical portfolio detailing the execution of 99 distinct offensive tasks across a 10-week curriculum. Validated advanced scanning evasion, unauthenticated Active Directory/LDAP schema extraction ($T1087.002$), LLMNR/NBT-NS broadcast poisoning ($T1557.001$) via Responder, asynchronous network profiling using sx and Unicornscan, and more.
    *   [View 390-Page Portfolio](https://docs.google.com/document/d/1AejQFfuJbAlt4ubGGYppA03NVkl1UdHtRSsUFw1xezo/edit?usp=sharing)
*   **BriteSpark Enterprise Malware Analysis:** Static and dynamic forensic analysis of `SampleMal.exe` using Ghidra, IDA Pro, and an isolated INetSim environment. Traced file system manipulation, registry persistence ($T1547.001$), and outbound FTP data exfiltration ($T1041$), using local DNS redirection and Netcat on port 21 to intercept credentials.
    *   [View Vulnerability Assessment Report](./02-Cyber-Offence-&-Defence/Network_Intrusion_Analysis_Report.pdf)

---
## 📁 03 | Artificial Intelligence & Full-Stack Software Engineering
*The building and automation layer. This section focuses on secure systems design, full-stack software development, and leveraging machine learning and deep learning to scale threat detection mechanisms.*

*   **FitnessGuard: A Hardened IoT Biometric Auditor for National Security and Military Readiness:** An Internet of Battlefield Things (IoBT) security solution deploying a dual-model machine learning pipeline[cite: 8]. Implements a Random Forest noise filter alongside a 3-layer deep Multi-Layer Perceptron (MLP) feed-forward neural network to achieve an ROC-AUC of 0.83 against non-linear adversarial data poisoning[cite: 8]. Features a SHA-256 cryptographic integrity gate provenance check and statistical Z-score anomaly filtering via SciPy[cite: 8].
    *   [View IoT Security Paper (PDF)](./03-Artificial-Intelligence-&-Full-Stack-Software-Engineering/IOT%20Security%20Paper.pdf)
*   **Clustering-Based Intrusion Detection Study:** An unsupervised machine learning study evaluating K-Means and Agglomerative Hierarchical Clustering algorithms using the `CICIDS2017` network traffic dataset[cite: 1]. Assesses structural trade-offs between computational scalability and cluster interpretability across both unsupervised (Silhouette/Davies-Bouldin) and supervised performance metrics, backed by an interactive Streamlit application deployment[cite: 1].
    *   [View Research Paper (PDF)](./03-Artificial-Intelligence-&-Full-Stack-Software-Engineering/Clustering-Based%20Intrusion%20Detection_%20A%20Comparative%20Analysis%20Study%20of%20K-Means%20%26%20Hiera....pdf)
*   **OkeyDokey Standalone Desktop Password Manager:** A secure, decentralized desktop credential vault developed in Python under the Scrum Agile framework[cite: 6]. Features strict local AES-256 equivalent data encryption (Fernet), cryptographic PIN-protected verification loops, an automated password complexity generator, and complete CRUD record operations, operating entirely offline to eliminate third-party dependencies[cite: 6].
    *   [View Software Engineering Documentation (PDF)](./03-Artificial-Intelligence-&-Full-Stack-Software-Engineering/OkeyDokey%20Software%20Engineering.pdf)
    *   [Browse App Source Code (GitHub)](https://github.com/EurekaAUH/PasswordManager.git)
*   **Interactive Gaming Database Web Application:** A responsive multi-page web platform utilizing HTML5, CSS3, and JavaScript, hosted entirely on GitHub Pages[cite: 7]. Features complex frontend components including asynchronous character array filtering, dynamic pop-up layouts, custom interactive cursor mechanics, and visual parallax scrolling effects designed to optimize user engagement[cite: 7].
    *   [Live Portfolio Site](https://shuaaa-j.github.io/)
    *   [View Project Documentation (PDF)](./03-Artificial-Intelligence-&-Full-Stack-Software-Engineering/Web%20Application%20Documentation.pdf)
    *   [Browse Frontend Source Code (GitHub)](https://github.com/Shuaaa-j/Shuaaa-j.github.io.git)
