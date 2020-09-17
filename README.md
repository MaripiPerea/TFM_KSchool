# __*CHILD MORTALITY RATE (probability of dying by age 5 per 1000 live births)*__
## __*1.- INTRODUCCIÓN*__
Desde 2000, las muertes infantiles se han reducido en casi la mitad y las muertes maternas en más de un tercio, debido principalmente a un mejor acceso a "servicios de salud" asequibles y de calidad, las mujeres y los bebés sobreviven y prosperan. Este es el poder de la **"cobertura sanitaria universal"**.

>__**"En todo el mundo, el nacimiento es una ocasión alegre. Sin embargo, cada 11 segundos, un nacimiento es una tragedia familiar"**__

>__**"Un par de manos especializadas para ayudar a las madres y a los recién nacidos alrededor del momento del nacimiento, junto con agua limpia, nutrición adecuada, medicamentos básicos y vacunas, puede marcar la diferencia entre la vida y la muerte. Debemos hacer todo lo necesario para invertir en la cobertura sanitaria universal para salvar estas preciosas vidas"**__

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Foto_Presentaci%C3%B3n.png?raw=true)

La meta de los ODS(Objetivos de Desarrollo Sostenible) para poner fin a las muertes prevenibles de recién nacidos y niños menores de 5 años es reducir la mortalidad neonatal a al menos 12 por cada 1000 nacidos vivos y la __**mortalidad de menores de 5 años a al menos 25 por cada 1000 nacidos vivos**__. 

>__**.- En 2018, 121 países ya habían alcanzado esta tasa de mortalidad de menores de cinco años.**__ 

>__**.- Entre los 74 restantes, 53 países tendrán que acelerar los progresos para alcanzar la meta de los ODS en materia de supervivencia infantil para 2030.**__

Se puede observar en la gráfica evolutiva que las regiones mundiales que **han cumplido** el objetivo(desde el 2005) son: __**Europe, Americas y Western Pacific**__. 
Mientras que __**"South-East Asia"**__ está aproximándose, **"Eastern Mediterranean"** lo está casi duplicando. Y si hablamos de __**"África"**__ está todavía muy lejos de alcanzarlo, porque lo triplica.
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo15_Graficas_Rate_Mort_Child.png?raw=true)

## __*2.- OBJETIVO del ESTUDIO*__"
El objetivo principal del estudio es encontrar el mejor modelo para predecir la "Tasa de Mortalidad Infantil" por "Región Mundial", en base a indicadores de "Cobertura de Inmunización", del "Reglamento de Salud Internacional", "Ratio de Mortalidad por Causas", indicadores de "Malnutrición Infantil" relacionado con la "Anemia" y el "Bajo peso al nacer", así cómo también los relacionados con la "Salud Maternal" en edad reproductiva y en mujeres embarazadas, y con la "Mortalidad de las madres". Teniendo en cuenta también el indicador de la "Esperanza de vida al nacer" según el país de procedencia.

Es muy importante destacar que el indicador "Tasa de Mortalidad Infantil" es una probabilidad de muerte derivada de una tabla de vida y expresada cómo una tasa por 1000. Es decir, que no es una tasa estrictamente (número de muertes / población de riesgo), ni se obtiene de las "Tasas de Mortalidad infantil por Causas". Es evidente, que estas tasas serán muy influyentes en el modelo, pero la diversidad de "Regiones Mundiales" con su "variedad" de causas de mortalidad(12 en total), hará que el modelo seleccione las más "influyentes" para poder estimar cualquier Región de forma óptima.

Derivado de lo anterior, otro objetivo importante del estudio será identificar los principales indicadores que realmente están condicionando positiva o negativamente en el movimiento de la tasa. De cara a poder hacer "estimaciones futuras" del ratio, disponiendo solamente de los resultados de estas variables. Esto se consigue con los "Modelos de Selección" de variables cómo la "Regresión Penalizada", "Regresión por Pasos (Stepwise)" o "RegSubsets", dónde claramente hace una selección de "x variables predictoras" obteniendo su coeficiente asociado, que minimizan el "Error de predicción" o la "Tasa de Error".

