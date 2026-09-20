# Snort IDS Findings

| Service | TCP Port | SID | Alert |
|---|---:|---:|---|
| FTP | 21 | 10000002 | FTP Packet found |
| SSH | 22 | 10000003 | SSH Packet found |
| HTTP | 80 | 10000004 | HTTP Packet found |

These are basic port-based detection rules. A matching alert indicates matching traffic, not necessarily malicious activity.

## Conclusion
The lab demonstrates the Snort workflow of custom-rule configuration, validation, authorized traffic monitoring, and alert review.
