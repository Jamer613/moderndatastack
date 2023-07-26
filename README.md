# Data Engineering com Modern_data_Stack.

Objetivos do Projeto - Criar um pipeline de dados utilizando modern data stack de ponta a ponta, desde a extração, carregamento, tratamento, ingestão, orquestração e consumo pelo usuário final. 

Documentação:

Ambiente de Desenvolvimento https://www.gitpod.io/

Documentação do Airbyte https://airbytehq.github.io/

Documentação do Airflow https://airflow.apache.org/docs/

Documentação do Dbt https://docs.getdbt.com/

Documentação do Snowflake https://docs.snowflake.com/en/

Documentação do Metabase https://www.metabase.com/docs/latest/

Link datasets utilizados https://health.google.com/covid-19/open-data/raw-data


# Tarefas a serem executadas para o Projeto Modern_data_stack:


Tarefas:

Infraestrutura:

- Setup do ambiente de desenvolvimento (Hardware, Software - Linux, Python, Docker, Curl, Pip, Git, Npm, etc...) X

- Setar as Permissoes do Gitpod ao Repositorio no Github X

- Subir o Airbyte via docker X

- Subir o Airflow via docker X

- Subir o Metabase via docker X

- Criar o script de execução ?

- Testar a Execução ?

- Snowflake Data Warehouse:
    
    - Criar a Conta no SnowFlake X
    - Verificar a existência das tabelas X
    - Obter os links de conexão e nome da conta X


Extração:

- No Airbyte:

    - Conectar com as origens baseadas nos Csvs X
    - Criar as entidades no snowflake através do script base da documentação    X
    - Conectar o destino no snowflake X
    - Criar as conexões do airbyte associando as origens ao destino X
    - Testar as conexões X


Preparação:

- No Airbyte (Destination Loading Method):

    - Local Staging (Ambiente de Desenvolvimento) X
    - Cloud Staging (Ambiente de Produção) X


Transformação:

- No Dbt:

    - Criação da Conta  X
    - Conexão com o Github  X
    - Criação do Dbt Project  X
    - Criação do Profile de conexão com o snowflake X
    - Criação do Schema X
    - Criação dos Modelos Base X
    - Criação do Modelo Relacionado X
    - Visualização gráfica do modelo X 
    - Teste de execução X
    - Commits, Branches, Pull Requests, Merges no Github  X
    - Obtenção do link de conexão com o Airbyte  X


Visualização:

- No Metabase:

    - Conectar Metabase com o Snowflake x
    - Criar uma Question  x
    - Criar um Dashboard x
    - Adicionar uma Question x
    - Visualizar o Resultado x


Orquestração:

- No Airflow:

    - Criar a dag x

    - Criar a Docker network x

    - Incluir nos composes a network criada x

    - Setup Up no serviço x

    - Testar a conexao entre os containers do airflow e do airbyte x

    - Criar as conexões com o Airbyte através do script x  

    - Testar a execução do pipeline x

Encerramento:

Concluo que o projeto é totalmente funcional, com um ótimo desempenho, facilidade no desenvolvimento, praticamento um projeto low code, atingindo assim o objetivo inicial, saliente que para utiliza-lo em um ambiente de produção seria necessário alguns passos a mais, como algumas configurações do ambiente, e gerenciamento dos containers através de Kubernets ou ferramentas desta finalidade. 

