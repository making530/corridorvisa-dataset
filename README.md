# CorridorVisa Dataset

Structured visa-requirement data for **1993** passport × destination corridors, **194** passports, and **15** policy-change events.

**Live site:** https://corridorvisa.com
**License:** CC BY-SA 4.0 (attribution required — see LICENSE)
**Last export:** 2026-09-20

## Files

| File | Rows | Contents |
|---|---|---|
| `corridors.csv/json` | 1993 | visa status, max stay, fee, official portal, last-verified date for every pair |
| `passports.csv/json` | 194 | visa-free count + Henley rank per passport, sorted desc |
| `changes.csv/json` | 15 | policy-change events with before/after values and source URLs |

## Attribution

> CorridorVisa (2026). *Corridor Visa Requirements Dataset*. https://corridorvisa.com · CC BY-SA 4.0

## Method

Each fact carries a `last_verified` date. Facts older than 90 days are flagged as unverified on the live site. Sources: official government portals (primary), English Wikipedia (secondary, CC BY-SA 4.0). Only structured fields are exported here — no prose.

## Contact

making530@gmail.com
