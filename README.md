# DataClimate

![a](a.png)

## Descrição
Este projeto realiza a análise e previsão de tendências climáticas utilizando dados históricos de temperatura, precipitação e umidade. O pipeline de dados inclui extração, transformação, análise exploratória e modelagem preditiva.

## Estrutura do projeto

- **data/**: Contém dados brutos e processados.

- **notebooks/**: Notebooks Jupyter para análise exploratória.

- **src/**: Scripts Python para extração, limpeza, análise e modelagem.

- **models/**: Modelos treinados.

- **requirements.txt**: Dependências do projeto.

## Tecnologias Utilizadas

- **Processamento de Dados**: Python, pandas, PySpark

- **Armazenamento**: AWS S3 / Local CSV

- **Visualização**: matplotlib, seaborn, Power BI

- **Machine Learning**: scikit-learn, TensorFlow

- **Orquestração**: Apache Airflow

- **Documentação**: Markdown

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/kauecodify/DataClimate.git
    cd DataClimate
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute os scripts na ordem:
    - Extração de dados:
        ```bash
        python src/data_extraction.py
        ```
    - Limpeza de dados:
        ```bash
        python src/data_cleaning.py
        ```
    - Análise e Visualização:
        ```bash
        python src/analysis_visualization.py
        ```
    - Treinamento do Modelo:
        ```bash
        python src/model_training.py
        ```

        

**MIT License ©**
