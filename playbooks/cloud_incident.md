# ☁️ Cloud Security Incident Response Playbook (AWS/Azure)

## Identification
- Suspicious IAM activity (policy changes, role assumptions)
- Unexpected EC2/Azure VM launches
- Unrecognized API calls or console logins
- Alerts from GuardDuty / Security Center / CloudTrail anomalies

## Containment
- Disable compromised API keys or credentials
- Revoke active sessions
- Isolate affected cloud assets (security groups, NSGs)
- Block malicious IPs

## Eradication
- Remove unauthorized resources (EC2, containers, storage buckets)
- Delete injected IAM policies or backdoor roles
- Patch vulnerable cloud workloads

## Recovery
- Restore resources from clean snapshots
- Re-enable workloads under enhanced monitoring
- Perform full audit of IAM permissions

## Lessons Learned
- Enforce MFA everywhere
- Implement least privilege IAM roles
- Enable CloudTrail/Defender/GuardDuty logging for all regions
- Automate detection with SIEM integration
