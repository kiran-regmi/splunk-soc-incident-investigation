# Alert Triage

## Alert Trigger
Splunk alert triggered due to an abnormal volume of failed authentication attempts within a short time window.

## Initial Assessment
- Activity exceeds normal authentication behavior
- Multiple user accounts targeted
- Pattern consistent with brute-force or credential stuffing

## Triage Actions
- Reviewed Windows authentication failure events (EventCode 4625)
- Identified affected users
- Identified source IP responsible for activity

## Triage Decision
Alert considered **valid** and escalated for full investigation due to potential account compromise risk.

