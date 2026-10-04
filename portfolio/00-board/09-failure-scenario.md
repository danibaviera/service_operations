# 09  Failure Scenario

## Scenario #01 Processing Failure

```text
✓ External Source
        ↓
✓ External API
        ↓
✓ Raw Repository
        ↓
✕ Transformation
        ↓
○ Curated Repository
        ↓
○ Internal Service
        ↓
○ Operations System
```

## Sequência de impacto

```text
TECHNICAL FAILURE
Transformation failed
        ↓
DATA IMPACT
Dataset unavailable
        ↓
SYSTEM IMPACT
Indicator unavailable
        ↓
PROCESS IMPACT
Analysis cannot continue
        ↓
OPERATIONAL IMPACT
Planning delayed
        ↓
EMPLOYEE IMPACT
Manual investigation begins
```

## Por que esse frame é forte

Ele conecta, de forma visual, a tese central do case: a falha técnica não fica apenas no backstage. Ela se transforma em atraso operacional e esforço humano para localizar a origem do problema.
