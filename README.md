# 🚌 Análisis de ocupación y factores asociados en transporte de pasajeros
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre una empresa de transporte intermunicipal de pasajeros (vehículos de 9 puestos, una ruta ida y regreso).  Se busca entender los patrones de ocupación, el impacto de días festivos y fines de semana, y la relación con condiciones climáticas.

# 📂 Contenido del repositorio

- TABLA_FINAL.xlsx → dataset procesado y limpio.
- scripts/ → notebooks y scripts en Python usados para el análisis.
- Informe_Ocupacion_Transporte_Graficos.pptx → presentación ejecutiva con gráficos y recomendaciones.
-README.md → este documento.

# ⚙️ Tecnologías usadas

- Python 3.11
# Librerías:
- pandas → limpieza y análisis de datos
-matplotlib → visualizaciones
- numpy
- holidays
- openmeteo_requests
- seaborn

# 📊 Principales hallazgos

- Ocupación promedio: 85.6%
- Sobrecupo detectado: hasta 133%
- Mayor demanda: tardes (16:00–18:00), fines de semana y festivos
- Menor demanda: noches (21:00–22:00)

# Clima: 
- tormentas y lluvias moderadas reducen la ocupación (~80%), pero la temperatura no influye significativamente.

# 💡 Recomendaciones

- Reforzar flota en tardes, fines de semana y festivos.
- Reducir o reorganizar salidas de baja demanda nocturna.

Implementar controles para prevenir sobrecupo.

Diseñar estrategias de comunicación para pasajeros en condiciones de clima adverso.
