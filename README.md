# Market-Regime-Classifier-with-Deep-Learning

SHerramienta de investigación cuantitativa de nivel institucional para la detección y modelado de regímenes de mercado mediante deep learning.

🚀 Descripción

Este proyecto implementa un sistema de clasificación de regímenes de mercado multi-activo basado en redes neuronales LSTM (Long Short-Term Memory), diseñado para capturar dependencias temporales no lineales en datos financieros.

El modelo procesa variables clave del mercado como:

Retornos logarítmicos
Volatilidad
Correlaciones entre activos

transformándolas en distribuciones probabilísticas de regímenes, lo que permite una comprensión estructurada de la evolución del mercado.

⚡ Características Clave
Arquitectura Deep Learning (LSTM): Captura dinámicas secuenciales y no lineales
Enfoque Híbrido: Clustering (KMeans) + aprendizaje supervisado con LSTM
Análisis Multi-Activo: Diseñado para portafolios diversificados
Modelado Probabilístico: Genera probabilidades de régimen en lugar de etiquetas rígidas
Dashboard Interactivo: Visualización avanzada con Streamlit y Plotly

🧠 Problema que Resuelve
-Los mercados financieros son sistemas no estacionarios, caracterizados por cambios estructurales, clustering de volatilidad y variaciones en correlaciones.
Los modelos tradicionales asumen estabilidad.
Este sistema aborda esa limitación permitiendo:

Identificar estados ocultos del mercado (regímenes)
Detectar transiciones entre regímenes
Construir un framework adaptativo basado en datos para la toma de decisiones cuantitativas

🔗 Documentación Completa
Para una explicación detallada (intuición cuantitativa, arquitectura y aplicaciones):
👉 Notion - Quant Research Note 👉 **[Ver documentación completa en Notion](https://www.notion.so/Clasificador-de-Reg-menes-de-Mercado-con-Deep-Learning-4567f18e4ca282e19af181a93023686e?source=copy_link)**

▶️ Ejecución
streamlit run app.py

Contexto Cuantitativo
Este proyecto forma parte de un framework más amplio de sistemas cuantitativos:
Detección de Regímenes → Selección de Estrategias → Asignación de Portafolio

Proyecto desarrollado como investigación independiente en finanzas cuantitativas y sistemas adaptativos de inversión. SANTIAGO PEÑA DIAZ
