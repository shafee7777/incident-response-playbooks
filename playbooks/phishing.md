# 📧 Phishing Incident Response Playbook

## Phase 1 — Preparation
- Ensure email filtering rules are in place
- Verify SPF, DKIM, DMARC configured
- User awareness training active

## Phase 2 — Identification
- Validate phishing indicators (sender spoofing, URLs, attachments)
- Pull email headers and analyze
- Check if multiple users received same email

## Phase 3 — Containment
- Quarantine email from all inboxes
- Block sender/domain
- Disable affected user accounts if any credentials were compromised

## Phase 4 — Eradication
- Remove malicious artifacts from endpoints
- Reset user passwords
- Patch vulnerable software

## Phase 5 — Recovery
- Re-enable accounts
- Confirm email filtering rules functioning
- Validate MFA is enforced

## Phase 6 — Lessons Learned
- Update playbook
- Improve user training modules
- Enhance detection rules
