# Telecom-X-2

## Duración del contrato según cancelación
De acuerdo al análisis de datos, la mediana en la que se encuentra la cantidad del número de contratos cancelados, se encuentra aproximadamente en 10 meses, mientras que la mediana de la cantidadd de contratos que no han sido cancelados se encuentra aproximadamente en 38 meses. Lo anterior indica que aquellos clientes que tienen menos de un año de servicio cancelan, mientras que aquellos que ya superaron tres años de servicio es poco probable que cancelen posteriormente. 

## Regresión logística para predecir la cancelación de los clientes
Acorde con los resultados del modelo de regresión logística, 1115 clientes fueron clasificados de manera correcta de acuerdo al estado de su contrato (923 cancelaron y 192 no cancelados). De igual forma, el modelo clasificó correctamente el 79% de los casos, lo cual indica que tiene una buena consistencia entre la cantidad de contratos no cancelados, mientras que en el caso de los contratos cancelados, únicamente el 51% fue clasificado correctamente, lo cual no es suficientemente adecuado. 

## Árbol de decisión
En este segundo modelo, únicamente 1024 contratos fueron clasificados de acuerdo al contrato, es decir, cancelado o no cancelado. Además, acertó en el 73% de los casos, lo cual es inferior al modelo previo. A pesar de esto, el modelo tuvo entre un 80 y 81% de precisión para los contratos no cancelados, mientras que únicamente acertó en el 50% de los casos de cancelación.

## Support Vector Machine (SVM)
Finalmente, el modelo SVM, el cual predice si un cliente va a cancelar o no, identificó correctamente 1149 casos como cancelados y no cancelados con una precisión del 73%. Además, es bueno para poder predecir a los clientes que no cancelan, con un 91% de precisión, mientras que en el caso de los clientes que sí cancelan, el modelo tuvo una precisión del 64%. 

## Recomendaciones finales
Como en el challenge anterior, se recomienda que la empresa de telecomunicaciones emplee programas que favorezcan la adherencia al servicio de manera oportuna, específicamente, enfocando la atención en la seguridad en línea, el pago y cargo mensual, así como mantener una relación costo-beneficio entre las características del servicio y el cobro que se hace. De igual manera, se insta a que la empresa permita cargos y costos con nuevos planes que favorezcan y aporten nuevos beneficios además de los ya establecidos de manera actual. Al mismo tiempo, algo interesante encontrado es una relación positiva entre el soporte técnico y las características del servicio brindado. 
