# Iteration Details

## Iteration 1: Big Data System
### Context:
- Decomposição do sistema Big Data.
- Objetivo: Coletar e processar dados semi-estruturados em larga escala.

### Drivers:
- Ad-hoc Analysis ★★
- Real-time Analysis ★★★
- Unstructured Data Processing ★★★
- Scalability ★★★
- Cost Economy ★★★

### Design Decision:
- **Lambda Architecture (Hybrid)**: Escolhida por equilibrar análise em tempo real e dados históricos.

### Technology:
- Não aplicável nesta iteração.

---

## Iteration 2: Data Stream
### Context:
- Implementação de fluxo de dados para monitoramento em tempo real.

### Drivers:
- Performance ★★
- Compatibility ★★★
- Reliability ★★

### Design Decision:
- **Data Collector**: Escolhido pela compatibilidade com fontes de dados e flexibilidade na coleta.

### Technology:
- **Fluentd**: Escolhido por sua confiabilidade e fácil integração.

---

## Iteration 3: Batch Layer
### Context:
- Processamento de dados históricos em lote.

### Drivers:
- Scalability ★★★
- Availability ★★★

### Design Decision:
- **Distributed File System**: Escolhido por sua escalabilidade e alta disponibilidade.

### Technology:
- **Hadoop Distributed File System (HDFS)**: Implementação eficiente para processamento em lote.

---

## Iteration 4: Serving Layer
### Context:
- Disponibilização de dados processados para sistemas consumidores.

### Drivers:
- Performance ★★
- Ad-hoc Analysis ★★

### Design Decision:
- **Interactive Query Engine**: Melhor equilíbrio entre análise ad-hoc e desempenho.

### Technology:
- **Spark SQL**: Escolhido por sua flexibilidade e integração com a camada de dados.

---

## Iteration 5: Speed Layer
### Context:
- Análise em tempo real para dashboards interativos.

### Drivers:
- Real-time Analysis ★★★
- Ad-hoc Analysis ★★

### Design Decision:
- **Distributed Search Engine**: Suporte a busca full-text e baixa latência.

### Technology:
- **Elasticsearch**: Escolhido pela integração com Kibana e suporte a pesquisas avançadas.

---

