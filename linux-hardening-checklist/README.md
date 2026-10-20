# Linux hardening checklist (lite)

## English

### Purpose

Fifteen SSH checks from the forty-item list, in English and Chinese. The
firewall, sysctl, sudo, password, account, update, and permission checks,
plus the read-only `audit.sh`, are in the full pack.

### Deliverables

- `deliverables/checklist.en.md` — SSH checks, English
- `deliverables/checklist.zh.md` — the same SSH checks, Chinese

### Quick start

Read both tables. Each row is one requirement: permissions on `sshd_config`,
root login, empty passwords, idle timeout, and an allow list. Compare them
with the global section of your `sshd_config` (everything above the first
`Match`). The full pack scores the whole list and writes JSON.

### Requirements

A text editor. No packages are required to read the lite checklist.

## 中文

### 用途

四十项清单中的十五项 SSH 检查，中英各一份。防火墙、sysctl、sudo、口令、
账号、更新、权限，以及只读的 `audit.sh`，在完整版中。

### 交付清单

- `deliverables/checklist.en.md` — SSH 检查，英文
- `deliverables/checklist.zh.md` — 同样的 SSH 检查，中文

### 快速开始

两份表都读一遍。每一行是一条要求：`sshd_config` 的权限、root 登录、空口令、
空闲超时，以及允许列表。拿它们和 `sshd_config` 里第一个 `Match` 之前的全局段
对照。完整版会给整份清单打分并写出 JSON。

### 环境要求

一个文本编辑器。阅读精简清单不需要额外软件包。

Full version: GUMROAD_URL
