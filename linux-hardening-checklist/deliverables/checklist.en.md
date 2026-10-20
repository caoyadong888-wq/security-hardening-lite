# Linux hardening checklist (lite)

Fifteen SSH checks from the full forty. Firewall, sysctl, sudo, password aging, accounts, updates, permissions, and `audit.sh` are in the full pack.

SSH numbers follow CIS Distribution Independent Linux section 5.2. Ubuntu 22.04 often uses a different sub-number for the same sentence.

| ID | CIS-style ref | Check |
| --- | --- | --- |
| SSH-PERM | 5.2.1 | Permissions on sshd_config are 0600 |
| SSH-LOGLEVEL | 5.2.5 | SSH LogLevel is INFO or VERBOSE |
| SSH-X11 | 5.2.6 | SSH X11 forwarding is disabled |
| SSH-MAXAUTH | 5.2.7 | SSH MaxAuthTries is 4 or less |
| SSH-RHOSTS | 5.2.8 | SSH IgnoreRhosts is enabled |
| SSH-HOSTBASED | 5.2.9 | SSH HostbasedAuthentication is disabled |
| SSH-ROOT | 5.2.10 | SSH root login is disabled |
| SSH-EMPTY | 5.2.11 | SSH PermitEmptyPasswords is disabled |
| SSH-ENV | 5.2.12 | SSH PermitUserEnvironment is disabled |
| SSH-ALIVE | 5.2.13 | SSH idle timeout is configured |
| SSH-GRACE | 5.2.14 | SSH LoginGraceTime is one minute or less |
| SSH-LIMIT | 5.2.15 | SSH access is limited to an allow list |
| SSH-PUBKEY | 5.2 | SSH public key authentication is enabled |
| SSH-PASSWD | 5.2 | SSH password authentication is disabled |
| SSH-MAXSESS | 5.2 | SSH MaxSessions is 10 or less |
