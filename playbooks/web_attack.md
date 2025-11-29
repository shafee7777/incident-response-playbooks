# 🌐 Web Application Attack (XSS / SQL Injection) Playbook

## Identification
- WAF alerts (XSS, SQLi payloads)
- Server logs showing unusual queries
- Sudden spike in application errors
- User reports of redirected pages or data exposure

## Containment
- Block malicious IPs at WAF/firewall
- Put application in maintenance mode if required
- Disable vulnerable parameters or endpoints
- Capture logs for attack analysis

## Eradication
- Patch vulnerable code or libraries
- Apply input validation and sanitization
- Enable prepared statements / parameterized queries
- Remove injected scripts or malicious files

## Recovery
- Restart application servers
- Perform vulnerability scans
- Validate no further exploitation occurs

## Lessons Learned
- Implement a secure SDLC process
- Strengthen WAF rules and rate limiting
- Conduct regular pentesting
