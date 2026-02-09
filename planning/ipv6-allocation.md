# IPv6 Address Allocation Plan

> Prefix: `2a0f:1cc5:2100::/40`
> Range: `2a0f:1cc5:2100::` ~ `2a0f:1cc5:21ff::`
> Total: 256 × /48

## Hierarchy

```
/40 (Global)
 └── /44 (Continent / Function, 16 × /48 each)
      └── /48 (Country / Service)
```

---

## Continental Allocation

| # | Prefix | Assignment | /48 |
|---|---|---|---|
| 0 | `2a0f:1cc5:2100::/44` | 🔧 Infrastructure | 16 |
| 1 | `2a0f:1cc5:2110::/44` | 🌏 Asia | 16 |
| 2 | `2a0f:1cc5:2120::/44` | 🌍 Europe (incl. Turkey) | 16 |
| 3 | `2a0f:1cc5:2130::/44` | 🌎 North America | 16 |
| 4 | `2a0f:1cc5:2140::/44` | 🌎 South America | 16 |
| 5 | `2a0f:1cc5:2150::/44` | 🌍 Africa | 16 |
| 6 | `2a0f:1cc5:2160::/44` | 🌏 Oceania + Antarctica | 16 |
| 7-14 | `2170` ~ `21e0` | 📦 Reserved (8 × /44) | 128 |
| 15 | `2a0f:1cc5:21f0::/44` | 🧪 Lab / Testing | 16 |

---

## Infrastructure (`2a0f:1cc5:2100::/44`)

| Prefix | Purpose |
|---|---|
| `2a0f:1cc5:2100::/48` | Node Loopback |
| `2a0f:1cc5:2101::/48` | Inter-node P2P Links |
| `2a0f:1cc5:2102::/48` | **Anycast DNS** (e.g. `2a0f:1cc5:2102::53`) |
| `2a0f:1cc5:2103::/48` | Anycast Services (Web, API) |
| `2a0f:1cc5:2104::/48` | Monitoring / Management |
| `2a0f:1cc5:2105::/48` | VPN / Tunnel Overlay |
| `2a0f:1cc5:2106::/48` | Transfer Net (IX Peering) |
| `2107` ~ `210f` | Reserved |

---

## Asia (`2a0f:1cc5:2110::/44`)

| Prefix | Country |
|---|---|
| `2a0f:1cc5:2110::/48` | 🇨🇳 China (CN) |
| `2a0f:1cc5:2111::/48` | 🇭🇰 Hong Kong (HK) |
| `2a0f:1cc5:2112::/48` | 🇲🇴 Macau (MO) |
| `2a0f:1cc5:2113::/48` | 🇯🇵 Japan (JP) |
| `2a0f:1cc5:2114::/48` | 🇸🇬 Singapore (SG) |
| `2a0f:1cc5:2115::/48` | 🇰🇷 South Korea (KR) |
| `2a0f:1cc5:2116::/48` | 🇹🇼 Taiwan (TW) |
| `2a0f:1cc5:2117::/48` | 🇮🇳 India (IN) |
| `2118` ~ `211f` | Reserved |

## Europe (`2a0f:1cc5:2120::/44`)

| Prefix | Country |
|---|---|
| `2a0f:1cc5:2120::/48` | 🇩🇪 Germany (DE) |
| `2a0f:1cc5:2121::/48` | 🇳🇱 Netherlands (NL) |
| `2a0f:1cc5:2122::/48` | 🇬🇧 United Kingdom (GB) |
| `2a0f:1cc5:2123::/48` | 🇫🇷 France (FR) |
| `2a0f:1cc5:2124::/48` | 🇫🇮 Finland (FI) |
| `2a0f:1cc5:2125::/48` | 🇨🇭 Switzerland (CH) |
| `2a0f:1cc5:2126::/48` | 🇪🇸 Spain (ES) |
| `2a0f:1cc5:2127::/48` | 🇺🇦 Ukraine (UA) |
| `2a0f:1cc5:2128::/48` | 🇹🇷 Turkey (TR) |
| `2129` ~ `212f` | Reserved |

## North America (`2a0f:1cc5:2130::/44`)

| Prefix | Country |
|---|---|
| `2a0f:1cc5:2130::/48` | 🇺🇸 United States (US) |
| `2a0f:1cc5:2131::/48` | 🇨🇦 Canada (CA) |
| `2132` ~ `213f` | Reserved |

## South America (`2a0f:1cc5:2140::/44`)

Regional pool — allocate on demand. No per-country split.

## Africa (`2a0f:1cc5:2150::/44`)

Regional pool — allocate on demand. No per-country split.

## Oceania + Antarctica (`2a0f:1cc5:2160::/44`)

| Prefix | Assignment |
|---|---|
| `2a0f:1cc5:2160::/48` | 🇦🇺 Australia (AU) |
| `2161` ~ `2167` | Oceania Reserved |
| `2a0f:1cc5:2168::/45` | 🏔️ Antarctica (AQ) — /45 = 8 × /48 |

---

## Utilization Summary

| Category | /44 | /48 | % |
|---|---|---|---|
| Infrastructure | 1 | 16 | 6.25% |
| Continents (6) | 6 | 96 | 37.5% |
| Reserved | 8 | 128 | 50% |
| Lab / Testing | 1 | 16 | 6.25% |
