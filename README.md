# Challenge_TelecomX
# 📊 Análisis de Churn en Clientes de Telecomunicaciones  

Este proyecto tiene como objetivo **analizar y comprender los factores que influyen en la rotación de clientes (Churn)** dentro de una empresa de telecomunicaciones, con el fin de generar *insights* y proponer estrategias de retención.  

---

## 🔍 Proceso de Trabajo  

1. **Preparación de Datos**  
   - Importación y estructuración de datos JSON en Pandas.  
   - Limpieza de valores ausentes, duplicados y cadenas vacías.  
   - Transformación de variables binarias y estandarización de columnas.  
   - Generación de nuevas características como `Cuentas_Diarias`.  

2. **Análisis Exploratorio de Datos (EDA)**  
   - **Distribución del Churn:** desbalance significativo entre clientes que se quedan y los que abandonan.  
   - **Variables categóricas:** contratos *“Mes a Mes”*, uso de *Fibra Óptica* y *Facturación Electrónica* asociados a mayor rotación.  
   - **Variables numéricas:** menor antigüedad y cargos extremos (altos o bajos) correlacionados con Churn.  
   - **Correlaciones clave:** relación negativa entre `Antiguedad_Meses` y Churn.  

3. **Conclusiones e Insights**  
   - Los **nuevos clientes con contratos flexibles** son más vulnerables.  
   - Algunos **servicios específicos** generan mayor riesgo de abandono.  
   - La **antigüedad** es un factor protector fuerte frente a la rotación.  

4. **Recomendaciones Estratégicas**  
   - Programas de bienvenida e incentivos para contratos de mayor duración.  
   - Optimización de calidad en *Fibra Óptica* y *Facturación Electrónica*.  
   - Revisión de precios para clientes con cargos extremos.  
   - Programas de fidelización basados en antigüedad.  

---

## 🛠️ Tecnologías Utilizadas  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  

---

## 📌 Próximos Pasos  
- Construcción de modelos predictivos de Churn (Machine Learning).  
- Segmentación avanzada de clientes para estrategias personalizadas.  

---

✍️ *Proyecto desarrollado como práctica de análisis de datos y generación de insights accionables.*
