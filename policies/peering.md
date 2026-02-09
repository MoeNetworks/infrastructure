# Peering Policy — MoeNet LLC (AS214773)

## Policy: Open Peering

MoeNet maintains an **open peering policy**. We welcome peering with networks of all sizes.

## Requirements

- Valid ASN
- Valid, non-bogon IPv6 prefix(es)
- Up-to-date PeeringDB record (preferred)
- Responsive NOC contact

## Peering Details

| Field | Value |
|---|---|
| ASN | AS214773 |
| IPv6 Prefix | `2a0f:1cc5:2100::/40` |
| Max Prefix v6 | 256 |
| NOC Email | <noc@moenetworks.net> |
| Peering Contact | <noc@moenetworks.net> |

## Peering Locations

| Location | Node |
|---|---|
| Hong Kong | hk1 |
| Tokyo, JP | jp1 |
| Los Angeles, US | us1 |
| Frankfurt, DE | de1 |

## How to Peer

1. Send an email to `noc@moenetworks.net` with your ASN and preferred location
2. Or reach out via Telegram: [@moenet](https://t.me/moenet)

## Traffic Policy

- Routes with RPKI invalid status are rejected
- IRR filtering is applied
- No traffic ratio requirements
- BGP communities are supported (see documentation)
