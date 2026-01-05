# Linux Log Analysis – Authentication Logs

## Objective
To analyze Linux authentication logs and identify suspicious login attempts.

## Log File
/var/log/auth.log

## Commands Used
grep "Failed password" /var/log/auth.log
grep "Accepted password" /var/log/auth.log

## Findings
- Multiple failed login attempts observed
- Repeated attempts from the same IP address
- Possible brute-force attack behavior

## Security Recommendation
- Enable strong password policies
- Implement account lockout
- Monitor logs regularly
