# Fundamentos de Engenharia de Dados

Este projeto tem como objetivo explorar os fundamentos essenciais do ciclo de vida dos dados em uma solução de Engenharia de Dados, 
abrangendo desde a origem até o preparo final para análise.

O primeiro conteúdo **Design e Normalização de Banco de Dados SQL e Banco de Dados NoSQL** aborda os principais conceitos relacionados a bancos de dados, 
com foco especial em suas duas categorias principais: relacionais e não relacionais. 
Inicialmente, é feita uma introdução aos bancos de dados relacionais. Em seguida, são explorados os aspectos do design de bancos de dados relacionais, 
incluindo o Modelo Conceitual, Lógico e Físico. O texto também descreve o processo de normalização, com destaque para as formas normais e suas aplicações na eliminação de redundâncias 
e garantia da integridade. Além disso, é apresentado um panorama sobre os bancos de dados não relacionais (NoSQL), enfatizando suas principais categorias: 
armazenamento chave-valor, de documentos, de coluna larga e de grafos. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/1_bancodedados_relacionais_nrelacionais.pdf)

O segundo conteúdo **ETL e ELT** aborda os processos de ETL (Extract, Transform, Load) e ELT (Extract, Load, Transform), eles são responsáveis por integrar e preparar dados de diferentes fontes para análises e decisões. O ETL extrai dados, transforma-os antes do carregamento e é ideal para ambientes locais e com dados que precisam de limpeza imediata. O ELT, por sua vez, extrai e carrega dados brutos diretamente em um Data Warehouse ou Data Lake, realizando a transformação no destino, sendo mais eficiente para grandes volumes e ambientes na nuvem. 
A escolha entre ETL e ELT depende de fatores como ambiente tecnológico, volume de dados e requisitos de processamento. O ETL é indicado para sistemas legados ou locais, enquanto o ELT é mais eficiente em ambientes modernos com grande capacidade de processamento. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/2_extracao_dados_etl_elt.pdf)

O terceiro conteúdo **Armazenamento e Modelagem em Data Warehouse**, traz uma introdução ao conceito de Data Warehouse (DW) e sua importância como um repositório central de dados voltado para análises, destacando a separação entre os processos transacionais (OLTP) e analíticos (OLAP) para otimização de desempenho. 
Em seguida, são explorados aspectos relacionados à arquitetura do DW, destacando as camadas Staging, Back Room e Front Room. O texto também descreve a diferença entre os modelos Relacional e Dimensional, com foco em suas aplicações em OLTP e OLAP, respectivamente.
Além disso, são apresentados conceitos de esquemas em estrela e floco de neve, amplamente utilizados em sistemas de Data Warehouse, e o papel dos Data Marts como subgrupos específicos para análises departamentais. Você pode acessar este tópico [neste link.](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/3_data_warehouse_modelagem%20.pdf)
