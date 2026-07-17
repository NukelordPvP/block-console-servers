# Xbox & PlayStation Blocklists

A collection of DNS blocklists for Xbox and PlayStation consoles. These lists are intended to improve privacy, reduce telemetry and advertising, and optionally block firmware updates, licensing, and other online services.

These blocklists are compatible with DNS-based blockers such as **Pi-hole**, **AdGuard Home**, **Technitium DNS**, **NextDNS**, and other DNS filtering solutions.

---

# Blocklists

## Xbox

### microsoft-ad-servers.txt
Blocks Microsoft advertising and marketing domains used by Xbox.

### microsoft-telemetry-servers.txt
Blocks Microsoft telemetry, diagnostics, and analytics servers.

### more-xbox-servers.txt
Additional Xbox and Microsoft service domains that are not included in the other lists.

### reallybad-xboxlive-servers.txt
Blocks critical Xbox Live services, including firmware updates, licensing, authentication, and other online functionality.

> **Warning:** This list can significantly impact Xbox Live functionality and is intended for users who understand the consequences.

---

## PlayStation

### playstation-telemetry-servers.txt
Blocks PlayStation telemetry, diagnostics, analytics, and data collection endpoints.

### sony-servers.txt
Contains PlayStation service domains, including firmware update servers and other Sony online services.

> **Note:** It is generally recommended to block only the servers relevant to your console's region to avoid disrupting services such as the PlayStation Store, game downloads, or online authentication.

---

# Recommended Setup

For network-wide blocking, use a DNS filtering solution such as **Pi-hole**.

Pi-hole allows these blocklists to be applied to every device on your network without configuring each console individually.

Other compatible DNS blockers include:

- AdGuard Home
- Technitium DNS Server
- NextDNS
- Control D
- dnsmasq-based DNS servers

---

# Disclaimer

Blocking Microsoft or Sony domains may disable or interfere with:

- Firmware and system updates
- Game updates
- Xbox Live or PlayStation Network services
- Licensing verification
- Cloud saves
- Digital purchases
- Online multiplayer
- Console activation
- Store functionality

Use these blocklists at your own risk.
