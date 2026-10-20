# Previsão de Séries Temporais
Esse repositório traz scripts Python (feitos para Jupyter Notebook e Google Colab). Todos os scripts são destinados à previsão de séries temporais relacionadas à Comercialização de Energia Elétrica.

Dataset1 --> Contém dados de preço de energia elétrica horários (cerca de 2 meses)

MediaMovel --> Executa uma suavização por Média Móvel para uma série temporal de preço de energia elétrica (Dataset1.csv) e também executa a Média Móvel (MA) como um algoritmo de previsão, o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

Autoregressivo --> Executa o modelo Autorregressivo (AR) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

ARMA --> Executa o modelo Autorregressivo de Médias Móveis (ARMA) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

ACF_PACF --> Executa análises da série temporal de preço de energia elétrica (Dataset1.csv) com o intuito de melhor guiar a parametrização de modelos MA, AR e ARMA.

ARIMA --> Executa o modelo Autorregressivo Integrado de Médias Móveis (ARIMA) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

SARIMA --> Executa o modelo Sazonal Autorregressivo Integrado de Médias Móveis (SARIMA) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

Dataset2 --> Contém dados de demanda, dólar, geração eólica, balanço e preço de energia elétrica horários (cerca de 2 meses).

Regressão Linear --> Executa o modelo de Regressão Linear como um algoritmo de previsão para uma série temporal de demanda de energia elétrica (Dataset2.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

Regressão Ridge --> Executa o modelo de Regressão Linear com Regularização Ridge como um algoritmo de previsão para uma série temporal de demanda de energia elétrica (Dataset2.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.
