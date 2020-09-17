# __*CHILD MORTALITY RATE*__
# 1.- INTRODUCCIÓN
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Foto_Presentaci%C3%B3n.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo15_Graficas_Rate_Mort_Child.png?raw=true)

# 2.- OBJETIVO
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Diagrama_M%C3%A9tricas.png?raw=true)

![Enlace Indicadores "Who_Rate_Mortality_Child"] (https://apps.who.int/gho/data/view.main.CM1300R?lang=en)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Def_M%C3%A9trica_Child_Mortality.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo15_Graficas_Rate_Mort_Child_2010-2017.png?raw=true)

# 3.- DEFINICIÓN MÉTRICAS PREDICTORAS

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

# 4.- ESTIMACIÓN DE NAs

# 5.- MÉTODOS de REGRESIÓN APLICADOS basados en la "SELECCIÓN DE MODELOS"
> Permiten seleccionar automáticamente la mejor combinación de variables predictoras para construir un modelo predictivo óptimo.

## 5.1- REGRESIÓN PENALIZADA.
Modelos aplicados:
###### .- CRESTA
###### .- LASSO
###### .- NET ELASTIC
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Encabezado.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Analisis_Reg_Penalizada1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo1_Analisis_Reg_Penalizada2.png?raw=true)

## 5.2- REGRESIÓN STEPWISE
Modelos aplicados:
###### .- LeapBackward(Selección hacia atrás)
###### .- LeapForward(Selección hacia delante)
###### .- LeapSeq(Selección por pasos)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo2_Analisis_Reg_STEPWISE1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo2_Analisis_Reg_STEPWISE2.png?raw=true)

## 5.3- REGRESIÓN basada en COMPONENTES PRINCIPALES:
Modelos aplicados:
###### .- PCR(Regresión de componentes principales)
###### .- PLS(Regresión de Mínimos cuadrados parciales)

![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo4_Analisis_PCR.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo4_Analisis_PLS.png?raw=true)

## 5.4- REGRESIÓN "REGSUBSETS":
Modelos aplicados:
###### .- Regsubsets (Subconjuntos)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Analisis_REGSUBSETS1.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo3_Analisis_REGSUBSETS2.png?raw=true)


## 6.- MACHINE LEARNING Supervised:
Algoritmos aplicados:
###### .-K-Nearest Neighbors (KNN)
###### .-Random Forest (RF)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo5_Analisis_KNN.png?raw=true)
![GitHub Logo](https://github.com/MaripiPerea/TFM_KSchool/blob/master/Diapo5_Analisis_Ramdom_Forest.png?raw=true)

