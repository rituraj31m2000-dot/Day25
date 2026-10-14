# Incident Response Checklist

Use this checklist as a starting point. Record completion, owner, and timestamp in your incident record. Follow your organization's approved plan.

## 1. Preparation
- [ ] Confirm incident response roles, escalation contacts, and communication channels.
- [ ] Know how to reach IT, security, management, legal/privacy, and relevant service providers.
- [ ] Maintain an inventory of critical assets, systems, data, and owners.
- [ ] Confirm logging, alerting, time synchronization, backups, and recovery procedures.
- [ ] Keep response tools and contact lists accessible and current.
- [ ] Define severity levels and decision authority for disruptive actions.

## 2. Detection and analysis
- [ ] Record reporter/source, discovery time, affected asset/user, and initial symptoms.
- [ ] Assign an incident ID and an incident lead.
- [ ] Validate whether the event is suspicious and distinguish false positive from confirmed incident.
- [ ] Preserve relevant logs, alerts, email headers, screenshots, and timestamps where permitted.
- [ ] Determine scope, likely entry point, affected accounts/systems/data, and business impact.
- [ ] Classify severity and notify the appropriate stakeholders.
- [ ] Maintain a factual timeline; label assumptions as unconfirmed.

## 3. Containment
- [ ] Select containment actions based on severity, business impact, and authority.
- [ ] Isolate affected endpoints or segments when appropriate and approved.
- [ ] Disable or restrict compromised accounts/sessions; revoke tokens where relevant.
- [ ] Block malicious indicators using approved controls when validated.
- [ ] Preserve evidence before actions that may alter it, when feasible and safe.
- [ ] Record every action, who approved it, and when it occurred.
- [ ] Reassess whether the incident is spreading.

## 4. Eradication
- [ ] Identify and address the root cause.
- [ ] Remove confirmed malware or unauthorized persistence using trusted tools.
- [ ] Patch exploited vulnerabilities and correct misconfigurations.
- [ ] Reset affected credentials and rotate exposed secrets/keys.
- [ ] Review related systems and accounts for signs of the same compromise.
- [ ] Verify that the threat and persistence mechanisms are removed.

## 5. Recovery
- [ ] Restore from known-good backups or clean images where necessary.
- [ ] Validate system integrity, security controls, and business functionality.
- [ ] Apply required patches and security configuration before reconnecting.
- [ ] Re-enable accounts/services only after authorization and validation.
- [ ] Monitor logs and alerts for recurrence or suspicious behavior.
- [ ] Confirm service owners accept the restored service and document the time.

## 6. Lessons learned and closure
- [ ] Complete the timeline, impact summary, root-cause analysis, and evidence inventory.
- [ ] Hold a post-incident review with relevant stakeholders.
- [ ] Record what worked, what failed, and what could be improved.
- [ ] Create corrective actions with owners and due dates.
- [ ] Update playbooks, detections, training, and recovery procedures.
- [ ] Confirm required notifications and record-retention steps with appropriate experts.
- [ ] Obtain closure approval and store records securely.

## Incident record quick fields
Incident ID | Date/time detected (with timezone) | Reporter | Incident lead | Severity | Affected assets/accounts | Summary | Evidence locations | Timeline | Containment actions | Root cause | Recovery validation | Notifications | Lessons learned | Action owner/due date | Closure approval

**Reminder:** Never put passwords, API keys, private personal data, or sensitive evidence in a public repository.
