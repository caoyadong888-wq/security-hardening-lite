# Ansible ops playbooks (lite)

## English

### Purpose

A free slice: operator accounts and the SSH drop-in, which have to ship together. Base packages, ufw, unattended upgrades, and node_exporter are in the full pack.

### Deliverables

- `deliverables/site.yml`
- `deliverables/ansible.cfg`
- `deliverables/inventory/hosts.yml`
- `deliverables/group_vars/all.yml`
- `deliverables/roles/users`
- `deliverables/roles/ssh_hardening`

### Quick start

```bash
cd deliverables
ansible-playbook site.yml --syntax-check
```

Replace the sample keys before a real run. `AllowGroups ops` will lock out any account that is not in `ops_users`.

### Requirements

Ansible Core 2.16 or newer. Debian 12 or Ubuntu 22.04/24.04 on the servers.

## 中文

### 用途

免费子集：运维账号和 SSH 加固，这两份必须一起用。基础软件包、ufw、无人值守升级和 node_exporter 在完整版里。

### 交付清单

- `deliverables/site.yml`
- `deliverables/ansible.cfg`
- `deliverables/inventory/hosts.yml`
- `deliverables/group_vars/all.yml`
- `deliverables/roles/users`
- `deliverables/roles/ssh_hardening`

### 快速开始

```bash
cd deliverables
ansible-playbook site.yml --syntax-check
```

真正执行前换掉示例公钥。`AllowGroups ops` 会把不在 `ops_users` 里的账号关在外面。

### 环境要求

Ansible Core 2.16 或更高。服务器是 Debian 12 或 Ubuntu 22.04/24.04。

Full version / 完整版: GUMROAD_URL

## Delivery time / 交付时间

- Lite (this folder): free, available now. / 精简版（本目录）：免费，立即可用。
- Full version: instant download after purchase (GUMROAD_URL). / 完整版：购买后即时下载（GUMROAD_URL）。
