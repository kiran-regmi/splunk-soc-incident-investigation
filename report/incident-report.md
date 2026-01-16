# Incident Report – Brute Force Authentication Attempt

## Executive Summary
A brute-force authentication attack was detected and investigated following a Splunk alert. The activity resulted in a successful login to at least one account, indicating potential credential compromise.

## Detection
The incident was detected via a Splunk alert based on excessive failed authentication attempts within a defined time window.

## Analysis
Investigation revealed multiple failed login attempts from a single external IP targeting several user accounts. A successful authentication event followed the failed attempts and originated from the same IP.

## Impact
- Potential account compromise
- Risk of unauthorized system access

## Response
- Alert validated and escalated
- Affected account(s) identified
- Incident escalated to Tier 2 for containment

## Recommendations
- Enforce MFA for all user accounts
- Implement stricter authentication rate limiting
- Monitor for similar attack patterns

