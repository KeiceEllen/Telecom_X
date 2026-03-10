# Telecom_X
🧠 **Visão Geral**

Este projeto tem como objetivo analisar os dados da empresa fictícia TelecomX, uma operadora de telecomunicações que enfrenta altos índices de evasão de clientes (churn).
Através de técnicas de Análise Exploratória de Dados (EDA), buscamos identificar padrões, comportamentos e fatores que influenciam o cancelamento de serviços, fornecendo insights estratégicos para apoiar a tomada de decisão do negócio.

O projeto foi desenvolvido seguindo as etapas clássicas de um pipeline de Data Science, contemplando extração, transformação, análise e elaboração de relatório final.

🎯**Objetivos do Projeto**

- Entender como a evasão de clientes está distribuída na base de dados;

- Identificar perfis de clientes com maior propensão ao churn;

- Analisar o impacto de variáveis categóricas e numéricas na evasão;

- Gerar insights acionáveis para redução do churn;

- Consolidar os resultados em um relatório claro e bem estruturado.

🛠️ **Tecnologias Utilizadas**

- Python

- Pandas — manipulação e limpeza dos dados

- Matplotlib & Seaborn — visualização de dados

- Google Colab — ambiente de desenvolvimento

- Git & GitHub — versionamento e publicação do projeto

📂 **Estrutura do Projeto**
```│
📁 telecomx-churn-analysis

├── 📄 TelecomX_Data.json        # Dataset original
├── 📄 notebook.ipynb            # Notebook com todo o pipeline de análise
├── 📄 README.md                 # Documentação do projeto
└── 📄 relatório_final.md/pdf    # Relatório final (opcional)
```
🔄 **Etapas do Projeto**

1️⃣ Extração

- Importação do dataset no formato JSON.

2️⃣ Limpeza e Tratamento de Dados

- Padronização de variáveis categóricas (Yes/No);

- Conversão de tipos de dados;

- Tratamento de valores inconsistentes e ausentes;

- Criação da variável Contas_Diarias para análise de gasto diário.

3️⃣ Análise Exploratória de Dados (EDA)

- Distribuição geral de churn;

- Análise de churn por variáveis categóricas (contrato, serviços, pagamento);

- Análise de churn por variáveis numéricas (tempo de contrato, cobranças);

- Uso de gráficos de barras, pizza, boxplot e histogramas.

4️⃣ Relatório Final

- Consolidação dos achados;

- Geração de insights estratégicos;

- Recomendações práticas para redução da evasão.

📈 Principais Insights

- Clientes com contratos Month-to-month apresentam maior churn;

- Clientes com menor tempo de permanência cancelam mais;

- Cobranças mensais elevadas estão associadas à evasão;

- Falta de serviços adicionais (segurança, suporte técnico) aumenta o churn;

- Método de pagamento Electronic Check apresenta maior risco de cancelamento.

📌 Conclusão

A análise mostrou que a evasão de clientes na TelecomX está fortemente relacionada a fatores contratuais, financeiros e de experiência do usuário.
Os resultados deste projeto podem ser utilizados como base para estratégias de retenção, personalização de ofertas e até desenvolvimento de modelos preditivos de churn.

🚀 Próximos Passos (Possíveis Extensões)

- Construção de um modelo de Machine Learning para previsão de churn;

- Balanceamento de classes;

- Feature engineering avançado;

- Avaliação de métricas de classificação.

