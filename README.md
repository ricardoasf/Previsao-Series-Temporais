# Previsão de Séries Temporais
Esse repositório traz scripts Python (feitos para Jupyter Notebook), os quais podem ser executados via Google Colab. Todos os scripts são destinados à previsão de séries temporais relacionados à Comercialização de Energia Elétrica.

Dataset1 --> Contém dados de preço de energia elétrica horários (cerca de 2 meses)

MediaMovel --> Executa uma suavização por média móvel para uma série temporal de preço de energia elétrica (Dataset1.csv) e também executa a Média Móvel (MA) como um algoritmo de previsão, o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

Autoregressivo --> Executa executa o modelo Autoregressivo (AR) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

ARMA --> Executa executa o modelo Autoregressivo de Média Móvel (ARMA) como um algoritmo de previsão para uma série temporal de preço de energia elétrica (Dataset1.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

ACF_PACF --> Executa análises da série temporal de preço de energia elétrica (Dataset1.csv) com o intuito de melhor guiar a parametrização de modelos MA, AR e ARMA.
