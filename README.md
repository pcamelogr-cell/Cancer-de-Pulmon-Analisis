# Proyecto Final - Cancer de Pulmon

Este proyecto forma parte del curso Programación II, grupo G-IV.
En este proyecto analizaremos 800.000 historias reales de personas diagnosticadas con cáncer de pulmón, con el objetivo de comprender patrones de supervivencia y los factores que influyen en la mortalidad. Utilizaremos herramientas de estadística descriptiva, manejo de datos y visualización para realizar un análisis completo de esta enfermedad que afecta a millones de familias en todo el mundo.

Trabajaremos con Python (Pandas) y emplearemos GitHub para la colaboración entre los integrantes del proyecto.

Al analizar estos datos, no solo estamos estudiando un conjunto de información:
estamos aportando a la comprensión de una de las enfermedades más mortales en la historia de la humanidad.

## Integrantes

- Paula Camelo - Lider del Proyecto


## Estructura del Dataset

El conjunto de datos utilizado contiene 800.000 registros y 20 columnas, que incluyen información demográfica, clínica y de antecedentes médicos de pacientes diagnosticados con cáncer de pulmón.
El dataset cuenta con:
  Variables categóricas: género, país, etapa del cáncer, historial familiar, tipo de tratamiento.

  
  Variables numéricas continuas: edad, pack_years.

  
  Variables numéricas discretas: presencia o ausencia de enfermedades (COPD, diabetes, stroke, u otras) .


  
  Fechas importantes: fecha de diagnóstico y fecha de fin del tratamiento.
  

## Diccionario del Dataset

| **Columna**            | **Descripción**                                           | **Tipo de dato**            |
|------------------------|-----------------------------------------------------------|-----------------------------|
| **id**                 | Identificador único del paciente                          | Entero (discreta)           |
| **age**                | Edad del paciente                                         | Numérica continua           |
| **gender**             | Género del paciente                                       | Categórica                  |
| **country**            | País de origen del paciente                               | Categórica                  |
| **diagnosis_date**     | Fecha del diagnóstico de cáncer de pulmón                 | Fecha                       |
| **cancer_stage**       | Etapa del cáncer (I, II, III, IV)                         | Categórica ordinal          |
| **family_history**     | Historial familiar de cáncer (Sí/No)                      | Categórica binaria          |
| **smoking_history**    | Historial de tabaquismo                                   | Categórica                  |
| **pack_years**         | Años-fumador acumulados                                   | Numérica continua           |
| **copd**               | Enfermedad pulmonar obstructiva crónica                   | Binaria                     |
| **pneumonia**          | Antecedentes de neumonía                                  | Binaria                     |
| **diabetes**           | Diagnóstico de diabetes                                   | Binaria                     |
| **heart_disease**      | Enfermedad cardíaca                                       | Binaria                     |
| **stroke**             | Antecedente de accidente cerebrovascular                  | Binaria                     |
| **liver_disease**      | Enfermedad hepática                                       | Binaria                     |
| **kidney_disease**     | Enfermedad renal                                          | Binaria                     |
| **other_cancer**       | Otros cánceres previos                                    | Binaria                     |
| **treatment_type**     | Tipo principal de tratamiento recibido                    | Categórica                  |
| **end_treatment_date** | Fecha de finalización del tratamiento                     | Fecha                       |
| **survived**           | Estado final del paciente (1 = sobrevivió, 0 = falleció)  | Binaria                     |




## Cómo ejecutar
1. Activar entorno virtual: `source .venv/Scripts/activate`
2. Instalar dependencias: `pip install -r requirements.txt`



## Conclusiones


