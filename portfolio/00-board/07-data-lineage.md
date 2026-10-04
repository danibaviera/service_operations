# 07 - Data Lineage

## Data Asset fictício

Daily Energy Indicator

## Fluxo do dado

```text
External Data Source
        ↓
External API
        ↓
Ingestion Process
        ↓
Raw Repository
        ↓
Transformation
        ↓
Curated Repository
        ↓
Internal Data Service
        ↓
Operations System
        ↓
Operational Planning
        ↓
Operations Analyst
```

## Metadados do asset

| Componente | Tipo | Owner | Input | Output | Frequency | Criticality |
|---|---|---|---|---|---|---|
| External Source | Source | External | — | Raw Data | Daily | High |
| External API | Integration | Integration | Data | API response | Daily | High |
| Ingestion Process | Process | Data Ops | API response | Raw data record | Daily | High |
| Raw Repository | Repository | Data Ops | Raw record | Raw dataset | Daily | High |
| Transformation | Processing | Engineering | Raw dataset | Curated dataset | Daily | High |
| Curated Repository | Repository | Data Ops | Curated dataset | Data asset | Daily | High |
| Internal Data Service | API | Tech | Data asset | Service response | On demand | High |
| Operations System | System | Product | Service response | Operational view | Daily | High |
| Operational Planning | Process | Operations | Operational view | Decision | Daily | High |
| Operations Analyst | Persona | Operations | Decision support | Action | Daily | High |

## Papel no case

Esse artefato mostra que o dado pode ser mapeado como um serviço operacional, não apenas como uma tabela ou pipeline técnico. O objetivo é conectar a cadeia técnica à ação do usuário final.
