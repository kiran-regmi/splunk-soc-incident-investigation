# SOC Incident Investigation Using Splunk (SOC-1)

## Purpose
This project demonstrates a SOC-1 level alert investigation using Splunk, focused on authentication-related suspicious activity (brute-force attempts). It includes alert triage, log analysis, correlation, severity assessment, escalation rationale, and incident documentation.

## Tools Used
- Splunk (SPL searches)
- Windows Authentication / Security Events (conceptual mapping)
- Network context (source IP correlation)

## Scenario
A detection is triggered due to repeated failed logins across multiple accounts from a single source IP, followed by a successful login attempt.

## Investigation Workflow
1. Alert validation (triage)
2. Evidence collection (pivoting in Splunk)
3. Timeline development
4. Severity assessment
5. Escalation decision
6. Incident report

## Contents
- `scenario/` - scenario overview
- `splunk-searches/` - SPL searches used during investigation
- `investigation/` - triage notes, timeline, findings, escalation decision
- `report/` - final incident report
- `screenshots/` - supporting screenshots from Splunk

## Outcome
Final determination and response actions are documented in `report/incident-report.md`.
