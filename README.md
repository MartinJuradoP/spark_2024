# Curso de Spark desde Cero 🚀

¡Bienvenido al curso de Apache Spark! En este curso aprenderás a trabajar con Spark desde los conceptos básicos hasta el procesamiento de datos avanzado. Este repositorio contiene los datos y recursos necesarios para que practiques durante el curso.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```
curso-spark
├── notebooks               # Notebooks Jupyter
│   ├── data                # Carpeta con los datos del curso
│   │   ├── departments.csv     # Datos de los departamentos
│   │   ├── employees.csv       # Datos de los empleados
│   │   └── jobs.csv            # Datos de las posiciones (jobs)
├── scripts                 # Scripts Python para ejemplos prácticos
└── README.md               # Este archivo

```

### Contenido de la carpeta `data`

1. **`departments.csv`**: Contiene la información de los departamentos de la empresa.
   - **Columnas**:
     - `id`: Identificador único del departamento.
     - `departamento`: Nombre del departamento.
   - **Ejemplo**:
     ```
     id,departamento
     1,Product Management
     2,Sales
     3,Research and Development
     ```

2. **`employees.csv`**: Contiene los datos de los empleados.
   - **Columnas**:
     - `id`: Identificador único del empleado.
     - `nombre`: Nombre completo del empleado.
     - `fecha de ingreso`: Fecha y hora en que el empleado se unió a la empresa (formato ISO 8601).
     - `departamento`: Identificador del departamento al que pertenece el empleado (relación con `departments.csv`).
     - `posición`: Identificador de la posición (relación con `jobs.csv`).
   - **Ejemplo**:
     ```
     id,nombre,fecha de ingreso,departamento,posición
     1,Harold Vogt,2021-11-07T02:48:42Z,2,96
     2,Ty Hofer,2021-05-30T05:43:46Z,8,
     ```

3. **`jobs.csv`**: Contiene la información de las posiciones dentro de la empresa.
   - **Columnas**:
     - `id`: Identificador único de la posición.
     - `posición`: Nombre de la posición.
   - **Ejemplo**:
     ```
     id,posición
     1,Software Engineer
     2,Data Scientist
     3,Product Manager
     ```


¡Disfruta el curso! 🚀
