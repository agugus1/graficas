abrir el user csv. mostrar la columna pais y edad, ordenar la columna edad y mostrar los 5 usuarios mas viejos de alemania. 

investigar los diferentes tipos de graficos ofrecidos por seaborn
Acá van los principales tipos de gráficos que ofrece Seaborn:

---

**Gráficos relacionales** (relación entre variables numéricas)
- `sns.scatterplot()` → puntos dispersos entre dos variables
- `sns.lineplot()` → línea que conecta valores

---

**Gráficos de distribución** (cómo se distribuyen los datos)
- `sns.histplot()` → histograma
- `sns.kdeplot()` → curva de densidad suavizada
- `sns.rugplot()` → pequeñas marcas sobre el eje

---

**Gráficos categóricos** (para variables de categorías)
- `sns.barplot()` → barras con promedios
- `sns.countplot()` → cuenta cuántas veces aparece cada categoría
- `sns.boxplot()` → muestra mediana, cuartiles y outliers
- `sns.violinplot()` → combinación de boxplot y distribución
- `sns.stripplot()` → puntos individuales por categoría
- `sns.swarmplot()` → igual que strip pero sin superposición

---

**Gráficos de regresión**
- `sns.regplot()` → scatter con línea de regresión

---

**Gráficos de matriz**
- `sns.heatmap()` → mapa de calor con colores según valores

---

**Gráficos múltiples**
- `sns.pairplot()` → scatter entre todas las columnas numéricas
- `sns.jointplot()` → scatter entre dos variables con distribución en los bordes
