# Dashboard de desempeño comercial 2024-2025: Andes Retail Group

Proyecto guiado del programa de Análisis de Datos de TripleTen (Sprint 10), hecho en Power BI. El caso y los datos vienen del curso. La preparación de los datos, el diseño del dashboard, la narrativa y las recomendaciones son míos.

## De qué trata

Andes Retail Group vende en Perú, Chile y Colombia. El objetivo es construir un dashboard de dos vistas que muestre cómo evoluciona el negocio entre 2024 y 2025 y comunicar el hallazgo principal con el modelo SCQA (Situación, Complicación, Pregunta y Respuesta) y un mensaje corto para stakeholders.

<!-- Agrega aquí capturas del dashboard, por ejemplo:
![Overview](capturas/overview.png)
![Detalle](capturas/detalle.png)
-->

## Qué incluye

- Preparación de datos en Power BI: formato de fecha en español, tipos de dato, columna condicional `Nivel_Venta` (venta alta si los ingresos son de 1,000 o más) y columnas de ganancia y margen.
- Vista Overview: KPIs de ingresos, ganancia, margen y unidades vendidas, ticket promedio por año y comparaciones por país, categoría y segmento de cliente.
- Vista de análisis detallado: ingresos por temporada, evolución en el tiempo, ingresos y ganancia por categoría, segmentos de cliente y tabla de pedidos por cliente, con segmentadores de año, país, región, categoría y segmento.
- Documento de planeación en el notebook: preguntas por vista, KPIs, tipos de gráfico, jerarquía visual y filtros.

## Hallazgos

- Entre 2024 y 2025 se vendieron $5.5M, con ganancia de $1.94M y margen cercano a 35 %.
- Los ingresos cayeron 6.8 % de 2024 a 2025 ($2.86M a $2.67M) y el ticket promedio bajó de $1,123 a $1,089. El margen se mantuvo plano.
- La caída se concentra en verano (-$203K, -16.6 %). El segmento Premium explica cerca de 83 % de esa caída, sobre todo en Perú (-23 %) y Chile (-17.5 %), y en las categorías Deportes (-26 %) y Ropa (-22 %). Hogar creció.
- Recomendación: un plan de reactivación de clientes Premium para el verano 2026, enfocado en Perú y Chile y con ofertas en Deportes y Ropa.

## Contenido del repositorio

- `Proyecto-Desempeno-Comercial-AndesRetail.ipynb`: documentación del proceso, la planeación, la narrativa SCQA y el mensaje para Slack.
- Archivo del dashboard (`.pbix`): [enlace](https://TU-ENLACE-AL-PBIX).

## Herramientas

Power BI Desktop, Power Query y DAX.

## Autor

Cuauhtli Iancuic Galindo Alcantara
