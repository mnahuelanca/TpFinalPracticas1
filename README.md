## Trabajo practico final "Practicas profesionalizastes I"


## Descripción del Proyecto
Este proyecto **simula** un entorno profesional de Ciencia de Datos para un cliente ficticio.  

El objetivo principal es desarrollar un **Modelo de Soporte para la toma de Decisión Clínica** que permita identificar pacientes con alto riesgo de desarrollar diabetes. Esto busca optimizar el tiempo médico y priorizar la atención preventiva.

### Objetivo Técnico
Desarrollar un modelo de clasificación  capaz de predecir la variable (Diabetes: Sí/No) basado en métricas clínicas históricas, logrando un equilibrio ético y técnico.

---

## Equipo y Roles 
Este proyecto fue ejecutado simulando los siguientes roles dentro de un equipo ágil:

| Rol | Responsabilidad Principal |
|:---|:---|
| **Product Owner** | Definición de alcance, gestión del backlog y supervisión ética. |
| **Data Analyst** | Análisis Exploratorio (EDA), calidad de datos y limpieza. |
| **Data Scientist** | Preprocesamiento, entrenamiento del modelo y validación de métricas. |

---

## Stack Tecnológico
* **Lenguaje:** Python
* **Librerías:** Pandas, Scikit-learn, Matplotlib/Seaborn.
* **Gestión de Proyecto:** Trello/Jira (Metodología Scrum/Kanban).
* **Control de Versiones:** Git & GitHub.

---

## Metodología de Trabajo
El proyecto se gestionó mediante un **Sprint de 2 semanas**, siguiendo el siguiente flujo:
1.  **Planificación:** Definición de Historias de Usuario y Sprint Backlog.
2.  **Análisis:** Carga de datos, EDA y limpieza (Rol: Data Analyst).
3.  **Modelado:** Entrenamiento y evaluación (Rol: Data Scientist).
4.  **Entrega:** Documentación y revisión ética (Rol: Product Owner).

---

## Informe de Ética y Responsabilidad Profesional


En el desarrollo de este modelo predictivo de salud, se han considerado los siguientes principios éticos:

### 1. Privacidad y Manejo de Datos
Los datos utilizados provienen de fuentes públicas anonimizadas. No se procesa Información de Identificación Personal real (nombres, DNI, direcciones), garantizando la privacidad de los pacientes simulados según las normativas de protección de datos.

### 2. Sesgos y Equidad
Se reconoce que el dataset puede contener sesgos históricos (ej. predominancia de cierto rango etario o género).
* **Mitigación:** Durante el EDA, se analizó la distribución de clases para identificar desequilibrios.
* **Limitación:** El modelo **no debe utilizarse como única herramienta de diagnóstico**, sino como un sistema de *soporte* secundario para el médico especialista.

### 3. Transparencia y Explicabilidad
Se priorizó el uso de modelos interpretables (o métricas claras), para asegurar que el personal médico pueda entender por qué un paciente fue clasificado como "Riesgo Alto".

---

## Instrucciones de Ejecución
Para replicar este análisis:

1.  Clonar el repositorio:
    ```bash
    git clone https://github.com/mnahuelanca/diabetes-prediccion.git
    ```
2.  Instalar dependencias:
    ```bash
    pip install -r requirements.txt
    ```
3.  Ejecutar el Notebook principal:
    ```bash
    jupyter notebook notebooks/analisis_y_modelo.ipynb
    ```

---

## 📂 Estructura del Repositorio
```text
├── data/                # Dataset original y procesado
├── notebooks/           # Jupyter Notebooks (EDA y Modelado)
├── src/                 # Scripts de soporte (opcional)
├── .gitignore           # Archivos ignorados
├── README.md            # Documentación del proyecto
└── requirements.txt     # Librerías necesarias