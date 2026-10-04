# 12 - Solution Concept

## Operacional Data Map

Ou Data Flow Explorer.

## Busca por data asset

```text
Search data asset

> Daily Energy Indicator
```

## Resultado esperado

```text
Daily Energy Indicator

STATUS
⚠ Delayed

EXPECTED UPDATE
07:00

LAST SUCCESSFUL UPDATE
Yesterday - 07:03

DATA FLOW

✓ External Source
        ↓
✓ API
        ↓
✓ Raw Repository
        ↓
✕ Transformation
        ↓
○ Curated Repository
        ↓
○ Operations System

POSSIBLE FAILURE
Transformation Process

OWNER
Data Operations

DEPENDENT PROCESS
Daily Operational Planning
```

## Proposta de melhoria

Uma interface simples de consulta permitiria que a operação localizasse rapidamente onde o problema está, quem é responsável e quais atividades serão impactadas.
