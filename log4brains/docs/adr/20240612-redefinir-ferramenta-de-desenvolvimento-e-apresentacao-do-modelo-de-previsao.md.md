# Define the provider and stack to delivery the project

- Status: accepted 
- Tags: arquitetura, stack

## Context and Problem Statement

Definir qual provedor de nuvem escolher para executar o projeto, bem como a stack que utilizaremos para desenvolver os processos de ingestão, transformação, modelo de previsão de vendas e ferramenta de dataviz que estejam de acordo com todos os integrantes.

## Decision Makers <!-- optional -->

| Nome                    | Função                                               | Matrícula |
|-------------------------|------------------------------------------------------|-----------|
| Gustavo Bido            | Data Governance                                      | 10444746  |
| Neoaquison Medeiros     | Data Engineer e Devops                               | 10444895  |
| Rafael dos Santos       | Product Manager, Data Engineer e Analytics Engineer  | 10444896  |
| Samuel Perumalswamy     | Data Engineer                                        | 10444049  |

## Decision Drivers <!-- optional -->

- GCP - Ferramenta mais utilizada pelos integrantes e se integra bem com dbt
- BigQuery - É um dos três principais data warehouses modernos e se integra nativamente com o dbt
- Jupyter

## Considered Options

- AWS e Red Shift
- Azure e Databricks
- … <!-- numbers of options can vary -->

## Decision Outcome

Escolhemos utilizar GCP com BigQuery pois são as ferramenta mais utilizadas pelos integrantes e se integra bem com dbt

### Positive Consequences <!-- optional -->



### Negative Consequences <!-- optional -->