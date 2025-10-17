# 🦈 Shark Attacks – Data Wrangling Project (Ironhack)

Proyecto del Bootcamp de **Data Analytics & AI – Ironhack**, enfocado en la **limpieza, análisis y visualización** de datos de ataques de tiburones a lo largo de la historia.

El objetivo principal es practicar técnicas de **Data Wrangling** (limpieza, formateo y transformación de datos) con Python y Pandas, y obtener conclusiones visuales sobre los factores que influyen en los incidentes.

---

## 🎯 Objetivos del proyecto
- Limpieza de datos (valores nulos, duplicados, formatos inconsistentes…).
- Normalización/traducción de columnas.
- Análisis por país, año, especie, momento del día y gravedad.
- Visualizaciones con **Matplotlib**.


---

## 📂 Estructura del repositorio
```
 shark-attacks/
│
├── data/
│ ├── raw/ # Datos originales (sin modificar) – ignorados por Git
│ └── processed/ # Datos limpios mínimos para reproducir el análisis
│
├── figures/ # Gráficos generados y versionados (.png)
│ ├── 01_especie_grupo_quesito.png
│ ├── 02_gravedad_por_especie_grouped.png
│ ├── 03_hora_linea.png
│ ├── 04_incidentes_por_hora.png
│ ├── 04b_incidentes_por_momento.png
│ ├── 05_incidentes_por_mes.png
│ └── 05b_top10_paises.png
│
├── notebooks/
│ └── proyecto1.1.ipynb # Notebook principal de análisis
│
├── Borrador.md
├── LICENSE
├── .gitignore
└── README.md
```



---

## ⚙️ Requisitos y ejecución

1. **Clonar**
   ```bash
   git clone https://github.com/adrianrubio-data/shark-attacks.git
   cd shark-attacks
   python -m venv venv
   venv\Scripts\activate   # Windows
      # source venv/bin/activate  # macOS/Linux

      pip install pandas numpy matplotlib jupyter

      jupyter notebook notebooks/proyecto1.1.ipynb
    ```


## 📊 Resultados principales
- Evolución temporal y estacionalidad (por horas y meses).
- Distribución por especies y gravedad.
- Ranking de países y comparativas por momento del día.

---

## 🧠 Tecnologías utilizadas
| Herramienta | Uso |
|-------------|-----|
| **Python** | Lenguaje |
| **Pandas** | Limpieza y manipulación |
| **NumPy** | Soporte numérico |
| **Matplotlib** | Visualización |
| **Jupyter** | Entorno interactivo |

---

## 👥 Equipo
- 🧑‍💻 [Adrián Rubio (Frankie)](https://github.com/adrianrubio-data) – Data Cleaning & Visualización  
- 👩‍💻 [Nerea Gómez](https://github.com/NereaGomez9) – Análisis & Documentación

---

## 🪪 Licencia
MIT.
