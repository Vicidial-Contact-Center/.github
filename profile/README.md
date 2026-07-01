# Vicidial Contact Center Platform for Windows

<div align="center">
  <img src="https://www.asterisk.org/wp-content/uploads/Vicidial_vector_blue_square_20150302.png" alt="Vicidial Contact Center Platform" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Vicidial-Contact-Center)

---

## What is Vicidial?

Vicidial is a powerful open-source contact center platform that provides a complete solution for inbound, outbound, and blended call handling. It is the engine behind GOautodial and is trusted by thousands of call centers worldwide. Vicidial offers predictive dialing, automated call distribution (ACD), and real-time campaign management capabilities.

Infrastructure teams managing contact center operations benefit from Vicidial's comprehensive feature set, including advanced answering machine detection (AMD), call recording, and multi-tenant architecture. System administrators appreciate the flexible deployment options, extensive API, and the ability to scale from small teams to hundreds of agents.

---

## Screenshot Block

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUUC1kSy3joYVoGKAy14ijgKweMtogNpb3JB1QdTOJOpZBEXk9jcq5Yxk&s=10" alt="Vicidial Admin Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Vicidial-Contact-Center)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Predictive Dialing** | Adaptive dialing algorithm that automatically adjusts dialing speed based on agent availability  |
| **Inbound ACD** | Automated Call Distribution with skill-based routing, queue prioritization, and overflow handling  |
| **Answering Machine Detection** | Advanced AMD settings with configurable thresholds for detecting answering machines, voicemail, and live calls  |
| **Call Recording** | Full call recording with the option to store on your own FTP server  |
| **Campaign Management** | Create and manage outbound, inbound, survey, and broadcast campaigns with custom scripts  |
| **Agent Features** | Preview dialing, manual dialing, call transfer, conference, and disposition management  |
| **Supervisor Features** | Real-time dashboard, listen-in, barge-in, whisper, and force log-out capabilities  |
| **Multi-Tenant** | Support for multiple tenants and users with role-based permissions  |
| **Compliance** | FTC-compliant drop timer with safe-harbor message, DNC list, timezone restrictions  |
| **API Integration** | Extensive API for integration with third-party applications and custom code  |
| **Reporting** | Comprehensive real-time and summary reports with detailed call detail records (CDRs)  |
| **WebRTC Support** | Browser-based calling without additional software installation  |
| **Multi-Language** | Support for multiple languages in the agent interface  |

---

## Installation Guide

### Prerequisites

- Windows 10, Windows 11, or Windows Server (with virtualization)
- Dedicated server or cloud VM recommended
- Minimum 2 GB RAM, 2 CPU cores
- At least 20 GB available storage
- Network connectivity with public IP

### Option 1: Vicidial with GOautodial (Recommended)

GOautodial provides the easiest way to deploy Vicidial with a modern web interface.

**Step 1:** Download the GOautodial ISO from the official GitHub repository.

**Step 2:** Install on dedicated hardware or virtual machine.

**Step 3:** Follow the GOautodial post-installation configuration steps.

### Option 2: Vicidial Scratch Install on CentOS 7

For users preferring a raw Vicidial installation:

**Step 1:** Install CentOS 7 minimal on a dedicated server or VM.

**Step 2:** Download the Vicidial scratch install script:

```bash
wget http://downloads.eflo.net/vicidial-install-centos7.sh
