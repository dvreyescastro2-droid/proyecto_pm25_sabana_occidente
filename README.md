# Proyecto PM2.5 Sabana Occidente

## Análisis ambiental del material particulado PM2.5 mediante métodos numéricos y Python

### Descripción del proyecto

Este proyecto ambiental tiene como objetivo analizar el comportamiento del material particulado PM2.5 en municipios de la Sabana Occidente de Cundinamarca mediante la aplicación de métodos numéricos y herramientas de análisis de datos en Python.

El estudio se desarrolló utilizando información ambiental organizada a partir de tendencias reales de calidad del aire y variables meteorológicas representativas de los municipios de Mosquera, Funza, Madrid y Facatativá.

---

## Objetivo general

Analizar las concentraciones de PM2.5 mediante la aplicación del método de regresión por mínimos cuadrados propuesto por Steven C. Chapra y Raymond P. Canale en el libro *Métodos Numéricos para Ingenieros*.

---

## Variables analizadas

- PM2.5
- Temperatura
- Humedad relativa
- Velocidad del viento
- Calidad del aire
- Fuente contaminante

---

## Método numérico aplicado

El proyecto implementa el método de regresión lineal múltiple por mínimos cuadrados para modelar el comportamiento del PM2.5 a partir de variables meteorológicas.

Modelo matemático aplicado:

$$
PM_{2.5} = a_0 + a_1(T) + a_2(H) + a_3(V)
$$

---

## Herramientas utilizadas

- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook
- GitHub
- Git Bash
- Visual Studio Code

---

## Estructura del proyecto

```text
proyecto_pm25_sabana_occidente/
│
├── data/
│   └── datos_pm25_sabana.csv
│
├── notebooks/
│   ├── 01_lectura_datos.ipynb
│   ├── 02_analisis_exploratorio.ipynb
│   ├── 03_graficas_pm25.ipynb
│   ├── 04_regresion_minimos_cuadrados.ipynb
│   └── 05_conclusiones_finales.ipynb
│
├── docs/
│   └── resultados_finales_pm25.csv
│
├── imagenes/
│
├── README.md
└── requirements.txt
```

---

## Resultados principales

- Mosquera y Funza presentaron mayores concentraciones de PM2.5 debido a actividades industriales y tráfico vehicular.
- Facatativá presentó menores concentraciones asociadas a mejores condiciones de ventilación atmosférica.
- El modelo matemático obtuvo un coeficiente de determinación:

$$
R^2 = 0.9875
$$

lo que indica una alta capacidad predictiva del modelo.

---

## Autores

- Dennis Reyes
- Lizeth León

---

## Referencias

Chapra, S. C., & Canale, R. P. (2015). *Métodos numéricos para ingenieros* (7.ª ed.). McGraw-Hill Education.

IDEAM. (2023). *Informe del estado de la calidad del aire en Colombia*.

Ministerio de Ambiente y Desarrollo Sostenible. (2022). *Política de gestión de la calidad del aire en Colombia*.

