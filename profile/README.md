<div align="center">

# Hosted Power

**Your business runs on apps. We keep them running.**

Managed European cloud for Magento, Shopware, Odoo and SaaS, built on our own platform, [TurboStack](https://www.hosted-power.com/en/platform/turbostack-features).

[Website](https://www.hosted-power.com) · [TurboStack docs](https://docs.turbostack.app) · [LinkedIn](https://www.linkedin.com/company/hosted-power/) · [hello@hosted-power.com](mailto:hello@hosted-power.com)

</div>

---

### 🛡️ nginx2root: fully patched NGINX where the distribution has none

When five critical NGINX vulnerabilities (nginx2root, CVE-2026-123007 and related) were disclosed on 18 November 2026, our managed servers ran a patched NGINX **the same day**. Then we published the fixes as the distributions' own NGINX packages, for every release still waiting for an official update or out of support.

**[nginx2root-patches](https://github.com/HOSTED-POWER/nginx2root-patches)** covers:

- Debian 8 to 13, CentOS 7 (EPEL) and CentOS 8 (AppStream 1.14 to 1.20)
- RHEL 9, Rocky Linux 9 and Oracle Linux 9 (base 1.20 and AppStream 1.22, 1.24, 1.26), AlmaLinux 9's retired 1.22 stream, and Oracle Linux 10
- 12 CVEs fixed, every one named in the package changelog; HTTP/2 stays on
- Same package names, modules and configuration, and the official update takes over automatically
- Covered by Dutch IT Leaders and Born's Tech and Windows World (DE), referenced on Defensia's CVE pages

> Switching HTTP/2 off is not a fix: it blocks only 2 of the 5 nginx2root vulnerabilities.

---

### 🛡️ php2shell: ready before PHP was

When two critical PHP vulnerabilities leaked in October 2026, we built and shipped protection **hours before PHP's official fix**, rolled it out across our platform without downtime, and open-sourced it.

**[php_uploadprogress_guard](https://github.com/HOSTED-POWER/php_uploadprogress_guard)** applies the official fix to an unpatched PHP without rebuilding it, from PHP 5.4 to 8.5, on Linux (x86_64 and ARM) and Windows. Since v3.2 it also covers two problems PHP itself has not shipped fixes for yet, on patched PHP too.

- Used by administrators from China to Russia, and packaged by other hosting providers for their own customers
- Referenced by independent CVE databases for end-of-life PHP versions
- Covered by Cybernews, Dutch IT Channel, IT-Connect (FR) and Born's Tech and Windows World (DE)

> Update PHP first. The extension is a bridge for the servers that can't, yet.

---

### ⚙️ What we build

| | |
|---|---|
| **TurboStack** | Our platform to deploy and manage applications: clusters with automatic failover, dedicated database servers, staging, one YAML or one click |
| **TurboShield** | Web application firewall and bot protection, tuned per shop |
| **TurboRadar** | Intrusion detection and the Threat Center: vulnerabilities and indicators of compromise per server, also via API |
| **TurboKernel & TurboRAM** | Our own high-performance kernel and compressed memory: more out of the same hardware |

### 🧰 Open source

We run hundreds of servers, and we share what helps others run theirs:

- **[nginx2root-patches](https://github.com/HOSTED-POWER/nginx2root-patches)**: fully patched distribution NGINX for Debian, CentOS and Enterprise Linux
- **[php_uploadprogress_guard](https://github.com/HOSTED-POWER/php_uploadprogress_guard)**: php2shell protection for unpatched PHP
- **[monitoring-plugins-crm](https://github.com/HOSTED-POWER/monitoring-plugins-crm)**: Nagios-compatible Pacemaker cluster check
- **[check_es_system](https://github.com/HOSTED-POWER/check_es_system)**: Elasticsearch node health and resources
- **[check_mysql_health](https://github.com/HOSTED-POWER/check_mysql_health)** and **[varnish-nagios](https://github.com/HOSTED-POWER/varnish-nagios)**: the database and cache checks behind our monitoring

---

<div align="center">

**Running PHP or NGINX your distribution hasn't patched yet? Need a platform that reacts before the patch does?**
[Talk to us](https://www.hosted-power.com) · Belgium 🇧🇪 · Netherlands 🇳🇱 · France 🇫🇷

</div>
