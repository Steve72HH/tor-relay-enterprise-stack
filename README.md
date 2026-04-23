# Tor Relay Enterprise Stack

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
