# SOC Investigation Portfolio

A beginner portfolio documenting simulated SOC alert-triage exercises, evidence, threat-intelligence enrichment and escalation decisions.

## Investigation 001: Suspicious SSH activity from a malware-associated IP

In a TryHackMe junior SOC analyst simulation, I reviewed two critical alerts involving the same IP address, checked the address in IP Hunter, and escalated the suspicious activity to the supervisor in the scenario.

**Key observation:** The SIEM dashboard showed unauthorised login attempts to SSH/port 22 at 15:42, followed by a successful SSH login from the same IP at 15:46 on 23 October 2026. IP Hunter's lab result labelled the address malicious and associated it with four cyber attacks. The alert was escalated in the simulated scenario.

- [Read the full investigation report](investigations/001-malware-associated-ip-triage.md)
- [View the SIEM alert dashboard screenshot](evidence/01-siem-alert-dashboard.png)
- [View the IP Hunter result screenshot](evidence/02-ip-hunter-reputation.png)

## Skills demonstrated

- Initial SOC Level 1 alert triage
- Identifying a suspicious IP address in alerts
- Threat-intelligence enrichment using an IP reputation tool
- Recognising a potentially suspicious authentication sequence
- Escalation and clear incident documentation
- Distinguishing observed evidence from assumptions

## Scope and accuracy

This is a write-up of a simulated training scenario, not professional SOC employment or a confirmed real-world incident. IP Hunter's reputation result is supporting context; it does not by itself prove that the SSH login compromised a system. The report distinguishes what was shown in the lab from recommended follow-up actions that were not confirmed as completed.

## Suggested public repository name

`soc-investigation-portfolio`

Before publishing, make sure you are permitted to share the training screenshots. Do not upload real employer/client logs, credentials, tokens, personal data or other sensitive information.
