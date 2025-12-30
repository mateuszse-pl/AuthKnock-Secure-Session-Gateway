![AuthKnock Logo](./logo.png)
# AuthKnock License

Copyright (c) 2025 Mateusz Serafiński

## 1. Community Edition (CE)

The Community Edition (CE) of AuthKnock is **free to use, modify, and distribute**. You are allowed to:

- Use the software for personal or commercial purposes.
- Modify the source code.
- Redistribute modified or unmodified versions, as long as this copyright notice and license are preserved.

CE releases are clearly tagged in this repository as `CE`. CE may include configuration files or examples similar to the Full version, but **installation and usage of Full features require a valid license key**.

CE is provided **“AS IS”**, without any warranty of any kind. The author is not responsible for any damages resulting from its use.

## 2. Full / Paid Edition

The Full (Paid) Edition of AuthKnock provides additional or identical functionality to CE but requires a **license key** for installation and use. 

- The Full edition may be **partially or fully closed source**. 
- Redistribution of the Full edition without authorization is prohibited.
- Using CE configuration files may be permitted, but **activation of Full features requires a valid license**.

## 3. License Agreement

By using any release from this repository, you agree to comply with the terms above.

## Editions Comparison

| Feature / Functionality | Community Edition (CE) | Full (Subscription) |
|-------------------------|:----------------------:|:-------------------:|
| Core system | ✅ Included | ✅ Included |
| Installation method | Shell script (`.sh`), user isolation | Web-based installer (GUI), optional Docker image |
| Authorization methods |  AD DS, MySQL, Local system, YAML file | AD DS, MySQL, Local system (YAML removed due the security reasons) |
| Two-Factor Authentication (2FA/MFA) | ✅ Included | ✅ Included |
| Service management | Basic Web UI | Advanced Web UI |
| Themes / UI skins | Single default theme | Multiple themes |
| Configuration management | Manual YAML file editing | Full configuration editor in Web UI |
| Configuration reload | Manual reload via script | Automatic reload (no restart required) |
| Auto-discovery of services | ❌ Not available | ✅ Available |
| Notifications | Email, Telegram | Email, Telegram + built-in SMTP server |
| Audit logs & change history | ❌ Limited / none | ✅ Full audit logs |
| Backup & restore | Scripts | Available via Web UI |
| User and role management | Basic | Advanced (GUI-based) |
| Active Directory (AD DS) automatic scripts | ❌ Not available | ✅ Automatic group creation and sync |
| MySQL automatic scripts | ❌ Not available | ✅ Automatic database and role creation |
| Deployment options | Manual installation | Docker image + Web installer |
| Automatic updates | ❌ Not available | ✅ Automatic minor updates |
| Monthly feature updates | ❌ Not available | ✅ Regular small updates (monthly) |
| Support | Community support only | SLA-based support (≤48h response) |
| License type | Free & Open Source | Paid annual subscription |

---

## Subscription Model (Full Edition)

The **Full** edition is distributed under a commercial subscription model.

- Pricing: **299 PLN / year**
- Includes:
  - All Full features
  - Automatic minor updates
  - Monthly small feature and improvement releases
  - SLA-based support (email / ticket system)
- A valid license key is required during installation or activation.

A free trial period (7–14 days) may be available.

---

## Notes

- The **Community Edition (CE)** is free to use, modify, and redistribute under the terms
  of the open-source license defined in this repository.
- The **Full Edition** requires a valid subscription and license key.
- Configuration formats between CE and Full are intentionally kept compatible.