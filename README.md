# Snort Intrusion Detection Project

A controlled Snort IDS lab using custom rules to detect TCP traffic targeting FTP (21), SSH (22), and HTTP (80).

## Objectives
- Configure Snort
- Create custom local rules
- Validate the configuration
- Monitor authorized lab traffic
- Review IDS alerts

## Custom Rules
See `rules/local.rules`.

Expected alerts:
- FTP Packet found
- SSH Packet found
- HTTP Packet found

## Validation
```bash
sudo snort -T -c /etc/snort/snort.conf
```

## Monitoring
```bash
sudo snort -c /etc/snort/snort.conf -i <INTERFACE>
```

Replace `<INTERFACE>` with the authorized lab interface.

## Safety
Use only on systems and networks you own or are authorized to test.
