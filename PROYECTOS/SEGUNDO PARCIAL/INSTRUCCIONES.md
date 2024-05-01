# PROYECTO DEL SEGUNDO PARCIAL

En la carpeta SEGUNDO PARCIAL se encuentra anexado el archivo mora_cdto.csv para el trabajo del parcial. Su trabajo consiste en realizar el mejor algoritmo para clasificación del dataset.

## Descripción del caso

El banco Omega ha observado un aumento en el número de clientes que entran en mora en sus pagos de tarjeta de crédito, lo que ha llevado a una disminución de sus ganancias. La entidad financiera desea entender las razones detrás de la mora de sus clientes y detectar los factores que influyen para determinar si una deuda será pagada o no.
Para lograr este objetivo, el banco decide utilizar técnicas de análisis de datos y aprendizaje automático para procesar una gran cantidad de datos de clientes, incluyendo información personal, historial crediticio, patrones de gasto y pagos, entre otros. A partir de este análisis, el banco busca identificar los factores que podrían estar influyendo en la mora de sus clientes y construir un modelo de clasificación que permita determinar si un cliente en particular pagará su deuda a tiempo o no.

El banco tiene acceso a información personal de los usuarios, recopilada a lo largo de su relación comercial, y la información e historial de pagos de los últimos 6 meses (octubre 2023 – marzo 2024). Las características de la data se detallan a continuación:

•	ID: ID del cliente
•	CU: Cupo máximo de la tarjeta de crédito
•	G: Género del cliente. (M = Masculino, F = Femenino, O = Otros).
•	ED: Nivel de instrucción educativa (1 = primaria, 2 = universidad, 3 = secundaria, 4 = otros).
•	EC: Estado civil del cliente. (Soltero, Casado, Otros)
•	E: Edad del cliente.
•	M1 – M6: Historial de pago previo. M1 = historial de pago (marzo 2024), M2 = historial de pago (febrero 2024), …, M6 = historial de pago (octubre 2023). El historial de pago se define: -1 = paga debidamente, 1 = retraso en el pago por un mes, 2 = retraso en el pago por dos meses, ..., 8 = retraso en el pago por ocho meses, 9 = retraso en el pago por nueve meses o más.
•	D1 – D6: Monto del estado de cuenta. D1 = monto del estado de cuenta (marzo 2023), D2 = monto del estado de cuenta (febrero 2024), …, D6 = monto del estado de cuenta (octubre 2023). El monto del estado de cuenta se encuentra descrito en dólares americanos.
•	P1 – P6: Monto del pago previo. P1 = monto pagado (marzo 2024), P2 = monto pagado (febrero 2024), …, P6 = monto pagado (octubre 2023).
•	SP: Próximo pago en mora. (Si, No)


## Entregables

### Informe sobre el desarrollo del trabajo (.pdf)
Documento en formato artículo (Se anexa ejemplo). Extensión máxima: 3 hojas.
### Notebook de Python (.ipynb)
Código en el que se muestre todo el trabajo desarrollado. Use adecuadamente las secciones de código y de texto. 
-Aplicar técnicas de aprendizaje automático no lineal para resolver problemas de ingeniería mecatrónica, justificando la selección de modelos y técnicas específicas (modelos de Ensamblaje)
### Archivo del mejor modelo entrenado
Archivo en cualquiera de los formatos posibles.
Más información: https://machinelearningmastery.com/save-load-machine-learning-models-python-scikit-learn/ 

## Evaluación del componente práctico (100%)
### Modelo entrenado (30%)
La exactitud más alta alcanzada en el conjunto de validación, por cualquier equipo del curso, será el referente para el máximo de la nota. El resto de valores logrados por los demás estudiantes se ponderarán de acuerdo a esta lógica. 
Ponderación: 
Funciona - 30%   
No funciona - 15%
### Evaluación del modelo (20%)
El modelo deberá evaluarse mediante la selección adecuada de métricas específicas para el caso. Esta selección deberá estar claramente detallada en el artículo y se deberá realizar una adecuada interpretación de los resultados obtenidos en las métricas.
Ponderación: 
Selección de la métrica e interpretación adecuada - 20%
Selección de la métrica o interpretación adecuada - 10%
Selección inadecuada de la métrica o nula interpretación del resultado - 5%
### Artículo (20%)
Presentación del artículo en el formato solicitado. 

### Notebook de Python (30%)
Originalidad del código presentado. Código y explicación del desarrollo de la solución.

# Evaluación del componente: Gestión del aprendizaje P2 (12%)
## Caso práctico - 60%
## Examen teórico - 40%


¡Éxitos en su trabajo!
