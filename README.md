# 🎮 Análisis Estratégico del Mercado Global de Videojuegos (1980-2016)

## 📌 Visión General
Como **Analista de Datos**, he desarrollado este proyecto para transformar un dataset de más de 16,000 registros en **inteligencia de negocios**. El análisis no solo muestra números, sino que identifica patrones de consumo que ayudan a tomar decisiones sobre inversión en desarrollo y estrategias de marketing regional.



---

## 🚀 Preguntas de Negocio Resueltas

### 1. 📈 Evolución y Cuota de Mercado (Market Share)
**Problema:** ¿Hacia dónde se mueve el dinero?
- **Análisis:** Visualización de áreas apiladas para ver la dominancia de géneros.
- **Insight:** Los géneros *Platform* dominaron los 80/90, pero fueron desplazados por *Action* y *Shooter*, que hoy representan el motor financiero de la industria.

### 2. 🔄 Ciclo de Vida: El Duelo PS3 vs PS4
**Problema:** ¿Cuándo es el momento óptimo para abandonar una tecnología vieja?
- **Análisis:** Comparación temporal de ventas entre generaciones.
- **Insight:** Identificamos el punto de "crossover" donde la PS4 superó a la PS3, marcando el fin de la rentabilidad del hardware antiguo.

### 3. 🗺️ Estrategia de Localización (Japón vs. Norteamérica)
**Problema:** ¿Podemos usar el mismo marketing en todo el mundo?
- **Análisis:** Matriz de correlación de Pearson y Top 5 regional.
- **Insight:** La baja correlación entre JP y NA confirma que Japón requiere una estrategia enfocada en *Role-Playing*, mientras que en NA el foco debe ser *Action*.

### 4. 🎯 El Principio de Pareto (Los "Hits")
**Problema:** ¿Dependemos de pocos juegos o del volumen?
- **Análisis:** Cálculo de concentración de ventas del Top 50.
- **Insight:** Una minoría de títulos genera la mayoría de los ingresos globales, validando la estrategia de "Alta Calidad sobre Cantidad".

### 5. 🏆 Eficiencia de los Competidores (Benchmarking)
**Problema:** ¿Quién es el Publisher más inteligente (no el más grande)?
- **Análisis:** Promedio de ventas por título filtrando ruido estadístico.
- **Insight:** Identificamos qué empresas tienen el mejor "ojo" comercial al lograr promedios de ventas más altos por cada juego lanzado.

---

## 🛠️ Stack Técnico y Funciones Utilizadas
- **Limpieza de Datos:** Manejo de valores nulos y filtrado de años inconsistentes.
- **Pandas:** `groupby()`, `unstack()`, `pivot_table()`, `isin()`, `nlargest()`.
- **Estadística:** Coeficientes de correlación y normalización de ejes (`axis=0`).
- **Visualización:** `plt.stackplot()`, `sns.heatmap()`, `plt.plot(marker='o')`.

---

##  Cómo navegar este proyecto
1.  **`Untitled37.ipynb`**: Contiene todo el proceso de ETL (Extracción, Transformación y Carga) y visualización.
2.  **`vgsales.csv`**: Fuente de datos cruda.
   




---
