# 📁 Pandas ES: Trabajando con diferentes formatos de archivo

Este repositorio contiene un notebook interactivo que muestra cómo usar **Pandas** para leer, manipular y guardar datos en distintos **formatos de archivo**: CSV, Excel, JSON, TXT, Parquet, entre otros.

## 🎯 Objetivos del proyecto

  - Aprender a cargar datos en Pandas desde múltiples fuentes.
  - Conocer las opciones avanzadas de lectura y escritura (separadores, hojas, índices).
  - Exportar DataFrames en diferentes formatos.
  - Comprender cuándo elegir cada formato según el contexto.
  - Ejemplificar un flujo completo: desde `data_in/` hasta `data_out/`.

## 📂 Estructura del repositorio

  Pandas-ES-trabajando-con-diferentes-formatos-de-archivo/
  ├── data_in/ # Archivos de entrada (CSV, XLSX, JSON…)
  ├── data_out/ # Archivos generados tras la transformación
  ├── notebooks/
  │ └── formatos.ipynb # Notebook principal: lectura y escritura de archivos
  └── README.md

## ▶️ Cómo ejecutar el notebook

### Opción 1: Local

```bash
git clone https://github.com/Sebas1020h/Pandas-ES-trabajando-con-diferentes-formatos-de-archivo.git
cd Pandas-ES-trabajando-con-diferentes-formatos-de-archivo/notebooks
pip install pandas pyarrow openpyxl
jupyter notebook formatos.ipynb
```

Opción 2: Google Colab

Haz clic aquí para abrirlo directamente:

📌 Lo que aprenderás

  pd.read_csv(), read_excel(), read_json(), read_table(), read_parquet(), etc.
  
  Manejo de parámetros como sep, sheet_name, index_col, dtype, engine, etc.
  
  Exportar datos usando to_csv(), to_excel(), to_json(), to_parquet().
  
  Comparativa de formatos: facilidad, rendimiento, preservación de tipos, compresión.
  
  Buenas prácticas sobre dónde mantener los datos data_in/ vs data_out/.

🙌 Créditos y agradecimientos

  Este proyecto fue desarrollado como parte del curso de análisis de datos con Python, impartido en Alura LATAM.

Agradecimientos especiales a:

👨‍🏫 Alejandro Gamarra

  Docente del programa de formación en ciencia de datos - Alura LATAM
  Por su acompañamiento pedagógico y su claridad en el uso de Pandas para trabajar con distintos formatos.

🤝 Contribuciones

Este proyecto es de código abierto. Si deseas aportar nuevos ejemplos, mejorar documentación o adaptar el notebook a otros formatos, ¡eres bienvenido!

  Pasos para contribuir:
  
  Haz un fork del repositorio.
  
  Crea una nueva rama: git checkout -b mejora-o-nuevo-ejemplo.
  
  Haz commit de tus cambios y push.
  
  Abre un pull request y describe tu aporte.

📚 Recursos útiles

  Documentación oficial de Pandas(https://pandas.pydata.org/)
  
  Guía para leer JSON y Parquet con Pandas(https://pandas.pydata.org/docs/user_guide/io.html)
  
  Alura LATAM (https://www.aluracursos.com/latam)

🧠 Autor

  Sebastián Urrego
  
  GitHub: @Sebas1020h
  
  Proyectos educativos y de ciencia de datos con Python.

“Cada formato de archivo es una ventana diferente al conocimiento. Lo importante es saber cómo abrirla.” 📊
