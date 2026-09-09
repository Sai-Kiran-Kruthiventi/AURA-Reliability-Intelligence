# AURA API Contract

This document defines how the different AURA modules communicate.

## Anomaly Detection Output

```json
{
  "component_id": "COMP-1042",
  "timestamp": "2026-09-08T14:32:17",
  "anomaly_score": 0.91,
  "severity": "critical",
  "affected_parameters": [
    "temperature",
    "voltage"
  ]
}
