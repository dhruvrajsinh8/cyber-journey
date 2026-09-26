# 🛡️ 90-Day Cyber Security & Purple Teaming Journey

> **"This is my 90 days cyber-learning journey"** — Documenting my daily hands-on transition from lower-intermediate to job-ready cybersecurity professional. Focused on **Purple Teaming** (bridging Blue Team Cyber Defence and Red Team Offensive Security) powered by **Python automation**.

---

## 🎯 Primary Focus Areas

- 🔵 **Blue Team & Cyber Defence**: SOC Analyst Tier 1 path, Network Traffic Analysis (Wireshark / Zeek), Incident Response, Endpoint Detection, and MITRE ATT&CK mapping.
- 🔴 **Red Team & Threat Research**: Offensive tactics, web exploitation, malware/model security (e.g., AI/ML supply chain attacks, unsafe deserialization).
- 🟣 **Purple Teaming**: Correlating offensive techniques with defensive detection signatures and mitigation strategies.
- 🐍 **Python for Security**: Scripting custom tools for network enumeration, log triage, IOC parsing, and automation.

---

## 📅 Daily Progress Tracker

All daily lab notes, scripts, exercises, and threat research logs are documented in:
👉 **[`progress.txt`](./progress.txt)**

---

## 📂 Repository Structure

- `progress.txt` — Chronological daily log of labs, concepts learned, and milestones.
- `index.py` — Python fundamentals practice.
- `ping.py` — Network availability & host check automation via Python `subprocess`.

---

## 🚀 Current Milestone
- [x] **Day 1 (2026-09-22)**: Setup & roadmap definition, Python subprocess automation (`ping.py`), initial Wireshark PCAP triage, and AI supply chain threat research.
- [x] **Day 2 (2026-09-23)**:
  - 🏆 **Completed JetBrains Web Server Exploitation Wireshark Lab (100%)**: TCP stream following, packet timestamp analysis, suspicious IP detection, and cmd/shell command execution extraction.
  - 🦜 **Parrot OS & Tooling**: Installed and configured Parrot OS security environment with active tooling.
  - 🌐 **VPN & Network Labs**: Configured and connected OpenVPN client tunnel to TryHackMe.
- [x] **Day 3 (2026-09-24)**:
  - 🛡️ **CyberDefenders FakeGPT Lab**: Chrome extension malware deconstruction, data theft analysis, covert `<img>` tag exfiltration, and anti-analysis evasion mechanisms.
  - 🤖 **PortSwigger Web Security Academy**: AI/ML LLM prompt injection & poisoning leading to Remote Command Execution (`ls`, `cat`) via chat interface.
  - 🐍 **Python Practice**: Fundamentals of data types, dynamic user input handling, and type casting.
- [x] **Day 4 (2026-09-25)**:
  - 🔍 **Reverse Engineering with Ghidra**: Explored stripped vs. non-stripped binaries, symbol tables (`.symtab` vs. `.dynsym`), and debug metadata.
  - ⚙️ **Decompiler Analysis**: Workflow for recovering execution flow in stripped binaries using entry point triage (`_start` to `main`), string cross-references (`XREFs`), and library import tracing.
- [x] **Day 5 (2026-09-26)**:
  - 🧩 **TryHackMe Reversing ELF (100%)**: Solved Linux crackmes using static analysis (`strings`, `readelf`, Ghidra) and dynamic runtime tracing (`ltrace`, `strace`, GDB).
  - 🦈 **Wireshark Deep Packet Analysis**: Investigated packet flows, anomaly patterns (port scans, beaconing), export object carving, and protocol dissection.
  - 📊 **Python for Security Data Analytics**: Explored `pandas`, `matplotlib`, and `seaborn` for SOC log triage, event aggregation, and network telemetry visualization.
- [ ] Develop automated Python IOC extractor / PCAP triage script
- [ ] Document research writeup on AI model supply chain attacks (Hugging Face / Pickle exploits)
