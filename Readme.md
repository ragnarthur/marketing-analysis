# Projeto de Análise de Marketing

Este repositório contém um projeto de análise de marketing utilizando técnicas de segmentação RFM (Recency, Frequency, Monetary) para categorizar clientes com base em seu comportamento de compra.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `marketing_campaign.xlsx`: Dataset utilizado para a análise, disponível no [Kaggle](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign).
- `analysis.ipynb`: Jupyter Notebook contendo o código para análise e segmentação dos clientes.
- `README.md`: Este arquivo, que descreve o projeto e suas etapas.

## Objetivo

O objetivo deste projeto é analisar o comportamento dos clientes e segmentá-los utilizando a técnica de RFM. A análise ajudará a entender melhor os diferentes segmentos de clientes e a desenvolver estratégias de marketing mais eficazes.

## Dataset

O dataset utilizado neste projeto foi obtido do [Kaggle](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign). Ele contém informações sobre clientes, incluindo dados demográficos, comportamentais e respostas a campanhas de marketing.

### Detalhes do Dataset

- **ID**: Identificador único do cliente.
- **Year_Birth**: Ano de nascimento do cliente.
- **Education**: Nível de educação do cliente.
- **Marital_Status**: Estado civil do cliente.
- **Income**: Renda anual do cliente.
- **Kidhome**: Número de crianças na casa do cliente.
- **Teenhome**: Número de adolescentes na casa do cliente.
- **Dt_Customer**: Data de cadastro do cliente.
- **Recency**: Número de dias desde a última compra do cliente.
- **MntWines**: Gasto em vinhos nos últimos 2 anos.
- **MntFruits**: Gasto em frutas nos últimos 2 anos.
- **MntMeatProducts**: Gasto em carnes nos últimos 2 anos.
- **MntFishProducts**: Gasto em peixes nos últimos 2 anos.
- **MntSweetProducts**: Gasto em doces nos últimos 2 anos.
- **MntGoldProds**: Gasto em produtos de ouro nos últimos 2 anos.
- **NumDealsPurchases**: Número de compras com desconto.
- **NumWebPurchases**: Número de compras pela web.
- **NumCatalogPurchases**: Número de compras por catálogo.
- **NumStorePurchases**: Número de compras em loja.
- **NumWebVisitsMonth**: Número de visitas ao site nos últimos 30 dias.
- **AcceptedCmp1**: 1 se a oferta na campanha 1 foi aceita, 0 caso contrário.
- **AcceptedCmp2**: 1 se a oferta na campanha 2 foi aceita, 0 caso contrário.
- **AcceptedCmp3**: 1 se a oferta na campanha 3 foi aceita, 0 caso contrário.
- **AcceptedCmp4**: 1 se a oferta na campanha 4 foi aceita, 0 caso contrário.
- **AcceptedCmp5**: 1 se a oferta na campanha 5 foi aceita, 0 caso contrário.
- **Complain**: 1 se o cliente fez uma reclamação nos últimos 2 anos, 0 caso contrário.
- **Z_CostContact**: Custo de contato (valor fixo).
- **Z_Revenue**: Receita (valor fixo).
- **Response**: 1 se o cliente aceitou a última campanha, 0 caso contrário.

## Etapas da Análise

### 1. Exploração e Limpeza dos Dados

- Carregamento do dataset.
- Verificação e tratamento de valores ausentes.
- Visualização e análise das distribuições das variáveis principais.

### 2. Cálculo dos Índices RFM

- Recency (Recência): Tempo desde a última compra.
- Frequency (Frequência): Número de compras realizadas.
- Monetary (Monetário): Valor gasto pelo cliente.

### 3. Segmentação dos Clientes

- Segmentação dos índices RFM em quartis.
- Cálculo do score RFM para cada cliente.
- Análise descritiva dos segmentos RFM.

### 4. Análise da Resposta às Campanhas de Marketing

- Cálculo da resposta às campanhas de marketing.
- Análise da resposta média às campanhas por segmento RFM.

## Resultados

Os resultados da análise mostram que clientes com scores RFM mais altos tendem a ser mais valiosos e mais receptivos às campanhas de marketing. A análise ajudará a direcionar campanhas de marketing mais eficazes para diferentes segmentos de clientes.

## Como Utilizar

Para reproduzir a análise, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```
3. Instale as dependências necessárias (assumindo que você tem o `pip` instalado):
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
4. Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. Execute o notebook `analysis.ipynb` para ver a análise completa.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 📞 Contato

Se você quiser entrar em contato comigo ou acompanhar meu trabalho, aqui estão algumas maneiras de fazer isso:

- **Email:** arthuraraujo07@hotmail.com
- **GitHub:** [ragnarthur](https://github.com/ragnarthur)
- **Instagram:** [@arthuraraujo07](https://instagram.com/arthuraraujo07)
