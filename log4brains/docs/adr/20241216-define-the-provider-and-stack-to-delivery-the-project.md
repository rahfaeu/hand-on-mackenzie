# Define the provider and stack to delivery the project

- Status: superseded by [20241216-define-the-provider-and-stack-to-delivery-the-project-2](20241216-define-the-provider-and-stack-to-delivery-the-project-2.md) 
- Tags: arquitetura, stack

Technical Story: [description | ticket/issue URL] <!-- optional -->

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

- GCP - Ferramenta mais utilizada pelos integrantes e se integra bem com dbt.
- BigQuery - É um dos três principais data warehouses modernos e se integra nativamente com o dbt.
- Streamlit - O Streamlit transforma scripts de dados em aplicativos web compartilháveis em minutos. Tudo em Python puro. Não é necessária experiência com front-end.
- Elementary - Solução nativa de observabilidade de dados para engenheiros de dados e analytics.
- Slack - A plataforma Slack oferece muitas ferramentas para ajudar a aprimorar seus workspaces. Em um nível mais alto, elas podem ser vistas através da lente das automações de fluxo de trabalho e dos aplicativos Slack que não são de fluxo de trabalho.
- Tableau - Ferramenta escolhida para realização da parte de Data Viz do projeto, pois foi a que aprendemos no curso e achamos que seria uma boa oportunidade de explorá-la.

## Considered Options

- AWS e Red Shift
- Azure e Databricks
- Jupyter

## Decision Outcome

- Escolhemos utilizar GCP com BigQuery pois são as ferramenta mais utilizadas pelos integrantes e se integra bem com dbt.

### Positive Consequences <!-- optional -->

- Utilizando o conceito de modern data stack, temos o tempo de desenvolvimento acelerado e ganhamos recursos de DataOps, Observabilidade, Monitoriamento, Alertas Tempestivos e tratativas, Documentação, Contrato de dados e outras possibilidades.


### Negative Consequences <!-- optional -->

- Treinamento do time com as ferramentas de Modern Data Stack.
- Avaliação do custo do projeto.