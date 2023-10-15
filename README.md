# Limpieza de Dataset para Análisis de Datos

Una de las tareas más cruciales en la ciencia de datos es la preparación y limpieza del conjunto de datos. En esta actividad, realizamos una exhaustiva limpieza del dataset para mejorar la calidad de los datos y permitir un análisis y modelado más preciso.

## Dataset Inicial

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/1c6f909b-9daf-4890-8548-5b64fa9f8eae)

El dataset inicial presentaba varios problemas y errores que requerían atención:

### Errores Identificados

**Error 1, 2 y 3:** Se eliminaron las variables "Range," "State" y "City" debido a problemas de calidad de datos. La variable "Range" contenía 10051 valores nulos, mientras que la variable "State" tenía 10048 valores iguales a "CA," y los 3 restantes eran nulos. La variable "City" generaba ruido en los datos con entradas como "SAN FRANCISCO" en mayúsculas, "S" (que no es una ciudad), "Treasure Island" (que no es una ciudad), "Yerba Buena" (que no es una ciudad), entre otros.

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/d949b049-7fcb-462e-b22b-a2910749ac0e)

**Error 4:** En la variable "AddressType," se identificaron 3 valores numéricos (1) que no correspondían al tipo de dato de la variable. Se eliminaron las filas que contenían estos datos numéricos incorrectos.

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/9bc7d045-efcf-48cd-b18c-6d4fd097dc8a)

**Error 5:** La variable "AgencyId" tenía 10048 atributos iguales a 1, lo que no aportaba valor al dataset. Se optó por eliminar esta variable.

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/f06e355c-26d2-42bf-a682-0b7a1736be2e)

**Error 6:** La variable "CrimeId" tenía 2 valores que se repetían 3 veces, lo que era inconsistente. Estos duplicados se eliminaron, garantizando que cada instancia tuviera un valor único.

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/a408129d-bcd5-4d42-bfad-53bbaab53551)

## Resultados en el Dataset Final

La limpieza y preparación del dataset permitieron obtener un conjunto de datos más limpio y apto para análisis y modelado de datos. Estos esfuerzos mejoraron la calidad de los datos, lo que se traducirá en resultados más precisos en futuros análisis y modelos.

![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/9698ead7-b9af-432b-bf0c-a8fd0d26c5bd)
![image](https://github.com/jolosjoel/Limpieza-de-Dataset/assets/45809759/3f17b9af-8e6b-4a30-8a42-0639cde79371)