En cambio, otros modelos cómo la "Regresión de Componentes Principales" (PCR y PLS) devuelve un modelo

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Diagrama_M%C3%A9tricas.png?raw=true)

![Enlace Indicadores "Who_Rate_Mortality_Child"] (https://apps.who.int/gho/data/view.main.CM1300R?lang=en)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Def_M%C3%A9trica_Child_Mortality.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo15_Graficas_Rate_Mort_Child_2010-2017.png?raw=true)

## __*3.- DEFINICIÓN MÉTRICAS PREDICTORAS*__

![Enlace Indicadores "Who_Anaemia_Woman"] (https://apps.who.int/gho/data/view.main.GSWCAH28REG)

![Enlace Indicadores "Who_Life_Expectancy"] (https://apps.who.int/gho/data/view.main.SDG2016LEXREGv?lang=en)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo7_Def_M%C3%A9trics_Women_Health_%20Life_Expectancy.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo12_Graficas_Life_Expectancy.png?raw=true)

![Enlace Indicadores "Who_Low_Weigth_birth"] (https://apps.who.int/gho/data/view.main.LBWWHOREGIONv)

![Enlace Indicadores "Who_Anaemia_children"] (https://apps.who.int/gho/data/view.main.ANEMIACHILDRENREGv)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo6_Def_M%C3%A9trics_Child_Malnutrition.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo11_Graficas_Malnutrition_Maternal.png?raw=true)

![Enlace Indicadores "Who_Mort_Children_Causes"] (https://apps.who.int/gho/data/node.main.ChildMortREG2002015?lang=en)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo6_Def_M%C3%A9trics_Causes_Child_Death.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo9_Graficas_Causes.png?raw=true)

![Enlace Indicadores "Who_Internat_Health_Regulations"] (https://apps.who.int/gho/data/view.main.IHRREGALLv?lang=en)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo5_Def_M%C3%A9trics_Internat_Health_Regulations.png?raw=true)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo10_Graficas_Regulations.png?raw=true)

![Enlace Indicadores "Who_Inmunization"] (https://apps.who.int/gho/data/node.main.A824?lang=en)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo4_Def_M%C3%A9trics_Immunization.png?raw=true)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo8_Graficas_Inm.png?raw=true)

## __*4.- ESTIMACIÓN DE VALORES "NAs"*__

## __*5.- MÉTODOS de REGRESIÓN APLICADOS basados en la "SELECCIÓN DE MODELOS"*__
> Permiten seleccionar automáticamente la mejor combinación de variables predictoras para construir un modelo predictivo óptimo.

### __*5.1- REGRESIÓN PENALIZADA*__
Modelos aplicados:
###### .- CRESTA
###### .- LASSO
###### .- NET ELASTIC
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Encabezado.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Analisis_Reg_Penalizada1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Analisis_Reg_Penalizada2.png?raw=true)

### __*5.2- REGRESIÓN STEPWISE*__
Modelos aplicados:
###### .- LeapBackward(Selección hacia atrás)
###### .- LeapForward(Selección hacia delante)
###### .- LeapSeq(Selección por pasos)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo2_Encabezado.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo2_Analisis_Reg_STEPWISE1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo2_Analisis_Reg_STEPWISE2.png?raw=true)

### __*5.3- REGRESIÓN basada en COMPONENTES PRINCIPALES*__
Modelos aplicados:
###### .- PCR(Regresión de componentes principales)
###### .- PLS(Regresión de Mínimos cuadrados parciales)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo4_Analisis_PCR.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo4_Analisis_PLS.png?raw=true)

### __*5.4- REGRESIÓN "REGSUBSETS"*__
Modelos aplicados:
###### .- Regsubsets (Subconjuntos)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Analisis_REGSUBSETS1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Analisis_REGSUBSETS2.png?raw=true)


### __*6.- MACHINE LEARNING Supervised*__
Algoritmos aplicados:
###### .-K-Nearest Neighbors (KNN)
###### .-Random Forest (RF)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo5_Analisis_KNN.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo5_Analisis_Ramdom_Forest.png?raw=true)

