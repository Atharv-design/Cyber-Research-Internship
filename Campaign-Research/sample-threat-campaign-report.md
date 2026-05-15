\# APT29 Phishing Campaign Analysis



\## Campaign Information



| Field | Details |

|---|---|

| Campaign ID | CAMP-001 |

| Threat Actor / APT Group | APT29 |

| Campaign Name | Banking Credential Theft Campaign |

| Campaign Activity Period | 2025-01-10 \~ 2025-02-02 UTC |

| Software | Microsoft Office |

| Target Country | India |

| Victim Country | India |

| Target Industry / Sector | Banking |

| Malware / Tool Used | AgentTesla |

| Threat Severity | High |

| Attribution Confidence | Medium |



\---



\## IOC Collection



| IOC Type | IOC Value |

|---|---|

| Domain | secure-login-microsoft365.com |

| IP Address | 185.244.25.12 |

| SHA256 Hash | a4d8f7f9b12c9abfxxxx |



\---



\## Infrastructure Information



| Field | Details |

|---|---|

| Domain / DNS | secure-login-microsoft365.com |

| Infrastructure Type | VPS Hosting |

| IP Geolocation | Russia |



\---



\## Attack Details



| Field | Details |

|---|---|

| Attack Vector | Phishing Email |

| Persistence Method | Registry Run Keys |

| Privilege Escalation | UAC Bypass |

| C2 Communication | HTTPS Beaconing |

| Data Exfiltration Method | ZIP Upload over HTTPS |



\---



\## MITRE ATT\&CK TTPs



| Technique | ATT\&CK ID |

|---|---|

| Phishing | T1566 |

| PowerShell Execution | T1059 |

| Credential Dumping | T1003 |



\---



\## Detection Sources



\- VirusTotal

\- Wireshark

\- Any.Run Sandbox

\- CrowdStrike Reports



\---



\## Analyst Notes



This phishing campaign targeted banking employees in India using malicious Office attachments. The malware attempted credential theft and established encrypted communication with a remote command-and-control server.

