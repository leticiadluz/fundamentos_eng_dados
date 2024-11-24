# Fundamentos de Engenharia de Dados

Este projeto tem como objetivo explorar os fundamentos essenciais do ciclo de vida dos dados em uma solução de Engenharia de Dados, 
abrangendo desde a origem até o preparo final para análise.

O primeiroconteúdo **ETL e ELT** aborda os processos de ETL (Extract, Transform, Load) e ELT (Extract, Load, Transform), eles são responsáveis por integrar e preparar dados de diferentes fontes para análises e decisões. O ETL extrai dados, transforma-os antes do carregamento e é ideal para ambientes locais e com dados que precisam de limpeza imediata. O ELT, por sua vez, extrai e carrega dados brutos diretamente em um Data Warehouse ou Data Lake, realizando a transformação no destino, sendo mais eficiente para grandes volumes e ambientes na nuvem. 
A escolha entre ETL e ELT depende de fatores como ambiente tecnológico, volume de dados e requisitos de processamento. O ETL é indicado para sistemas legados ou locais, enquanto o ELT é mais eficiente em ambientes modernos com grande capacidade de processamento. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/1_extracao_dados_etl_elt.pdf)

O segundo conteúdo **Armazenamento e Modelagem em Data Warehouse**, traz uma introdução ao conceito de Data Warehouse (DW) e sua importância como um repositório central de dados voltado para análises, destacando a separação entre os processos transacionais (OLTP) e analíticos (OLAP) para otimização de desempenho. 
Em seguida, são explorados aspectos relacionados à arquitetura do DW, destacando as camadas Staging, Back Room e Front Room. O texto também descreve a diferença entre os modelos Relacional e Dimensional, com foco em suas aplicações em OLTP e OLAP, respectivamente.
Além disso, são apresentados conceitos de esquemas em estrela e floco de neve, amplamente utilizados em sistemas de Data Warehouse, e o papel dos Data Marts como subgrupos específicos para análises departamentais. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/2_data_warehouse_modelagem%20.pdf)

O terceiro conteúdo **Data Lake, Data Lakehouse, Delta Lake e Arquitetura Medalhão**  explora a evolução das arquiteturas de dados desde o Data Warehouse (DW) até o conceito mais avançado de Data Lakehouse. Inicialmente, os data warehouses foram projetados para integrar dados estruturados de diferentes áreas de uma empresa, utilizando modelos dimensionais para análises OLAP. Contudo, enfrentaram limitações significativas frente aos desafios do big data. Para superar essas barreiras, surgiu o Data Lake, que permite armazenar dados estruturados, semiestruturados e não estruturados em um único repositório centralizado. Apesar de promissores, os data lakes enfrentaram desafios como desorganização dos dados, baixa eficiência para consultas diretas e falta de governança, levando ao surgimento de híbridos conhecidos como Lakehouses. O Data Lakehouse combina a flexibilidade e escalabilidade do data lake com as funcionalidades avançadas de governança e transações ACID típicas de um data warehouse. Essa evolução é suportada por frameworks como Delta Lake, Apache Iceberg e Apache Hudi, que introduzem controles avançados e organizam dados brutos em tabelas estruturadas, otimizando o desempenho analítico. O Delta Lake um dos componentes centrais na implementação de um Data Lakehouse transforma o data lake bruto em uma solução altamente eficiente e governada, otimizando o armazenamento e as análises. A Arquitetura Medallion é um padrão amplamente utilizado em soluções baseadas em Delta Lake, funcionando como uma estrutura lógica para gerenciar e organizar os dados em etapas de qualidade e refinamento. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/3_datalake_lakehouse_deltalake.pdf)

O conteúdo extra **Design e Normalização de Banco de Dados SQL e Banco de Dados NoSQL** aborda os principais conceitos relacionados a bancos de dados, 
com foco especial em suas duas categorias principais: relacionais e não relacionais. 
Inicialmente, é feita uma introdução aos bancos de dados relacionais. Em seguida, são explorados os aspectos do design de bancos de dados relacionais, 
incluindo o Modelo Conceitual, Lógico e Físico. O texto também descreve o processo de normalização, com destaque para as formas normais e suas aplicações na eliminação de redundâncias 
e garantia da integridade. Além disso, é apresentado um panorama sobre os bancos de dados não relacionais (NoSQL), enfatizando suas principais categorias: 
armazenamento chave-valor, de documentos, de coluna larga e de grafos. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/extra_bancodedados_sql_nosql.pdf)


Autor:
Leticia da Luz
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/leticiadluz/)
