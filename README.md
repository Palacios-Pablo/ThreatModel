# ThreatModel

Threat models built with **OWASP Threat Dragon** for the Master's in Information Security (Universidad Mariano Gálvez, course: Application Security).

## Main model: Markt GT (e-commerce)

STRIDE threat model of an e-commerce platform with web store, mobile app, API gateway, microservices (identity, catalog, orders, payments, notifications) and banking integrations.

| Diagram | Threats identified |
|---|---|
| DFD Level 0 – Context | 7 |
| DFD Level 1 – Main processes | 44 |
| DFD Level 2 – Payments and bank integrations | 19 |

Total: **70 threats** across Spoofing, Tampering, Repudiation, Information disclosure, Denial of service and Elevation of privilege.

## Files
- `MarktGT-threat-model.json`: the full model (open it in Threat Dragon).
- `ThreatDragonModels/`: additional exploratory models.

## How to open it
Go to [threatdragon.com](https://www.threatdragon.com/) or the desktop app and use *Open an existing threat model* with the JSON file.
