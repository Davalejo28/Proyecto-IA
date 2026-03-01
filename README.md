# Proyecto-IA

Predicción del Empleo Informal en Colombia mediante Machine Learning (GEIH – 2025)
Integrantes:
David Castiblanco, Juan Diego Villabon, Alejandro Velandia 
________________________________________Objetivo:
Desarrollar un modelo predictivo que permita estimar la probabilidad de que un trabajador en Colombia se encuentre en condición de informalidad laboral, utilizando microdatos oficiales de la Gran Encuesta Integrada de Hogares (GEIH) del Departamento Administrativo Nacional de Estadística para el período 2015–2023, integrando variables macroeconómicas y características individuales.
________________________________________Descripción:
La informalidad laboral representa uno de los principales desafíos estructurales del mercado laboral colombiano. Más del 50% de los ocupados no cuentan con acceso pleno a seguridad social, lo que afecta la productividad, el recaudo fiscal y la protección social.
El proyecto propone aplicar técnicas de Machine Learning para identificar los determinantes de la informalidad y construir un modelo que permita predecir a nivel individual. A diferencia de los análisis descriptivos tradicionales, este enfoque permitirá:
1)Identificar patrones complejos entre variables.
2)Estimar probabilidades individuales.
3)Medir la importancia relativa de los factores explicativos.
El estudio combinará microdatos laborales con variables macroeconómicas como el crecimiento del PIB y la tasa de intervención del Banco de la República.
________________________________________Desafíos
1)Procesamiento y limpieza de grandes volúmenes de microdatos.
2)Definición rigurosa de informalidad según metodología DANE.
3)Posible multicolinealidad entre variables macroeconómicas.
4)Manejo de desbalance de clases.
5)Incorporación de rezagos económicos (efecto no inmediato del PIB o tasas).
________________________________________
Entrega de Valor
1.	El proyecto generará:
2.	Un modelo predictivo replicable.
3.	Identificación de factores clave de riesgo.
4.	Evidencia para diseño de políticas públicas laborales.
5.	Herramienta académica aplicable a otros mercados emergentes.
Valor económico claro:
1.	Mejor focalización de políticas de formalización.
2.	Anticipación de deterioro laboral en fases recesivas.
3.	Apoyo a decisiones regulatorias.
________________________________________
Stakeholders
Entidades públicas:
1.	Departamento Administrativo Nacional de Estadística
2.	Ministerio de Trabajo
3.	Banco de la República
4.	Departamento Nacional de Planeación
Sector privado:
1.	Centros de investigación
2.	Consultoras económicas
3.	Organismos multilaterales
________________________________________


Técnicas:
La metodología seguirá el enfoque CRISP-DM:
1.	Comprensión del negocio (mercado laboral colombiano).
2.	Comprensión y preparación de datos (GEIH).
3.	Modelamiento.
Modelos:
1.	Regresión Logística (benchmark econométrico).
2.	Random Forest.
3.	Gradient Boosting (XGBoost).
Evaluación:
1.	Accuracy
2.	Precision y Recall
Se utilizarán técnicas de interpretabilidad (importancia de variables y SHAP).
________________________________________
Fuentes de Datos
Fuente principal:
●	Microdatos GEIH – Departamento Administrativo Nacional de Estadística.
Fuentes complementarias:
●	PIB real – Departamento Administrativo Nacional de Estadística.
●	Tasa de intervención – Banco de la República.
●	Tasa de desempleo nacional.
Todas las fuentes son oficiales y de acceso público.
________________________________________
Variables
Variable Dependiente
●	Condición de informalidad (1 = informal, 0 = formal).
________________________________________
Variables Macro
roeconómicasPIB (crecimiento real anual)
Se utiliza para capturar el ciclo económico. Se espera que en periodos de expansión disminuya la probabilidad de informalidad, mientras que en recesión aumente.
Tasa de desempleo
Indicador de presión en el mercado laboral.
Tasa de intervención del Banco de la República
Refleja el costo del crédito y la postura monetaria.
________________________________________
Variables Individuales
Demográficas
●	Edad
●	Sexo
●	Región
●	Zona (urbana/rural)
Educativas
●	Nivel educativo
●	Años de escolaridad
Laborales
●	Rama de actividad
●	Tamaño de empresa
●	Ingreso laboral
●	Tipo de ocupación
