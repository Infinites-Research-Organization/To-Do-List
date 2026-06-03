# Open-Source Privacy & Defense Engineering: Project Roadmap

This repository serves as the centralized development roadmap and project tracker for the **Infinites Research Organization**. Our objective is to design, audit, and open-source non-destructive, passive, and privacy-preserving technologies that enhance individual sovereignty and situational awareness.

---

## Research & Development

Below is proposed projects that we can work on, feel free to add to this list if you're a member

### 1. Camera Detection & Network Auditing
*   **Project Name:** `cam-detect-cli`
*   **Core Objective:** Develop a terminal-based passive network utility to detect local Wi-Fi-enabled surveillance hardware.
*   **Technical Specifications:**
    *   Passive Wi-Fi frame analysis in monitor mode to identify anomalous, high-bandwidth streaming signatures.
    *   Hardware fingerprinting via MAC address OUI analysis and broadcast parsing (mDNS/uPnP).
    *   **Interoperability:** Native export functionality to standard `.pcap` files and structured telemetry feeds optimized for direct integration with **Kismet** and **Wireshark**.

### 2. Edge-Optimized Multi-Modal Drone Detection
*   **Project Name:** `uas-edge-vision-audio`
*   **Core Objective:** Build low-latency, early-warning classification models for commercial Unmanned Aerial Systems (UAS).
*   **Technical Specifications:**
    *   **Computer Vision (CV):** Lightweights custom object detection weights (optimized for YOLO architectures) trained specifically on low-altitude, variable-lighting drone profiles.
    *   **Acoustic DSP:** Audio classification algorithms trained on the micro-Doppler and RPM acoustic signatures of drone propulsion systems.
    *   **Hardware Target:** Designed strictly for resource-constrained edge devices (e.g., Raspberry Pi, NVIDIA Jetson Nano) to ensure accessible deployment.

### 3. Passive RF Drone Detection (SDR)
*   **Project Name:** `sdr-uas-passive-sniffer`
*   **Core Objective:** Engineer a passive Radio Frequency (RF) telemetry tracker utilizing Software Defined Radio hardware.
*   **Technical Specifications:**
    *   Receive-only parsing of common ISM bands ($2.4\text{ GHz}$ and $5.8\text{ GHz}$).
    *   Signal signature extraction for drone control links and analog/digital video downlinks.
    *   Zero-transmission architecture to ensure total compliance with international spectrum management policies.

### 4. Adversarial Machine Learning & AI-Camo
*   **Project Name:** `adversarial-camo-r&d`
*   **Core Objective:** Conduct defensive machine learning research to protect physical privacy against unauthorized biometric, object, and facial recognition models.
*   **Technical Specifications:**
    *   Generation of optimized geometric, high-contrast, and infrared-reflective patterns.
    *   Digital testing against standard open-source object detection models (e.g., COCO-trained architectures) to maximize evasion and bounding-box disruption.
    *   Development of physical canvas, textile, and patch blueprints for individual privacy preservation.

### 5. Compromising Emanations & Unintentional RF Detection
*   **Project Name:** `urfe-tempest-explorer`
*   **Core Objective:** Investigate the detection of non-networked electronic devices via their Unintentional Radio Frequency Emissions (URFE).
*   **Technical Specifications:**
    *   Utilizing high-gain directional antennas coupled with coherent SDR front-ends to sweep localized spectrums.
    *   Isolating the subtle electromagnetic footprints (TEMPEST) leaked by internal clock oscillators, circuit traces, and display logic boards.
    *   Algorithmic filtering to isolate device footprints from baseline environmental RF noise.

---

## ⚖️ Platform Compliance & Dual-Use Statement

All projects hosted under this framework adhere strictly to **GitHub’s Acceptable Use and Active Malware or Exploits Policies**. 

*   **Passive Architecture by Design:** Our software focus remains exclusively on **receive-only** signal processing, physical material modeling, local computer vision, and defensive data perturbation. 
*   **No Active Exploitation or Disruption:** None of the utilities listed in this roadmap contain code designed to inject malicious packets, execute denial-of-service (DoS) attacks, flood public spectrums, or jam/disrupt active network or hardware infrastructure. 
*   **Educational Purpose:** These tools are built to empower individuals, privacy advocates, and security auditors to verify the physical and digital boundaries of their own environments.
