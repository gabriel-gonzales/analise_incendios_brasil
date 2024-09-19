# Análise dos Incêndios no Brasil em 2024

## Descrição do Projeto

Este projeto tem como objetivo analisar os incêndios florestais ocorridos no Brasil durante o ano de 2024. Foi utilizado dados climáticos e informações sobre o risco de fogo (FRP - Fire Radiative Power) para entender como fatores como dias sem chuva, precipitação e outras variáveis influenciam a incidência de incêndios.

O foco principal está na análise exploratória de dados (EDA) e visualização gráfica para identificar padrões regionais e temporais dos incêndios. A análise permite compreender melhor as regiões e os períodos mais suscetíveis ao fogo, oferecendo insights importantes para a prevenção de futuros incêndios.

## Estrutura do Projeto

- **Bibliotecas Utilizadas**:
    - `pandas`: Para manipulação de dados.
    - `matplotlib` e `seaborn`: Para visualizações gráficas.
    - `scikit-learn`: Para pré-processamento de dados e análise de componentes principais (PCA).
  
- **Principais Etapas**:
    1. **Carregamento dos Dados**: Os dados utilizados são distribuídos em três quadrimestres do ano de 2024, representando diversas variáveis climáticas e de risco de fogo por estado.
    2. **Tratamento dos Dados**: Tratamento de dados faltantes, verificação de outliers e normalização de variáveis.
    3. **Análise Exploratória (EDA)**: Visualizações para identificar padrões nas variáveis como dias sem chuva, precipitação e FRP, além de análise por estado e período.
    4. **Insights sobre Estados e Cidades**: Identificação de estados e regiões com maior incidência de fogo e variáveis que impactam mais diretamente os incêndios.

## Principais Descobertas

1. **Dias sem Chuva**: Esta foi a variável mais impactante no aumento do risco de incêndios florestais. Regiões que tiveram longos períodos de seca, como o estado de **Mato Grosso**, foram as mais afetadas.
   
2. **Precipitação**: Estados com maior índice de precipitação, como **Amazonas**, apresentaram uma queda significativa no risco de incêndios. Essa variável foi crucial para a mitigação dos incêndios.

3. **FRP (Fire Radiative Power)**: Embora significativo, o impacto do FRP no aumento de novos focos de incêndio foi pequeno. Estados como **Acre** apresentaram altos valores de FRP, mas o efeito sobre o aumento de novos incêndios foi limitado.

4. **Análise Temporal**: Durante o terceiro quadrimestre de 2024, observou-se um aumento significativo nos incêndios em estados como **Pará** e **Bahia**, correlacionado com longos períodos de estiagem.

## Como Executar o Projeto

1. **Executando no Kaggle**: 
    - O notebook foi desenvolvido para ser executado diretamente no Kaggle. Certifique-se de que os datasets de entrada estão disponíveis no ambiente Kaggle. Ao abrir o notebook, basta executar as células sequencialmente.

2. **Executando Localmente**:
    - Para executar em seu ambiente local, siga os passos:
      - Faça o download dos arquivos de dados CSV e ajuste os caminhos no código para apontar para os arquivos locais.
      - Instale as bibliotecas necessárias com o seguinte comando:
  
            pip install pandas matplotlib seaborn scikit-learn
        
      - Abra o notebook em um ambiente como Jupyter ou Google Colab e execute as células.

## Conclusão

O projeto revelou como fatores climáticos impactam significativamente a incidência de incêndios florestais no Brasil. Estados como Mato Grosso e Pará foram os mais afetados pelos períodos secos, enquanto a precipitação foi um fator decisivo para reduzir o risco em regiões como Amazonas. A análise dos dados climáticos oferece insights valiosos para a prevenção e controle de incêndios, ajudando a definir estratégias futuras de combate ao fogo.

## Fontes dos Dados

Os dados utilizados estão disponíveis na plataforma Kaggle e podem ser acessados diretamente no ambiente do notebook.

Disponível também em:

      www.kaggle.com/datasets/mayaravalliero/fire-watch-brazil-2024

