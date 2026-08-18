# Herramientas-de-Datos-Moran-Maria
Análisis de DataSet para Proyecto Final de Curso Agos2026, utilizando herramientas como Excel, Python y Power BI
# 🏈 Proyecto Final: El Lado Oculto de los Anuncios de la Super Bowl (2000-2021)

**Autor:** Maria Isabel Moran  
**Curso:** Herramientas de Análisis de Datos  
**Cohorte:** Agosto 2026  

---

### 🚀 ¿De qué viene este proyecto?
En este proyecto me metí de lleno a analizar la evolución y el impacto de los comerciales de la Super Bowl usando un combo potente: **Python**, **Power BI** y **GitHub**. La idea fue meter las manos en el código para responder tres preguntas clave: qué marcas mandan en el evento, cómo cambiaron los anuncios con los años y qué fórmulas mágicas hacen que un comercial la rompa en internet.

### 🛠️ El paso a paso (¡lo que se hizo!)

1. **Limpieza a fondo:** Importé el dataset de comerciales y pasé todo el contenido al español para entenderlo mejor. Como la vida real no es perfecta, me encontré con varios datos faltantes en las métricas de YouTube, así que los rellené con ceros y reajusté las vistas a millones y los "me gusta" a miles para que los gráficos no fueran un dolor de cabeza.
2. **Cazando valores locos (*Rangos Anomalos*):** Usando histogramas y diagramas de caja de **Seaborn**, busqué si había errores. ¿Qué descubrí? Que las duraciones extra largas (de hasta 180 segundos) o videos virales con millones de reproducciones no eran fallos del sistema, ¡sino comerciales que se hicieron recontra virales!
3. **Exportación mundial:** Con los datos limpios y brillantes, exporté todo a un archivo llamado `data_power.csv` para armar un tablero interactivo espectacular en **Power BI**.

---

### 📊 Los Descubrimientos Clave

* **La reina de la publicidad:** La marca con más comerciales en la historia de la Super Bowl es ***Bud Light*** con **62 anuncios**, seguida por *Budweiser* con 43.
* **Evolución en el tiempo:** Al cruzar los años con las variables, se nota un salto gigante en el costo estimado promedio de los anuncios y cambios claros en las estrategias: pasamos de usar humor simple a meter cada vez más celebridades y animales.
* **La receta del éxito:** Comparando las métricas con variables lógicas (Sí/No), descubrí qué características disparan las vistas y los *likes* en YouTube. El contenido divertido, los animales y los cameos de famosos son los reyes del enganche.

---

### 📖 Fuentes e Imágenes
* **Dataset Base:** mavenanalytics.io** 
* **Archivo Histórico:** /content/superbowl_commercials.csv *.
* **Librerías de código:** pandas, matplotlib.pyplot, seaborn, plotly.express 
