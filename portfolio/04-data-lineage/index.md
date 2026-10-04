# 04 - Data Lineage

## Objetivo

Explicar a cadeia do dado desde a origem até o consumidor final, mostrando dependências e pontos de interrupção.

## Data asset principal

Daily Energy Indicator - indicador diário fictício, de criticidade alta, consumido no planejamento operacional.

## Fluxo principal

Source → API → Raw Repository → Transformation → Curated Repository → Internal Service → Operations System → Operational Planning → Operations Analyst

A tabela de metadados do asset está em [../00-board/07-data-lineage.md](../00-board/07-data-lineage.md) e o ponto de falha em [../00-board/09-failure-scenario.md](../00-board/09-failure-scenario.md).

## Materiais fictícios

- [lineage-ficticia/index.md](lineage-ficticia/index.md)
- [lineage-ficticia/repositorios-ficticios.csv](lineage-ficticia/repositorios-ficticios.csv)
- [lineage-ficticia/lineage-ficticia.json](lineage-ficticia/lineage-ficticia.json)
- [bpmn-ficticio/index.md](bpmn-ficticio/index.md)
- [bpmn-ficticio/processo-bpmn.md](bpmn-ficticio/processo-bpmn.md)
