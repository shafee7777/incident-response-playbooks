# ✅ Incident Triage Checklist

## 1. Verify Alert
- [ ] Confirm alert source (SIEM/EDR/WAF)
- [ ] Validate alert isn’t a false positive

## 2. Identify Scope
- [ ] What systems are affected?
- [ ] Which users/accounts involved?
- [ ] Signs of lateral movement?
- [ ] Data exposure?

## 3. Containment Steps
- [ ] Isolate endpoint/server
- [ ] Disable compromised credentials
- [ ] Block malicious IP/domains

## 4. Evidence Collection
- [ ] Export logs (SIEM, endpoint, network)
- [ ] Capture memory dump (if required)
- [ ] Collect file samples, event data

## 5. Notifications
- [ ] Notify SOC / IR team
- [ ] Notify management (if major incident)
- [ ] Notify legal/compliance (if required)

## 6. Next Steps
- [ ] Move to eradication
- [ ] Begin forensic analysis
- [ ] Start documentation
