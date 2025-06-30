# gamepass-sales-dashboard
Interactive dashboard for analyzing Xbox Game Pass sales and subscriptions. Organizes, visualizes, and extracts insights from raw data to support strategic decision-making.
# Dashboard de Vendas — Xbox Game Pass 🎮

Este projeto tem como objetivo construir um **dashboard de vendas**, focado na organização e visualização dos dados de assinaturas do Xbox Game Pass. Ao transformar os dados brutos em gráficos claros e informativos, o dashboard permite uma análise eficaz do desempenho de vendas e apoia decisões estratégicas baseadas em dados.

---

## 🚩 Objetivo

- Organizar e visualizar dados de vendas.
- Identificar tendências e padrões de assinaturas.
- Facilitar decisões baseadas em informações confiáveis.

---

## 📦 Dados Utilizados

Os dados utilizados referem-se ao volume de assinaturas do Xbox Game Pass ao longo de 2024.  
**Principais campos:**

- `subscriber_id`: Identificador único do assinante
- `name`: Nome do assinante
- `plan`: Tipo de plano (Ultimate, Standard, Core)
- `start_date`: Data de início da assinatura
- `auto_renewal`: Renovação automática ativada
- `subscription_price`: Valor do plano base
- `subscription_type`: Periodicidade do plano
- Demais colunas relativas a benefícios extras, descontos e valor total da venda

As colunas eventualmente “vazias” (`empty_1`, `empty_3`, etc.) foram mantidas para futuras atualizações ou integração de novos dados.

---

## 🗂 Estrutura do Repositório

```text
/
├── data/
│   └── vendas_xbox_game_pass_2024.xlsx     # Base de dados de assinaturas
├── src/
│   ├── app.py                             # Script principal do dashboard
│   ├── dashboard/
│   │   └── componentes_dash.py            # Componentes visuais do dashboard
│   └── utils/
│       └── processamento_dados.py         # Funções auxiliares
├── notebooks/
│   └── analise_exploratoria.ipynb         # Notebook para análise exploratória
├── README.md
├── requirements.txt                       # Bibliotecas necessárias
└── LICENSE
