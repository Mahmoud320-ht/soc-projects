# SOC Detection Lab (Splunk)

Hands-on lab where I simulate real attacks and build Splunk detections that
trigger alerts, to learn how the Tier 1 SOC workflow works end to end.

## Projects

| Project | Focus | MITRE ATT&CK |
|---|---|---|
| [SSH Brute Force Detection](./ssh-bruteforce-detection-splunk) | Detecting repeated failed SSH logins with Splunk | T1110 (Brute Force) |
| [Reverse Shell Network Detection](./reverse-shell-network-detection) | Detecting reverse shell network activity | T1059 (Command and Scripting Interpreter) |
| [Custom Log IDS Script](./custom-log-ids-script) | Custom script that analyzes logs for suspicious events | - |
| [SOC Investigation Timeline](./soc-investigation-timeline) | Documenting an incident investigation timeline | - |

## Lab Environment
- SIEM: Splunk
- Attacker: <fill in, e.g. Kali Linux>
- Victim / log source: <fill in>

## Skills Demonstrated
Log analysis, alert creation, attack simulation, incident investigation,
MITRE ATT&CK mapping.

## Disclaimer
All attacks were performed against my own isolated lab for learning purposes only.
