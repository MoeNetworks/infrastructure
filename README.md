# MoeNet LLC — Infrastructure

| Field | Value |
|---|---|
| **Organization** | MoeNet LLC |
| **ASN** | AS214773 |
| **IPv6 Prefix** | `2a0f:1cc5:2100::/40` |
| **NOC Email** | <noc@moenetworks.net> |
| **Contact** | <noc@moenetworks.net> |
| **Website** | <https://moenetworks.net> |
| **PeeringDB** | [AS214773](https://www.peeringdb.com/asn/214773) |
| **Telegram** | [@heicha](https://t.me/heicha) |

## Network Overview

MoeNet is a global backbone network focused on building open, community-driven digital infrastructure.

### Current PoPs

| Node | City | Country | Provider | Status |
|---|---|---|---|---|
| hk1 | Hong Kong | HK | DMIT | ✅ Online |
| jp1 | Tokyo | JP | Oracle Cloud | ✅ Online |
| us1 | Los Angeles | US | RackNerd | ✅ Online |
| de1 | Frankfurt | DE | Hetzner | ✅ Online |
| sg1 | Singapore | SG | TBD | 🔜 Planned |

## Repository Structure

```
infrastructure/
├── README.md              # This file
├── geofeed.csv            # RFC 8805 geolocation feed
├── policies/
│   └── peering.md         # Peering policy
└── planning/
    └── ipv6-allocation.md  # IPv6 global allocation plan
```

## Resources

- [IPv6 Allocation Plan](planning/ipv6-allocation.md)
- [Peering Policy](policies/peering.md)
- [Geofeed](geofeed.csv) — RFC 8805 compliant, for RIR and search engine geolocation
