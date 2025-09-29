# Dataset sintético - Deserción estudiantil

Este dataset fue creado para el taller de Aprendizaje Supervisado vs No Supervisado.  
Contiene 500 registros simulados de estudiantes y busca predecir si un estudiante deserta (Sí/No).

## 📊 Variables incluidas

- **Edad**: Entero, entre 16 y 30 (con algunos valores atípicos mayores de 40).  
- **Género**: Categórico (M/F).  
- **Ciudad_Origen**: Categórico (Urbano/Rural).  
- **Promedio_Colegio**: Decimal, 0–5 (algunos valores -1 como atípicos).  
- **Examen_Admision**: Entero, 0–100 (con algunos nulos).  
- **Notas_Primer_Semestre**: Decimal, 0–5 (con nulos).  
- **Nivel_Socioeconomico**: Entero, 1–6.  
- **Beca**: Categórico (Sí/No).  
- **Credito**: Categórico (Sí/No).  
- **Desercion**: Variable de salida (Sí/No).  

## ⚠️ Detalles especiales
- Se introdujeron **nulos** en algunas variables académicas.  
- Se agregaron **valores atípicos**: promedios negativos (-1) y edades > 40.  
- Distribución: aproximadamente 30% de estudiantes desertan.  

## 📂 Uso
Este dataset puede usarse para entrenar y evaluar modelos de Machine Learning, especialmente **clasificación supervisada** (regresión logística, árboles de decisión, etc.).

---
