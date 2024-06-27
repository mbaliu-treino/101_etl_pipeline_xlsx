# ETL Pipeline XLSX

Este projeto consiste em um processo de ETL simples para consolidar dados de múltiplos arquivos XLSX em um único arquivo. 

O código Python utiliza bibliotecas como Pandas, Openpyxl, Xlsxwriter para manipular os dados localizados em um repositório local

## Funcionalidades

* Extração de dados de vários arquivos XLSX em um pasta específica (`src/data/raw`)
* Adição de informações de rastreabilidade, como nome do arquivo, localidade e informações de campanha a partir de links UTM
* Concatenação dos dados em um único DataFrame
* Persistência do DataFrame em um novo arquivo XLSX


## Como usar

1. Prepração do ambiente de execução

`pip install -r requirements.txt`

2. Os arquivos XLSX devem estar na pasta `src/data/raw`.

3. Execute o script python

4. O arquivo consolidado será salvo em `src/data/ready/data_cleaned.xlsx`


## Conclusões

Este projeto serve como base para construir pipelines de dados mais complexos e pode ser adaptado para diferentes fontes de dados e requisitos de transformação.