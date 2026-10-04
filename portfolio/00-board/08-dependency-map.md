# 08 - Dependency Map

## Dependências de múltiplos dados

```text
Meteorological Forecast ───┐
                           │
Energy Indicator ──────────┼──→ Operational Planning
                           │
Reservoir Information ─────┘
```

## Dependência inversa do dado

```text
Curated Dataset
     │
     ├──→ Operations System
     │        ↓
     │    Planning
     │
     ├──→ Dashboard
     │        ↓
     │    Monitoring
     │
     └──→ Daily Report
              ↓
          Business Team
```

## Insight

Uma atividade operacional pode depender de múltiplos fluxos de informação ao mesmo tempo. Quando uma parte da cadeia falha, o impacto vai além do dado em si: alcança a atividade, a decisão e a experiência do time.
