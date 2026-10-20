# Linux 加固检查清单（精简）

完整四十项中的十五项 SSH 检查。防火墙、sysctl、sudo、口令期限、账号、更新、权限以及 `audit.sh` 在完整版中。

SSH 编号遵循 CIS 发行版无关基准的 5.2 节。Ubuntu 22.04 对同一句话经常使用不同的小节号。

| ID | CIS 风格引用 | 检查项 |
| --- | --- | --- |
| SSH-PERM | 5.2.1 | sshd_config 的权限为 0600 |
| SSH-LOGLEVEL | 5.2.5 | SSH LogLevel 为 INFO 或 VERBOSE |
| SSH-X11 | 5.2.6 | 已关闭 SSH 的 X11 转发 |
| SSH-MAXAUTH | 5.2.7 | SSH MaxAuthTries 不大于 4 |
| SSH-RHOSTS | 5.2.8 | 已启用 SSH IgnoreRhosts |
| SSH-HOSTBASED | 5.2.9 | 已关闭 SSH HostbasedAuthentication |
| SSH-ROOT | 5.2.10 | 已禁止 SSH 的 root 登录 |
| SSH-EMPTY | 5.2.11 | 已关闭 SSH PermitEmptyPasswords |
| SSH-ENV | 5.2.12 | 已关闭 SSH PermitUserEnvironment |
| SSH-ALIVE | 5.2.13 | 已配置 SSH 空闲超时 |
| SSH-GRACE | 5.2.14 | SSH LoginGraceTime 不超过一分钟 |
| SSH-LIMIT | 5.2.15 | SSH 使用允许列表限制登录 |
| SSH-PUBKEY | 5.2 | 已启用 SSH 公钥认证 |
| SSH-PASSWD | 5.2 | 已关闭 SSH 口令认证 |
| SSH-MAXSESS | 5.2 | SSH MaxSessions 不大于 10 |
