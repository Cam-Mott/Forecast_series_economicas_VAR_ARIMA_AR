# Forecast_series_economicas_VAR_ARIMA_AR
## **Introducción**
---
EMAE (Estimador Mensual de Actividad Económica), IS (Índice de Salarios) e IPC (Índice de Precios al Consumidor) son 3 variables que pueden aportar mucha información sobre la economía de un país: indican el desempeño de la actividad económica en general, la dinámica de los salarios y el comportamiento de los precios de bienes y servicios. Reesulta entonces de interes analizar y evaluar la construcción de modelos de series de tiempo que permitan anticipar su comportamiento futuro. Si bien el foco se centrara el predecir el IPC, en el presente repositorio se abordan los famosos modelos VAR, ARIMA y AR, la capacidad predictiva de cada uno, sus limitaciones y supuestos. El objetivo en sí no es construir un modelo óptimo; se busca presentar las series de tiempo, el funcionamiento de los modelos y algunas de las pruebas que podemos realizar sobre los mismos a fin de determinar si resultan adecuados o no.

## **Dataset**
---
Se trabajar con las variaciones porcentuales del EMAE, IS e IPC, equivalentes al crecimiento económico, el incremento de salarios y la inflación respectivamente. Los datos provienen del INDEC y sobre los mismos se calcularon las variaciones porcentuales. El periodo trabajado va desde el 02/2004 al 02/2010, constituyendo un total de 73 registros. Tras importar los datos, se trabaja el dataset para aislar el componente estacional de las series, a fin de evaluar posteriomente su estacionariedad.

## **Test de hipótesis y métricas**
---

Se realizaron 3 test de hipótesis: Test Dickey-Fuller Aumentado para determinar la estacionariedad de las series, Test de Granger para determinar la causalidad entre variables y Test de hipótesis sobre coeficientes del modelo ARIMA, para determinar si los mismos eran o no diferentes a 0. Por otra parte, también se construyeron las métricas MAPE, RMSE y MAE para evaluar y comparar la calidad predictiva de cada uno de los modelos. 

Todas las pruebas y métricas se presentan numérica y gráficamente, a fin de visualizar y comparar las salidas con mayor facilidad.

<img width="1360" height="296" alt="image" src="https://github.com/user-attachments/assets/7afc24c1-a222-4819-a0a8-c828bc2cf4dc" />




