# Prueba-T-cnica-Tuya-S.A.
Prueba técnica para vacante de Analista de Datos. Fases: SQL, Productividad y Segmentación.
Este repositorio contiene la solución completa a la prueba técnica para el cargo de **Analista de Datos**.

## Estructura del Proyecto
### Fase 1: SQL y Modelado Relacional
Se desarrollaron consultas SQL que permiten:
- Calcular órdenes y ventas por periodo.
- Identificar el cliente con la orden de mayor valor.
- Actualizar estructuras sin `ALTER TABLE`.

### Fase 2: Análisis de Productividad
Utilizando Power BI, se construyó un tablero para comparar cargos base:
- Métricas clave: Capturas por ejecutivo, productividad ajustada al costo, KPI.
- Análisis por antigüedad, región y canal.

### Fase 3: Segmentación (Machine Learning)
Se utilizó K-Means para clasificar puntos de venta:
- Variables: capturas, conversiones, tráfico, contribución.
- El número óptimo de clusters se definió con el método del codo.
- Resultados interpretados para recomendar tipos de ejecutivos por segmento.

### Fase 4: Presentación
El informe final incluye visuales, análisis integrados y recomendaciones estratégicas.

## Contenido
- `data/`: Datos utilizados
- `notebooks/`: Modelo de clustering con Python
- `dashboard/`: Dashboard de Power BI
- `presentacion/`: Informe PDF con resultados

## Requisitos
Para reproducir el modelo en python:
- Se debe realizar con Colab o VS Code



