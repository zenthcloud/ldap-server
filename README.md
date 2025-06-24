# Zenth LDAP Server

**Zenth LDAP Server** is an open-source, sovereign identity and directory service developed as part of the Zenth Cloud ecosystem by Sky Genesis Enterprise. It provides centralized authentication and user management across all Zenth services using the Lightweight Directory Access Protocol (LDAP).

## 👤 Features

- ✅ Fully compatible with LDAPv3 and Active Directory schemas
- ✅ Centralized identity store for users, groups, and roles
- ✅ Secure authentication via TLS and hashed credentials
- ✅ Integration-ready with all Zenth Cloud services (mail, SIP, panel, API)
- ✅ User provisioning and group policy support
- ✅ RESTful provisioning via `api-server`
- ✅ Replication-ready for HA/clustered deployments

## 📦 Part of the Zenth Cloud Stack

Zenth LDAP Server acts as the backbone for identity management across the Zenth ecosystem:

- `mail-server` – Mailbox authentication and address book
- `sip-server` – VoIP user registration and call permissions
- `panel-server` – Central UI for user and group administration
- `api-server` – Syncs and manages user provisioning via unified API
- `vpn-server`, `firewall-server` – Access control and network policy enforcement

## 🛠️ Technology

- Based on **OpenLDAP**, hardened and extended
- Custom schemas for Zenth Cloud integration
- LDAP over SSL/TLS (LDAPS)
- Container-ready (Proxmox, Docker, K8s)
- Support for external directory sync (optional)

## 📖 Documentation

Full usage instructions, schema extensions, and integration examples are available in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

This project is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See `LICENSE` for details.

---

For contributions, issues, or improvements, join the open-source effort at [github.com/zenthcloud](https://github.com/zenthcloud).
