Projeto de Armazenamento, Manipulação e Transformação de Dados

Projeto desenvolvido como atividade final do componente Armazenamento, Manipulação e Transformação de Dados, com foco na consolidação, tratamento e análise de dados utilizando conceitos de ETL e modelagem dimensional (Star Schema).

⭐ Metodologia STAR
🟢 S — Situation (Situação)

Um marketplace fictício enfrentava dificuldades para analisar seu desempenho operacional e comercial. Os dados do negócio estavam distribuídos em múltiplos arquivos CSV independentes, provenientes de diferentes sistemas, como pedidos, clientes e produtos.

Essa descentralização causava inconsistências, dificultava análises históricas e impedia a geração de indicadores confiáveis para apoiar a tomada de decisão estratégica.

🎯 T — Task (Tarefa)

O objetivo do projeto foi consolidar, limpar e transformar os dados brutos em uma estrutura analítica confiável, permitindo:

Padronização e qualidade dos dados

Integração das múltiplas fontes

Criação de um Data Warehouse modelado em Star Schema

Execução de consultas analíticas para geração de insights de negócio

⚙️ A — Action (Ação)

Para atender ao desafio proposto, foram executadas as seguintes etapas:

Importação dos arquivos CSV para uma Staging Area

Limpeza e tratamento dos dados (remoção de duplicidades, normalização e validações)

Implementação do processo ETL para carga dos dados tratados

Modelagem dimensional com tabelas fato e dimensões

Desenvolvimento de consultas SQL para análise dos dados consolidados

🏗️ Arquitetura da Solução

Fluxo de Dados:

CSVs Brutos
   ↓
Staging Area (Limpeza e Tratamento)
   ↓
Data Warehouse (Star Schema)
   ↓
Dashboard & Insights
