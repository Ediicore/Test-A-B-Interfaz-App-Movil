# 🧪 Test A/B - Optimización de Interfaz en App Móvil
Este proyecto consiste en el análisis de un experimento controlado (Test A/B) para una aplicación de venta de productos alimenticios, evaluando si un cambio en el diseño de fuentes afecta las tasas de conversión.

## 🎯 Objetivos del Proyecto
* Analizar el embudo de ventas (Funnel) para identificar dónde abandonan los usuarios.
* Realizar pruebas de hipótesis estadísticas para comparar dos grupos de control contra un grupo de prueba.
* Validar si los resultados del cambio de diseño son estadísticamente significativos.

## 🛠️ Tecnologías Utilizadas
* **Python (Pandas, Plotly)**: Para el análisis del flujo de usuarios y embudos interactivos.
* **Estadística Inferencial**: Pruebas Z y corrección de Bonferroni para comparaciones múltiples.
* **Visualización de Datos**: Gráficos de embudo para representar la pérdida de usuarios en cada paso.

## 📊 Resultados Clave
* Se analizó el comportamiento de **246,129 eventos** de usuario.
* El embudo mostró que la mayor pérdida ocurre en la pantalla de "Ofertas" (solo el 62% avanza).
* **Conclusión:** Las pruebas estadísticas demostraron que el cambio de fuente **no afectó** la conversión, lo que evitó que la empresa gastara recursos en un cambio innecesario.
# 🧪 Test A/B: Optimización de Interfaz en App Móvil
### Análisis Estadístico de Conversión y Embudo de Ventas (Funnel)

---

## 📝 Contexto del Proyecto
Este proyecto consistió en el análisis de un experimento controlado (Test A/B) para una aplicación de retail alimenticio. El desafío era validar si un cambio en el diseño de la interfaz (fuentes) impactaba significativamente en el comportamiento de compra de los usuarios o si se trataba de una fluctuación aleatoria.

## 🎯 Objetivos Clave
* **Análisis de Funnel:** Identificar los puntos críticos de abandono en el proceso de compra (desde el Main Screen hasta el Payment Success).
* **Pruebas de Hipótesis:** Realizar comparaciones estadísticas entre dos grupos de control (A1/A2) y un grupo de prueba (B).
* **Validación de Significancia:** Aplicar correcciones estadísticas para asegurar la integridad de los resultados en comparaciones múltiples.

## 🛠️ Stack Tecnológico
| Herramienta | Uso Principal |
| :--- | :--- |
| **Python (Pandas)** | Procesamiento y limpieza de registros de eventos masivos. |
| **Plotly / Matplotlib** | Creación de embudos de ventas interactivos y visualización de distribución de eventos. |
| **Estadística Inferencial** | Pruebas Z (Z-test) y corrección de Bonferroni para mitigar el error tipo I. |

## 📊 Resultados e Impacto de Negocio
El análisis de **246,129 eventos** permitió llegar a conclusiones financieras estratégicas:
* 📉 **Detección de Fugas:** Se descubrió que la mayor pérdida de usuarios ocurre en la transición a la pantalla de "Ofertas" (solo el **62%** avanza), señalando una oportunidad de optimización de UX.
* 🚫 **Mitigación de Riesgos:** Las pruebas estadísticas demostraron que el cambio de diseño **no generó una diferencia significativa** en la conversión. 
* 💰 **Ahorro Operativo:** Gracias al análisis, se recomendó no proceder con el cambio, evitando gastos innecesarios en desarrollo e implementación de una interfaz que no aportaba valor al negocio.

## 📂 Estructura del Repositorio
* `Test-A-B-Interfaz-App-Movil.ipynb`: Notebook con el flujo completo de validación estadística y visualización de embudos.
* `README.md`: Documentación ejecutiva del experimento.

---

## 🚀 Cómo ejecutar el proyecto
1. **Clona el repositorio:** `git clone https://github.com/Ediicore/Test-A-B-Interfaz-App-Movil.git`
2. **Instala las dependencias:** `pip install pandas plotly matplotlib scipy`
3. **Explora el análisis:** Abre el archivo `.ipynb` en Jupyter Notebook o Google Colab.

---

### 🤝 ¡Conectemos!
**¿Te interesa optimizar la toma de decisiones basada en datos o validar experimentos mediante rigor estadístico?**

📬 **Correo:** edgar.apple08@gmail.com  
💼 **LinkedIn:** [Edgar Emmanuel Estrella Cruz](https://www.linkedin.com/in/edgar-emmanuel-estrella-cruz-1114303a3/)
