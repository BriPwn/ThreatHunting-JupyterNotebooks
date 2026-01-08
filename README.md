# 🟣 Weekly Purple Team - Threat Hunting Notebooks

[![YouTube Channel](https://img.shields.io/badge/YouTube-Weekly%20Purple%20Team-red?style=for-the-badge&logo=youtube)](https://youtube.com/@WeeklyPurpleTeam)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter)](https://jupyter.org/)

A collection of threat hunting and detection engineering Jupyter notebooks accompanying the [Weekly Purple Team](https://youtube.com/@WeeklyPurpleTeam) YouTube channel. Each notebook provides hands-on labs and detection logic to help security professionals understand both offensive techniques and defensive strategies.

---

## 🎯 About This Repository

These notebooks bridge the gap between red team tactics and blue team defenses. By understanding how attacks work, we build better detections.

Each notebook is designed to:
- **Demonstrate** real-world attack techniques
- **Analyze** telemetry and log data
- **Develop** detection logic and hunting queries
- **Validate** defensive controls

## 📺 YouTube Channel

Subscribe to [Weekly Purple Team](https://youtube.com/@WeeklyPurpleTeam) for video walkthroughs of these notebooks and more cybersecurity content covering:

- 🔴 **Red Team** - Offensive techniques and tooling
- 🔵 **Blue Team** - Detection engineering and threat hunting
- 🟣 **Purple Team** - Bridging offense and defense

---

## 📂 Repository Structure

```
├── notebooks/
│   ├── credential-access/      # Kerberoasting, hash dumping, etc.
│   ├── defense-evasion/        # EDR bypass, log tampering, etc.
│   ├── initial-access/         # Phishing, exploitation, etc.
│   ├── lateral-movement/       # Pass-the-hash, RDP, etc.
│   ├── persistence/            # Scheduled tasks, registry, etc.
│   └── command-and-control/    # C2 traffic analysis, beacons, etc.
```

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or JupyterLab
- Required Python packages (see `requirements.txt`)

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/weekly-purple-team-notebooks.git
cd weekly-purple-team-notebooks

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter lab
```

## 📓 Featured Notebooks

| Notebook | MITRE ATT&CK | Video Link |
|----------|--------------|------------|
| Kerberoasting Detection | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | [Watch](https://youtube.com/@WeeklyPurpleTeam)

## 🛠️ SIEM Platform Coverage

Detection queries will start with Elastic other platforms can be provided:

| Platform | Directory | Status |
|----------|-----------|--------|
| Elastic 9.2 | `queries/kql/` | ✅ Active |
| Sigma (Universal) | `queries/sigma/` | ✅ Active |
| Cortex XSIAM | `queries/xql/` | ❌ In Process|
| CrowdStrike NG-SIEM | `queries/crowdstrike/` | ❌ In Process |

## 🤝 Contributing

Contributions are welcome! Whether it's new notebooks, detection queries, or bug fixes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-detection`)
3. Commit your changes (`git commit -m 'Add Kerberoasting detection for Splunk'`)
4. Push to the branch (`git push origin feature/new-detection`)
5. Open a Pull Request

## ⚠️ Disclaimer

These materials are provided for **educational and authorized security testing purposes only**. The techniques demonstrated should only be used in environments where you have explicit permission. Misuse of these tools and techniques may violate laws and regulations.

Always obtain proper authorization before conducting security assessments.

## 📬 Connect

- **YouTube**: [@WeeklyPurpleTeam](https://youtube.com/@WeeklyPurpleTeam)
- **LinkedIn**: [Connect with me](https://linkedin.com)
- **Twitter/X**: [Follow for updates](https://twitter.com)

---

<p align="center">
  <b>Learn to attack. Learn to defend. Stay purple.</b> 🟣
</p>
# ThreatHunting-JupyterNotebooks
