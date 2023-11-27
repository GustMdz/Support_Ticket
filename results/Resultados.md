# Principales Resultados del Proyecto

A continuación, se exponen los resultados clave del proyecto, resaltando las visualizaciones y gráficos generados mediante bibliotecas como Altair. También se incluyen los hallazgos del análisis de texto, enriqueciendo la comprensión de la distribución geográfica de los clientes mediante la utilización de la librería GeoPandas.

## Análisis de Texto

### Análisis de Sentimiento

Se ha desarrollado una gráfica de barras que proporciona una rápida y clara comprensión de la naturaleza emocional de los títulos de los tickets de soporte.

- **Neutral (64%):** Predomina la categoría neutral, representando el 64% de los resultados. Esto sugiere que la mayoría de los clientes utiliza un lenguaje moderado al describir sus problemas.

- **Negativo (13%):** La presencia del 13% de títulos con etiquetas negativas indica que un segmento significativo de los clientes expresa problemas con un tono crítico o urgente.

- **Positivo (22%):** Aproximadamente el 22% de los resultados exhiben un lenguaje positivo, indicando que algunos clientes expresan sus problemas de manera optimista.

![Gráfica de Sentimiento](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Sentiment_bargraph.png)

Fuente: [Elaboración propia](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Sentiment_bargraph.png)

### Análisis Extendido del Sentimiento por Cliente

La siguiente gráfica de barras presenta el promedio del valor de los resultados de sentimiento para cada cliente.

- **Clientes con Títulos Positivos (Ejemplos):**
  - YREFY
  - FedEx
  - City of Fremont

Estos clientes destacan por tener títulos de tickets que, en promedio, expresan sentimientos positivos.

- **Clientes con Títulos Negativos (Ejemplos):**
  - Elsinore Valley Municipal Water District
  - City of Aspen and Pitkin County Colorado
  - Hernando County Florida

Por otro lado, estos clientes muestran, en promedio, títulos de tickets con sentimientos más negativos.

![Gráfica de Sentimiento por Cliente](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/sentimiento_Por_cliente.png)

Fuente: [Elaboración propia](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/sentimiento_Por_cliente.png)

### Wordcloud de Palabras Más Frecuentes en Títulos

Se ha creado una visualización con el Wordcloud de las palabras más frecuentes, ofreciendo una instantánea visual de las palabras clave dominantes en los títulos de los tickets de soporte.

![Wordcloud](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/wordcloud.png)

Fuente: [Elaboración propia](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/wordcloud.png)

### Gráfica de Barras de Palabras Más Utilizadas en Títulos

Con las palabras más frecuentemente utilizadas en los títulos de los tickets de soporte, se ha generado una gráfica de barras ordenada de mayor a menor frecuencia.

**Resumen de la Gráfica de Barras:**

1. **"Project"**
2. **"Change"**
3. **"Update"**
4. **"Status"**
5. **"Report"**
6. **"Workflow"**
7. **"Contract**
8. **Issue"**
9. **User**
10. **Item**

La visualización ordenada revela las palabras más comunes, permitiéndonos identificar rápidamente los temas dominantes en los títulos de los tickets de soporte.

![Gráfica de Barras de Palabras Más Utilizadas](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Top%2020%20Words%20by%20Frecuancy.png)

Fuente: [Elaboración propia](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Top%2020%20Words%20by%20Frecuancy.png)

### Extracción de Noun Chunks en Títulos

En el último paso de nuestro análisis de texto, se aplicó la extracción de Noun Chunks a los títulos de los tickets de soporte para identificar conceptos específicos que enriquecen el contenido semántico.

Los Noun Chunks más comunes:
1. **"Move Amount"**
2. **"Internal Item"**
3. **"Line Item"**
4. **"Punch List"**
5. **"Same Project"**
6. **"Change Order"**
7. **"Construction Daily Report"**
8. **"CPMS Prod"**
9. **"General Document"**
10. **"Task Order"**

![Extracción de Noun Chunks](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Top%2020%20Noun%20Chunks.png)

Fuente: [Elaboración propia](https://github.com/GustMdz/Support_Ticket/blob/main/data/Images/Top%2020%20Noun%20Chunks.png)
