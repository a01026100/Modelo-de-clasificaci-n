# Análisis de Ciencia de Datos

## 📄 Descripción

Este notebook aborda un reto de análisis de datos que incluye la **exploración**, **limpieza**, **ingeniería de características**, **modelado** y **evaluación** de un conjunto de datos real. El objetivo es extraer insights accionables y construir un modelo predictivo robusto.

## 📁 Estructura del repositorio

```bash
.
├── data/                                # Datos originales (CSV, JSON, etc.)
│   └── dataset.csv                      # Dataset principal
├── notebooks/                           # Notebooks organizados por fase
│   └── Reto-Analisis-CienciaDeDatos.ipynb  # Notebook principal
├── docs/                                # Documentación
│   └── screenshots/                     # Capturas de pantalla de outputs clave
├── environment.yml or requirements.txt  # Dependencias del proyecto
└── README.md                            # Este archivo
```

## 🚀 Uso

1. Abre el notebook en Jupyter o Colab:

   ```bash
   jupyter lab notebooks/Reto-Analisis-CienciaDeDatos.ipynb
   ```
2. Ejecuta las celdas en orden:

   1. **Carga y exploración de datos**
   2. **Limpieza e imputación**
   3. **Análisis exploratorio (EDA)**
   4. **Ingeniería de características**
   5. **Entrenamiento de modelos**
   6. **Evaluación y validación**

## 🧭 Metodología

1. **EDA**: estadísticas descriptivas, detección de outliers, correlaciones.
2. **Preprocesamiento**: manejo de valores faltantes, codificación de variables categóricas y escalado.
3. **Modelado**: comparación de al menos dos algoritmos supervisados (por ejemplo, Random Forest y XGBoost).
4. **Validación**: validación cruzada, métricas de desempeño (RMSE, Accuracy, AUC, según el caso).
5. **Interpretación**: análisis de importancia de variables y conclusiones basadas en los resultados.

## 📸 Capturas de pantalla

Modelo de Arbol de decision con Undersampling

<img width="700" alt="image" src="https://github.com/user-attachments/assets/d5129fd7-cb8b-450a-af28-8dda9474df22" />

El undersampling reduce aleatoriamente muestras de la clase mayoritaria para equilibrar las clases, evitando sesgos del modelo a costa de perder algo de información.

Encontrar las variables más relevantes

<img width="848" alt="image" src="https://github.com/user-attachments/assets/8dec8f81-04df-4a78-b9f1-1a3553fab57b" />

Ordena los índices de las características según su importancia (de mayor a menor), imprime las columnas junto con sus valores de feature_importances_ en ese orden, y luego dibuja el árbol de decisión (best_clf) con los nombres de las variables y las clases etiquetadas, mostrando la estructura del modelo hasta una profundidad de 2 niveles.





## 📈 Resultados clave

<img width="607" alt="image" src="https://github.com/user-attachments/assets/0608e29b-820d-405a-b56b-79dad3a18ccd" />

<img width="604" alt="image" src="https://github.com/user-attachments/assets/368eba9d-58d0-448f-ba3a-d43adccf2d96" />



* El mejor modelo (Undersampling) alcanzó un **recall** de 0.7  y un **Accuracy** de 69 % en el conjunto de prueba.
* Las variables más relevantes fueron `var1`, `var2` y `var3`, que explican más del 60 % de la varianza del modelo.


**Conclusión:** El enfoque de limpieza rigurosa, selección de características y comparación de algoritmos permitió desarrollar un modelo sólido, escalable y fácil de actualizar con nuevos datos.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Haz un fork, crea una rama y envía un pull request.

## 👤 Contacto

Pablo Pérez – [github.com/tu-usuario](https://github.com/tu-usuario)
Email: [tu.email@ejemplo.com](mailto:tu.email@ejemplo.com)
