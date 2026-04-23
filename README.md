# Tor Relay Enterprise Stack

![Ansible](https://img.shields.io/badge/automation-Ansible-red)
![Security](https://img.shields.io/badge/security-UFW%20%7C%20Fail2ban%20%7C%20CrowdSec-blue)
![Monitoring](https://img.shields.io/badge/monitoring-Prometheus%20%7C%20Grafana-orange)
![License](https://img.shields.io/github/license/Steve72HH/tor-relay-enterprise-stack)
![Last Commit](https://img.shields.io/github/last-commit/Steve72HH/tor-relay-enterprise-stack)
![Issues](https://img.shields.io/github/issues/Steve72HH/tor-relay-enterprise-stack)

Dieses Repository enthält eine produktionsreife Infrastruktur zum Betrieb von Tor-Relays mit Fokus auf:

- Sicherheit (UFW, Fail2ban, CrowdSec)
- Monitoring (Prometheus + Grafana)
- Alerting (Alertmanager + Telegram)
- Automatisierung (Ansible)

---

## 🔧 Features

- Vollautomatisches Setup von Tor-Relays
- Enterprise Security Stack
- CrowdSec Integration (kollektive Bedrohungserkennung)
- Echtzeit Monitoring
- Alerting via Telegram

---

## 🚀 Deployment

```bash
ansible-playbook playbooks/site.yml
