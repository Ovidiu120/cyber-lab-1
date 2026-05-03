# Findings Report - Brute Force Attack

## Summary
Multiple failed login attempts were detected targeting admin and root accounts. One successful login followed repeated attempts from the same IP.

## Indicators of Compromise (IOCs)
- IP: 192.168.1.10
- IP: 192.168.1.11
- Target users: admin, root

## Timeline
- 10:00: multiple failed login attempts (admin)
- 10:01: successful login (admin)
- 10:02: repeated failed attempts (root)

## Conclusion
Suspicious brute force activity detected. One account was successfully accessed after repeated attempts.

## Recommendations
- Enable account lockout policies
- Implement MFA
- Monitor repeated login failures

