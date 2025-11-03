Este proyecto contiene tres notebooks que abordan el **Problema de Asignación Cuadrática (QAP)** usando diferentes técnicas de **metaheurísticas**.  
El objetivo es comparar cómo distintos métodos de optimización aproximada buscan soluciones de calidad en un problema combinatorio difícil.

---

## 📘 Contenido

### 1️⃣ `01_Local_Search_QAP.ipynb`
Implementa **búsquedas locales** sobre permutaciones del QAP.  
- Usa un vecindario basado en **intercambio de posiciones (2-opt)**.  
- Evalúa estrategias de mejora (**first-improvement** y **best-improvement**).  
- Permite observar cómo la búsqueda local explora el espacio de soluciones y cuándo se estanca en óptimos locales.

---

### 2️⃣ `02_Simulated_Annealing_QAP.ipynb`
Desarrolla la metaheurística de **Enfriamiento Simulado (Simulated Annealing)**.  
- Parte de una solución inicial y acepta movimientos peores con cierta probabilidad dependiente de la **temperatura**.  
- A medida que la temperatura baja, el algoritmo se vuelve más estricto y converge.  
- Se estudia el efecto de parámetros como la temperatura inicial, el factor de enfriamiento y el número de iteraciones.

---

### 3️⃣ `03_QAP_GA_Comparison.ipynb`
Implementa y compara tres **Algoritmos Genéticos (GA)** distintos aplicados al QAP:
- **AGS:** Genético simple (selección por torneo, cruce OX, mutación).  
- **CHC:** Variante con control de diversidad mediante distancia de Hamming.  
- **GA Multimodal:** Usa *clearing* para mantener varios nichos de soluciones.



