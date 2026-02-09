# IT Help Desk for Beginners
**Instructor:** Robert McMillen (LinkedIn Learning)

This document contains key takeaways and troubleshooting workflows from the IT Help Desk for Beginners course. These notes serve as a quick reference for incident management and hardware/software troubleshooting.

---

## 📝 Key Learnings & Concepts

### 1. Incident Management
* **Incident Tracking Tools:** Used to log, track, update, and close IT issues.
* **Spiceworks:** A concept similar to GitHub but specifically for tracking and managing IT issues.
* **SLA (Service Level Agreement):** Defines the required response and resolution times.
* **Priority Levels:** Issues are categorized as Low, Medium, High, or Critical.
* **Escalation:** Redirecting unresolved or reclassified issues to the specialized team.

### 2. The Support Process
* **Documentation (Critical):** Document every issue and resolution to build a Knowledge Base.
* **Critical Thinking:** Always consider multiple ways to resolve an issue.
* **Verify, Don't Assume:** Follow step-by-step verification.

---

## 🛡️ Security & Malware

### 🎣 Phishing Awareness
Phishing occurs when users are tricked into clicking malicious links or sharing passwords.
* **Common Sources:** Fake emails, gaming websites, and unauthorized USB drives.

### 🦠 Signs of Malware Infection
* **System Performance:** Computer slows down, crashes, or won't shut down/restart.
* **Browser Issues:** Default search engine or homepage changes; excessive pop-ups.
* **Software:** Unable to remove programs; repeated error messages.
* **Other:** Emails sent without user knowledge; rapid battery drain.
* **Initial Check Tool:** **Task Manager** (Look for unknown processes or unusually high resource usage).

---

## 🧑‍💻 Common Help Desk Workflows

### 🔐 Access & Troubleshooting
- [ ] **Can't Log In:** Check Caps Lock, expired passwords, or locked accounts. 
- [ ] **Shared Drive Access:** Ping the server, remap the network drive, and check permissions.
- [ ] **Internet Connectivity:** Determine if it's one user or everyone. Check IP/DNS settings.
- [ ] **Slow Performance:** Check Task Manager, remove temp files, and check disk space.

### 🖥️ Hardware & Peripherals
- [ ] **Printing Issues:** Check power, paper jams, and toner. Reinstall drivers if needed.
- [ ] **Wireless Peripherals:** Check Bluetooth connectivity and replace batteries.
- [ ] **Blue Screen (BSOD):** Identify the crash code, check for driver issues, and reboot.
- [ ] **Power Issues:** Check connections, try a reset, or escalate for hardware repair.

---

## 🖥️ Troubleshooting Tools (Windows)

| Tool | Usage |
| :--- | :--- |
| **Event Viewer** | Filter 'System' logs to find hardware/software events. |
| **Device Manager** | Enable/disable devices and update drivers. |
| **Disk Management** | Manage storage, partitions, and disk health. |
| **Task Manager** | Monitor real-time CPU, Memory, Disk, and Network usage. |
| **Resource Monitor** | Detailed breakdown of system resource allocation. |

---

## 🌐 Networking Basics (Command Line)
* `ipconfig` / `ipconfig /all`: Check local IP configuration.
* `ping [address]`: Test connectivity to a server or website.
* `tracert [address]`: Identify the network path and find where a connection fails.

---

## 🧠 Key Takeaway
> "Strong IT support is about process, documentation, calm troubleshooting, and critical thinking — not just tools."
