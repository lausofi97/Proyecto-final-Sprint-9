# Experimento A/B | Conversión y gasto en una landing page

**Autora:** Laura Sofía Arias González  
**Tipo:** Proyecto académico de análisis de datos — TripleTen  
**Herramientas:** Python · pandas · scipy · statsmodels · seaborn · matplotlib

## Resumen ejecutivo

Evalué dos versiones de una página con pruebas de medias, proporciones y asociación para sustentar una recomendación de producto.

## Pregunta de negocio

¿Qué versión de la landing page muestra mejor desempeño de conversión y gasto entre usuarios convertidos?

## Proceso de análisis

1. Validación de datos y comparación de los grupos A y B.
2. Prueba t independiente para gasto entre usuarios convertidos.
3. Prueba Z para comparar proporciones de conversión.
4. Pruebas chi-cuadrado para fuente de tráfico y tipo de usuario frente a conversión.
5. Comparación de volúmenes y tasas, evitando confundir canales grandes con canales más efectivos.

## Hallazgos principales

- Versión A: 2.512 conversiones / 19.982 usuarios ≈ 12,57 %. Versión B: 3.194 / 20.018 ≈ 15,96 %.
- La diferencia observada es ≈ +3,38 puntos porcentuales a favor de B; mejora relativa ≈ 26,9 %. Es un resultado del experimento académico, no un impacto implementado.
- La prueba Z bilateral reporta p ≈ 3,76 × 10⁻²².
- El gasto promedio entre convertidos fue ≈ 61,09 en A y 68,75 en B; prueba t reportada p ≈ 1,06 × 10⁻²⁰.
- La fuente de tráfico presenta asociación con conversión (p ≈ 0,034); para tipo de usuario no se obtuvo evidencia suficiente (p ≈ 0,474).

## Recomendación

Priorizar B como candidata a despliegue, sujeto a verificar asignación experimental, métricas de control e impacto práctico.

## Ver el análisis

[Notebook del proyecto](https://github.com/lausofi97/Proyecto-final-Sprint-9/blob/main/S9%20Version_Student_Proyecto_Landing_Experiment%20%281%29.ipynb)

## Alcance y limitaciones

- El gasto se compara entre quienes convirtieron; no es gasto medio de todos los usuarios ni ticket promedio de pedidos.
- Antes de una decisión real se deben comprobar independencia, aleatorización, balance de muestra, duración y posibles comparaciones múltiples.
- Las asociaciones de tráfico no demuestran que cambiar el canal cause una mejora.


## Cómo ejecutar el proyecto

1. Descarga el notebook de este repositorio.
2. Ábrelo en Google Colab.
3. Sube el archivo `landing_experiment.csv` al entorno de Colab.
4. Comprueba que la carga del dataset utilice esta ruta:
   `/content/landing_experiment.csv`
5. Ejecuta las celdas en orden y revisa los resultados.

El dataset no está incluido en este repositorio. Para repetir el análisis necesitas disponer del archivo utilizado en el proyecto académico.

## Contacto

[LinkedIn](https://www.linkedin.com/in/laura-sofia-arias) · [GitHub](https://github.com/lausofi97)
