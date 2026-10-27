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

Regressão Polinomial --> Executa o modelo de Regressão Polinomial como um algoritmo de previsão para uma série temporal de fechamento de preço de energia elétrica (Dataset2.csv), o qual emprega o mês mais antigo como ajuste do modelo e os dias do mês mais recente como alvos da previsão.

Dataset3 --> Contém dados de fechamento de ativo de mercado financeiro com discretização diária (cerca de 11 anos).

Regressão LASSO --> Executa o modelo de Regressão Linear com Regularização LASSO como um algoritmo de previsão para uma série temporal de fechamento de ativo no mercado financeiro (Dataset3.csv), o qual emprega os anos mais antigos como ajuste do modelo e os anos mais recente como alvos da previsão.

Dataset4 --> Contém dados de preço de energia elétrica horários (cerca de 2 meses), porém com Dados Faltantes (Missing Data).

AnaliseDadosFaltantes --> Faz distintos tratamentos de dados faltantes no preço de energia elétrica (Dataset4.csv).

SelecaoFeatures --> Faz uma análise de lags do preço da energia elétrica (Dataset4.csv) em função de ACF, PACF e Matriz de Correlação para compreender como essas ferramentas auxiliam na seleção de features na previsão de séries temporais.

ExtracaoSelecaoFeatures_MediaMovel --> Realiza o cálculo de Média Móvel como forma de extrair features do preço da energia elétrica (Dataset4.csv) e análise tanto a Matriz de Correlação quanto os indicadores MAE, RMSE e R2 em relação ao desempenho de modelos preditivos.
