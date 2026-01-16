# Scenario Overview: Brute Force Authentication Attempt

## Detection Summary
A SOC alert triggered due to a spike in failed authentication attempts across multiple user accounts from a single external source IP, followed by a successful login.

## Hypothesis
Potential credential stuffing / brute-force activity leading to account compromise.

## Primary Questions to Answer
1. Which accounts were targeted and how many failures occurred?
2. What source IP(s) generated the attempts?
3. Was there a successful login after the failures?
4. Did the successful login come from the same IP or a different one?
5. Is there evidence of post-login activity (new processes, lateral movement, privilege escalation)?
6. What is the recommended response (containment/escalation)?
