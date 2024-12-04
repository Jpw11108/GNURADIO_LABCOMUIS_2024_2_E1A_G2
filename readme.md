# Análisis de Emisoras FM

## Inciso A: Análisis de Emisoras

Se realizó un listado de las emisoras recibidas en el equipo, registrando la información contenida en la señal banda base demodulada. 
![banda base](https://github.com/nicolasve18/GNURADIO_LABCOMUIS_2024_2_E1A_G2/blob/practica_4/practica_4/Captura%20de%20pantalla%202024-12-04%20165340.png)
Con base en el **Plan Técnico de Radiodifusión Sonora para FM**, se verificó si alguna emisora no cumplía con el ancho de banda permitido para su categoría. Para esto, se compararon los valores obtenidos con los estándares establecidos. En algunos casos, se identificaron emisoras cuya modulación se encontraba fuera de los límites del ancho de banda permitido.





## Inciso B: Análisis del Ancho de Banda en Pasabanda

### Medición de Ancho de Banda
Utilizando un **analizador de espectro**, se midió el ancho de banda de las emisoras en pasabanda. Las mediciones se realizaron en un rango adecuado y se registraron los valores correspondientes con los resultados obtenidos mediante el **analizador de espectro** fueron comparados con los datos de ancho de banda calculados en **GNU Radio**. 

Se observó algo curioso que se mencionaba en la teoría al modificar el factor KapAm. Al hacerlo, la señal mantenía una amplitud constante, pero presentaba un comportamiento similar al de un acordeón. Esto se debía a que al modificar el KapAm , la frecuencia de la señal variaba, lo que generaba esa sensación visual. como se ve en la imagen
![señal variando el kpAm](https://github.com/nicolasve18/GNURADIO_LABCOMUIS_2024_2_E1A_G2/blob/practica_4/practica_4/SCR03.PNG)

## conclusion:
## conclusion:
Se observó que algunas emisoras no cumplen con el ancho de banda reglamentario y utilizan más del permitido. Como resultado, en ciertas áreas del espectro, las emisoras causan interferencias entre sí.

Al calcular los coeficientes de Bessel, se observó una diferencia entre los valores teóricos y los obtenidos en el laboratorio. Esta discrepancia se atribuye a varias razones, como las imperfecciones al generar la señal en GNU Radio, así como las pérdidas y atenuaciones causadas por el cableado y el propio analizador de frecuencia.
se vio que al se una señal de banda estrecha  osea con un kpAm menor a 0,2 se puede analizar como si estuviera modulada por amplitud facilitando los calculos.
