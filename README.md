# linux-auditd
Guidance for Auditd Implementation.

## Disclaimer

Please ensure proper testing is performed prior to production/large scale implemenation.

## Purpose

- Out of the box configuration and companion script that can be easily implemented on all major Linux distributions.
- Reasonable log generation.
- Human readable.

## Source Material

Rules within the configuration are based on the sources and repositories below.

Gov.uk auditd rules https://github.com/gds-operations/puppet-auditd/pull/1

CentOS 7 hardening https://highon.coffee/blog/security-harden-centos-7/#auditd---audit-daemon

Linux audit repo https://github.com/linux-audit/audit-userspace/tree/master/rules

Auditd high performance linux auditing https://linux-audit.com/tuning-auditd-high-performance-linux-auditing/

Neo23x0 best practice configuration https://github.com/Neo23x0/auditd/blob/master/audit.rules

bfuzzy auditd-attack https://github.com/bfuzzy/auditd-attack/blob/master/auditd-attack.rules


## Additional Information and Guidance

PCI DSS compliance see: https://github.com/linux-audit/audit-userspace/blob/master/rules/30-pci-dss-v31.rules

NISPOM compliance see: https://github.com/linux-audit/audit-userspace/blob/master/rules/30-nispom.rules

## Contributing
