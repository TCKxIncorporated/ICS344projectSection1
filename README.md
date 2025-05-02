# ICS344 Course Project Repository

## 📁 Project Structure
This repository contains our complete implementation of the ICS344 project, organized into three main phases:
- `Phase1/`: Service setup and compromise using Metasploit and a custom exploit.
- `Phase2/`: Security Information and Event Management (SIEM) integration and attack visualization using Splunk.
- `Phase3/`: Defensive countermeasure deployment and validation against the original attack.

Each phase folder contains:
- Screenshots
- Scripts or configuration files
- A brief documentation of the sub-steps

---

## 👥 Group Information
- **Group Number**: Group 9
- **Group Members**:
  - HUSSAIN ALNASSER — ID: [202172010]
  - NAIF ALQAHTANI — ID: [202172110]
  - ALI AL SHAIKH AHMED — ID: [202179050]

---

## 🛠️ Work Distribution
| Task | Team Member(s) |
|------|----------------|
| Metasploit Exploits & Script | [NAIF ALQAHTANI] |
| Splunk Configuration & SIEM Integration | [HUSSAIN ALNASSER] |
| Defense Implementation & Testing | [HUSSAIN ALNASSER] |
| Documentation & Screenshots | All Members |

---

## 📌 Phase 1: Setup and Compromise

### ✅ Objectives
- Deploy Metasploitable3 (victim) and Kali Linux (attacker) in an isolated network.
- Launch a successful SSH brute-force attack using:
  - Metasploit's `ssh_login` module.
  - A custom Python exploit using Paramiko.

---

## 📊 Phase 2: SIEM Integration and Visualization

### ✅ Objectives
- Set up Splunk Enterprise (on Kali Linux) and a Splunk Universal Forwarder (on the victim).
- Forward system logs from `/var/log/auth.log`.
- Visualize brute-force login attempts using Splunk dashboards and search queries.

---

## 🔐 Phase 3: Defensive Strategy

### ✅ Objective
- Mitigate the SSH attack vector used in Phase 1.
- We changed the default password of the `vagrant` user.
- Re-ran the same Metasploit attack to validate the effectiveness of the defense.




