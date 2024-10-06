# Projeto de Pipeline de Dados

Este projeto visa construir um pipeline de dados para coleta, processamento e armazenamento de informações provenientes de APIs públicas. O pipeline inclui etapas de extração, transformação e carregamento de dados (ETL) e inclui um sistema de alertas para monitorar possíveis falhas durante o processo.

## Visão Geral

O pipeline de dados é projetado para integrar dados de várias APIs e prepará-los para análise. O projeto utiliza as seguintes APIs:

- **[API de Bancos do Brasil](https://brasilapi.com.br/api/banks/v1)**: Fornece informações sobre bancos registrados no Brasil.
- **[API de Participantes de Pix](https://brasilapi.com.br/api/pix/v1/participants)**: Fornece informações sobre participantes do sistema de pagamentos Pix.
- **[API de  Corretoras](https://brasilapi.com.br/api/cvm/corretoras/v1)**: Fornece informações sobre corretoras financeiras.

## Funcionalidades

O projeto inclui as seguintes funcionalidades:

- **Extração de Dados**: Coleta dados das APIs e armazena no banco de dados.
- **Transformação de Dados**: Processa e transforma os dados extraídos para facilitar a análise.
- **Sistema de Alerta**: Notifica em caso de falhas durante a extração ou transformação dos dados.
- **Armazenamento de Dados**: Utiliza um banco de dados SQLite para armazenar dados extraídos e transformados.

## Requisitos

Certifique-se de ter o Python instalado em seu sistema. Você também precisará do Jupyter Notebook para executar o pipeline.

### Instalação das Dependências

Para instalar as bibliotecas necessárias, use o arquivo `requirements.txt` incluído no projeto. Este arquivo lista todas as dependências necessárias para executar o pipeline.

```bash
pip install -r requirements.txt
