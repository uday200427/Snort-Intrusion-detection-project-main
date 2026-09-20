# Snort Configuration Notes

Custom rules are stored at `/etc/snort/rules/local.rules` and should be included by the Snort configuration.

Validate before monitoring:
```bash
sudo snort -T -c /etc/snort/snort.conf
```

Monitor an authorized lab interface:
```bash
sudo snort -c /etc/snort/snort.conf -i <INTERFACE>
```

The exact configuration path and command-line options can vary by Snort version/package.
