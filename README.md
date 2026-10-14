# Day 25 — Basic Incident Response

**Cybersecurity Internship Project | Level 1**

## Overview
This project explains a practical, repeatable incident response workflow and provides a checklist for handling suspected cybersecurity incidents. It is an educational template, not a substitute for an organization's approved procedures or legal/regulatory advice.

## Objectives
- Explain incident response and why it matters.
- Organize actions into preparation, detection and analysis, containment, eradication, recovery, and lessons learned.
- Provide a reusable checklist and incident record template.
- Encourage evidence preservation, clear communication, and authorized action.

## Incident response workflow
1. **Preparation:** Define roles, contacts, escalation paths, asset inventory, backups, logging, and response tools.
2. **Detection and analysis:** Validate the alert, record time and source, determine scope/severity, preserve relevant logs, and open an incident record.
3. **Containment:** Limit spread and impact using approved actions (for example, isolating an affected endpoint). Coordinate with system owners; avoid destroying evidence.
4. **Eradication:** Remove the root cause, such as malware, compromised accounts, persistence mechanisms, or exploited vulnerabilities.
5. **Recovery:** Restore from trusted backups or clean images, patch systems, rotate affected credentials, and monitor for recurrence.
6. **Lessons learned:** Document the timeline, impact, root cause, decisions, gaps, and measurable follow-up actions.

> Note: NIST SP 800-61 Rev. 3 (2025) frames incident response within broader cybersecurity risk management and emphasizes Detect, Respond, Recover, with preparation and continuous improvement supporting the lifecycle. This project uses the familiar six-stage teaching sequence to make the task easy to follow.

## Repository contents
- `README.md` — project overview and workflow
- `incident_response_checklist.md` — actionable checklist
- `incident_log_template.csv` — starter incident record
- `project_report.pdf` — formatted project report
- `project_report.docx` — editable report

## Example scenario (fictional)
A staff member reports a suspicious email attachment. The analyst records the report, checks email/security logs, identifies recipients, asks the user not to open the attachment, and follows approved procedures to quarantine the message and isolate any confirmed affected endpoint. Evidence is preserved; credentials are reset if compromise is confirmed. The system is restored only after remediation and validation. The team documents lessons learned.

## How to use
1. Read the report and checklist.
2. Copy the checklist into your team's approved workspace.
3. Fill in the incident log with verified facts only.
4. Follow organizational escalation and evidence-handling policies.
5. Review and customize the template with a supervisor before operational use.

## Safety and scope
- Work only on systems and accounts you are authorized to administer.
- Do not run malware or perform intrusive tests as part of this documentation task.
- Do not publish personal data, secrets, access tokens, or real incident evidence in a public repository.
- Treat the example scenario as fictional.

## Reference
National Institute of Standards and Technology (NIST), *SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management* (April 2025): https://csrc.nist.gov/pubs/sp/800/61/r3/final
