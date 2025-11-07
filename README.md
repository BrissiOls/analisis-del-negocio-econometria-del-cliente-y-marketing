# 📈 Optimización de Gastos de Marketing y Análisis de Rentabilidad (Showz)

## 🎯 Objetivo del Proyecto

El objetivo principal fue optimizar los gastos de marketing de Showz (venta de entradas) mediante un análisis profundo de la rentabilidad por fuente de adquisición, los patrones de uso del servicio y la evaluación del retorno de la inversión ($\text{ROMI}$) a lo largo del periodo Ene/2017 - Dic/2018.

## 🛠️ Metodología y Herramientas

Se empleó un enfoque de análisis de *cohortes* para calcular métricas financieras y de comportamiento, basándose en tres conjuntos de datos: visitas al servidor, pedidos y costos de marketing.

* **Lenguaje y Librerías:** **Python** (`pandas`, `numpy`) fue utilizado para la limpieza de datos, estructuración de *cohortes* (especialmente para $\text{LTV}$) y cálculo de métricas financieras.
* **Visualización:** `seaborn` y `matplotlib` para trazar la evolución de métricas ($\text{LTV}$, $\text{CAC}$, $\text{ROMI}$) por fuente de adquisición y tiempo.
* **Métricas Clave Calculadas:** **LTV** (Valor de vida del cliente), **CAC** (Costo de adquisición de clientes), **ROMI** (Retorno de la inversión en marketing).

## 📊 Hallazgos y Resultados Clave

El análisis reveló oportunidades críticas para la reasignación presupuestaria y la mejora de la retención:

| Métrica / Hallazgo | Descripción | Impacto |
| :--- | :--- | :--- |
| **Fuente Más Rentable** | **Fuente 1** posee el $\text{ROMI}$ más alto, con un valor de **60**. | **Recomendación:** Priorizar la inversión en esta fuente para maximizar el retorno. |
| **Fuente No Rentable** | **Fuente 3** (la más invertida) genera pérdidas. La diferencia ($\text{LTV}-\text{CAC}$) es de **-41.82**. | **Acción Inmediata:** Reducir o suspender la inversión en la Fuente 3 y reasignar fondos. |
| **Retención Crítica** | La tasa de retención es muy baja: el **97% de los clientes nuevos** no regresan el segundo mes. | **Foco Estratégico:** Urge crear estrategias de *engagement* y fidelización post-primera compra. |
| **Velocidad de Compra** | El tiempo promedio para la **primera compra es menor a 1 día**. | **Oportunidad:** Alta velocidad de conversión inicial, pero bajo *LTV* a largo plazo. |
| **Patrón de Uso** | Promedio de **908 visitantes diarios**. El **75%** de los clientes inician sesión solo una vez a la semana. | **Conclusión:** El servicio es utilizado bajo demanda o una vez por semana. |

## ✅ Conclusiones y Recomendaciones

1.  **Optimización de Gasto:** Se recomienda reasignar el presupuesto invertido en la Fuente 3 a las fuentes **1 y 9** para capitalizar su alta rentabilidad ($\text{ROMI} \ge 60$).
2.  **Estrategia de Retención:** Los recursos deben enfocarse en el primer mes de vida del cliente para mejorar la **tasa de retención**, que es crítica, y aumentar el valor $\text{LTV}$ a largo plazo.
3.  **Tendencias:** Existe un pico de visitas durante Noviembre/2017 a Febrero/2018, lo que puede guiar la planificación de futuras campañas estacionales.


