# Análise Comparativa da Segurança Pública: São Paulo vs Rio de Janeiro (2002–2021)
O projeto realiza uma análise de visualização e comparação dos dados de segurança pública dos estados de São Paulo (SP) e Rio de Janeiro (RJ), com foco em crimes como homicídios, roubos e furtos, a partir de dados oficiais disponibilizados por órgãos estaduais.
---

## Contexto
A segurança pública é uma das maiores preocupações da população brasileira. Para entender melhor os padrões e tendências da criminalidade em dois dos principais estados do país, obtem-se dados abertos disponibilizados por:
- Secretaria de Segurança Pública do Estado de São Paulo (SSP-SP)
- Instituto de Segurança Pública do Estado do Rio de Janeiro (ISP-RJ)

Fontes de dados utilizadas:
- SP: [base SSP-SP](https://basedosdados.org/dataset/90324ba8-9c39-4191-a8a4-302f93732464)
- RJ: [base ISP-RJ](https://basedosdados.org/dataset/dbd717cb-7da8-4efd-9162-951a71694541)

---

## Metodologia

### 1. Coleta e consulta dos dados
Foram utilizados arquivos CSV contendo estatísticas mensais de crimes dos anos de 2002 a 2021, tanto a nível estadual quanto por município/região.

### 2. Processamento
- Conversão de colunas de ano/mês para o formato de data.
- Preenchimento de valores nulos com 0 para colunas numéricas.
- Filtragem dos dados para manter apenas o período comum entre SP e RJ (2002–2021).

## Resultados

### Homicídios
- O RJ apresentou valores mais altos de homicídios dolosos no início do período, mas caiu ao longo dos anos, se aproximando de SP.
- SP teve uma distribuição estável nas duas décadas analisadas.
- A capital e a região metropolitana concentram a maior parte dos homicídios em SP.
- No RJ, os maiores volumes foram identificados em municípios da Baixada Fluminense (Duque de Caxias, Nova Iguaçu, Belford Roxo).

### Roubos e Furtos
- Tem-se uma previsibilidade nos roubos, com picos em março/abril e novembro/dezembro.
- Os furtos também apresentam aumento nos meses de férias e festas (janeiro e dezembro).
- SP tem volumes significativamente maiores de crimes patrimoniais comparado ao RJ.

---
