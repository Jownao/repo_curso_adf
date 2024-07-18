# repo_curso_adf

Este repositório contém os arquivos e recursos relacionados ao curso "Azure Data Factory para Iniciantes". Aqui, você encontrará pipelines, datasets, linked services e outros componentes implementados durante o curso.

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Pipelines](#pipelines)
- [Datasets](#datasets)
- [Linked Services](#linked-services)
- [Como Executar](#como-executar)
- [Licença](#licença)

## Sobre o Projeto

Este repositório foi criado como parte do curso "Azure Data Factory para Iniciantes". O objetivo do curso é ensinar os fundamentos do Azure Data Factory (ADF), uma ferramenta de integração de dados na nuvem. Durante o curso, aprendemos a criar e gerenciar pipelines de dados, conectar a várias fontes de dados e realizar transformações.

## Estrutura do Repositório

```plaintext
repo_curso_adf/
├── datasets/
│   ├── ds_fixo_azuresql.json
│   ├── ds_fixo_excel.json
│   ├── ds_fixo_json.json
│   ├── ds_generico_azuresql.json
│   ├── ds_generico_csv.json
│   ├── ds_generico_parquet.json
├── factory/
│   ├── adf-firstproject-jownao.json
├── linkedService/
│   ├── ls_azuresql.json
│   ├── ls_datalake.json
├── pipeline/
│   ├── pipe_01.json
│   ├── pipe_copydata.json
│   ├── pipe_executepipeline.json
│   ├── pipe_filter.json
│   ├── pipe_forEach.json
│   ├── pipe_getmetadata.json
│   ├── pipe_gitHub.json
│   ├── pipe_gitHub_copy1.json
│   ├── pipe_lookup.json
│   ├── pipe_storedprocedure.json
│   ├── pipe_wait.json
│   ├── pipeline_parametros.json
│   ├── pratica_01.json
│   ├── pratica_02.json
│   ├── pratica_03.json
│   ├── pratica_04.json
├── LICENSE
└── README.md
```

## Pipelines

As pipelines são usadas para orquestrar processos de ETL (Extract, Transform, Load). Aqui estão as pipelines incluídas neste repositório:

- **pipe_01.json**: Pipeline inicial com um exemplo básico de cópia de dados.
- **pipe_copydata.json**: Pipeline para copiar dados entre duas fontes.
- **pipe_executepipeline.json**: Pipeline que executa outra pipeline.
- **pipe_filter.json**: Pipeline que aplica filtros nos dados.
- **pipe_forEach.json**: Pipeline que utiliza um loop ForEach.
- **pipe_getmetadata.json**: Pipeline que obtém metadados de uma fonte de dados.
- **pipe_gitHub.json**: Pipeline que integra com o GitHub.
- **pipe_gitHub_copy1.json**: Cópia da pipeline de integração com o GitHub.
- **pipe_lookup.json**: Pipeline que realiza operações de lookup.
- **pipe_storedprocedure.json**: Pipeline que chama uma stored procedure.
- **pipe_wait.json**: Pipeline que implementa uma atividade de espera.
- **pipeline_parametros.json**: Pipeline que demonstra o uso de parâmetros.
- **pratica_01.json**: Pipeline prática 01.
- **pratica_02.json**: Pipeline prática 02.
- **pratica_03.json**: Pipeline prática 03.
- **pratica_04.json**: Pipeline prática 04.

## Datasets

Os datasets representam as fontes de dados usadas nas pipelines. Aqui estão os datasets incluídos neste repositório:

- **ds_fixo_azuresql.json**: Dataset fixo para Azure SQL.
- **ds_fixo_excel.json**: Dataset fixo para arquivos Excel.
- **ds_fixo_json.json**: Dataset fixo para arquivos JSON.
- **ds_generico_azuresql.json**: Dataset genérico para Azure SQL.
- **ds_generico_csv.json**: Dataset genérico para arquivos CSV.
- **ds_generico_parquet.json**: Dataset genérico para arquivos Parquet.

## Linked Services

Os Linked Services definem as conexões com os serviços de dados. Aqui estão os Linked Services incluídos neste repositório:

- **ls_azuresql.json**: Linked Service para conexão com Azure SQL.
- **ls_datalake.json**: Linked Service para conexão com Azure Data Lake.

## Como Executar

Para executar as pipelines e datasets deste repositório, siga os passos abaixo:

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/Jownao/repo_curso_adf.git
    ```
2. **Importe os arquivos no Azure Data Factory**:
    - Faça login no portal do Azure.
    - Navegue até o seu Data Factory.
    - Importe os pipelines, datasets e linked services na interface do ADF.

3. **Configure os Linked Services**:
    - Verifique os arquivos JSON dos pipelines e datasets para identificar os Linked Services necessários.
    - Configure os Linked Services no ADF para garantir que eles apontem para as fontes de dados corretas.

4. **Execute as Pipelines**:
    - Após configurar os Linked Services, execute as pipelines diretamente do portal do ADF.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
```

Você pode copiar o conteúdo acima e colar no seu arquivo `README.md`.
