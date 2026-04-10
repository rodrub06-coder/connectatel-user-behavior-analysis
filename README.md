📊 ConnectaTel Customer Analysis
🚀 Overview

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre el comportamiento de usuarios de ConnectaTel, con el objetivo de identificar patrones de uso, segmentar clientes y generar insights accionables para negocio.

Se analizan variables clave como edad, número de mensajes, llamadas y minutos de uso, permitiendo entender cómo interactúan los usuarios con el servicio.

🎯 Objetivos
Limpiar y validar la calidad de los datos
Analizar el comportamiento de uso de los clientes
Segmentar usuarios por edad y nivel de actividad
Detectar patrones de consumo y outliers
Generar recomendaciones estratégicas para el negocio
🧹 Data Cleaning

Durante el análisis se identificaron y corrigieron problemas como:

Valores inválidos (sentinels como -999 y "?")
Fechas fuera de rango (años futuros)
Valores nulos
Datos estructuralmente faltantes

Esto permitió trabajar con un dataset confiable para el análisis.

📊 Análisis Exploratorio

Se realizaron:

Estadísticas descriptivas
Distribuciones (histogramas)
Boxplots para detección de outliers
Análisis por tipo de usuario
👥 Segmentación de Clientes
🔹 Por Edad
Joven: < 30 años
Adulto: 30–59 años
Adulto Mayor: 60+ años

👉 El segmento adulto representa el grupo más activo.

🔹 Por Nivel de Uso
Bajo uso: < 5 interacciones
Uso medio: 5–9
Alto uso: ≥ 10

👉 Predomina el uso medio, pero el alto uso genera mayor valor.

🔍 Hallazgos Clave
La mayoría de los usuarios presenta un uso moderado del servicio
Existen usuarios intensivos (heavy users) con alto consumo de minutos
Los outliers representan clientes valiosos, no errores
No hay una relación fuerte entre edad y tipo de plan
💡 Recomendaciones
🎯 Fidelizar usuarios de alto consumo (especialmente premium)
📈 Diseñar estrategias de upselling para usuarios de uso medio
📣 Implementar campañas segmentadas por edad
💰 Crear planes específicos para usuarios intensivos
🛠️ Tecnologías utilizadas
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
📁 Estructura del proyecto
├── data/
├── notebooks/
├── README.md
📌 Conclusión

Este análisis permite identificar oportunidades claras de negocio mediante la segmentación de clientes y el entendimiento de patrones de uso, facilitando la toma de decisiones estratégicas basadas en datos.

👨‍💻 Autor

Proyecto desarrollado como parte de formación en análisis de datos 📊
