# Análisis de Datos de las Tiendas del Sr. Juan

## Descripción

Este proyecto combina el análisis de datos enfocado en las tiendas del Sr. Juan. El objetivo general es proporcionar insights valiosos a partir de los datos de ventas, identificando patrones, tendencias y oportunidades de mejora para ambos escenarios.

**Análisis de las Tiendas del Sr. Juan:** Se presenta un informe detallado basado en datos de múltiples ventas de las Tiendas del Sr. Juan para responder preguntas clave sobre el rendimiento de los productos, categorías, precios y tendencias a lo largo del tiempo. El objetivo es proporcionar información útil para la toma de decisiones en gestión de inventario, marketing y estrategias de precios.

El análisis de Alura Store se implementó en un notebook de Jupyter utilizando las librerías de Python Pandas, Matplotlib y/o Seaborn.

## Estructura del Proyecto y Organización de Archivos

El proyecto se organiza de la siguiente manera:

* `data/`
    * `├── tienda_1.csv`
    * `├── tienda_2.csv`
    * `├── tienda_3.csv`
    * `└── tienda_4.csv`
* `notebooks/`
    * `└── Analisis_tiendas.ipynb`
* `reports/`
    * `└── Informe_Final_Tiendas.pdf`
* `ChallengeAlura.ipynb`
* `README.md`

Cada carpeta contiene lo siguiente:

* **`data/`**: Contiene los conjuntos de datos utilizados para ambos análisis.
  - `tienda_1.csv`.
  - `tienda_2.csv`.
  - `tienda_3.csv`.
  - `tienda_4.csv`.
* **`notebooks/`**: Alberga el notebook con el código de Python para cada análisis `Analisis_tiendasipynb`.
* **`reports/`**: Carpeta para guardar informes generados a partir de ambos análisis`Informe_Final_Tiendas.pdf`.
* **`ChallengeAlura.ipynb`**: Archivo desplegado directamente desde Google colab.
* **`README.md`**: El presente archivo, que proporciona una descripción general del proyecto, instrucciones de uso y otros detalles relevantes.

## Gráficos e Insights Obtenidos

**Análisis de las Tiendas del Sr. Juan:**

1.  **Gráfico de dispersión de Ingresos Totales por Tienda:**

    ![Ventas Totales](https://github.com/user-attachments/assets/ae5dcfb8-3a69-4cbd-9b3c-78bac5c3fe12)

    **Insight:** Identifica la tienda con mayor potencial de ingresos.

2.  **Gráfico de torta de Calificación Promedio por Tienda:**

    ![satisfaccion del cliente](https://github.com/user-attachments/assets/45a57007-2143-433d-b7bf-9a414ab15570)
    
    **Insight:** Muestra la satisfacción del cliente en cada ubicación.


## Instalación y Uso

1.  **Clonar el Repositorio:** Clona este repositorio en tu máquina local utilizando el siguiente comando:
    ```bash
    `git clone https://github.com/Daimond92/analisis-tienda-data-science/tree/main`
    cd [analisis-tienda-data-science]
    ```

2.  **Asegurarse de tener las dependencias instaladas:**

    *  Google Colab ya incluye la mayoría de las librerías necesarias. Si ejecutas el notebook localmente, asegúrate de tener instaladas:
        ```bash
        pip install pandas pyspark matplotlib
        ```

3.  **Ejecutar los Notebooks:**

    * **Análisis de las Tiendas del Sr. Juan (`analisis_sr_juan.ipynb`):** Abre el archivo usando Google Colab. Carga los datos de las tiendas del Sr. Juan (reemplazando el archivo de ejemplo si es necesario) en el entorno de Colab y ejecuta las celdas secuencialmente.

4.  **Explorar y Experimentar:** Puedes modificar los notebooks para realizar análisis adicionales y generar nuevas visualizaciones para ambos conjuntos de datos.

## Tecnologías Utilizadas

-   **Google Colab**: Entorno de desarrollo interactivo basado en la nube para el análisis de datos.
-   **Python**: Lenguaje de programación principal utilizado para ambos análisis.
-   **Pandas**: Librería fundamental para la manipulación y análisis de datos en ambos proyectos.
-   **Pyspark**: Librería para el procesamiento distribuido de datos y funcionalidades SQL (utilizada en el análisis del Sr. Juan).
-   **Matplotlib**: Librería para la creación de gráficos y visualizaciones en ambos proyectos.
-   **Seaborn**: Librería de visualización de datos basada en Matplotlib (utilizada en el análisis de Alura Store).
-   **Github**: Plataforma de control de versiones y colaboración para la gestión del código fuente del proyecto.

## Estado del Proyecto

-   **Finalizado**: El análisis se considera completo y funcional, entregando insights relevantes para los datos proporcionados.

## Requisitos del Entorno de Desarrollo

Se recomienda utilizar las siguientes herramientas:

-   **Editor de código**: Google Colab.
-   **Git**: Para clonar el repositorio y gestionar el código fuente.
-   **Librerías de Python**: Asegúrate de tener instaladas las librerías mencionadas en la sección de Instalación y Uso.

## Derechos de Autor

Los derechos de autor de este proyecto pertenecen a **David Alejandro Malaver Arévalo**.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un **fork** del repositorio y enviar un **pull request** con tus cambios. Especifica claramente a qué parte del análisis corresponden tus contribuciones.

### Pasos para contribuir:

1.  Haz un fork de este repositorio.
2.  Crea una rama nueva para tus cambios.
3.  Realiza tus modificaciones.
4.  Haz commit de tus cambios.
5.  Sube tus cambios a tu fork en GitHub.
6.  Envía un pull request detallando lo que has cambiado y a qué análisis afecta.

## Contacto

Si tienes preguntas o sugerencias sobre el análisis, no dudes en contactarnos a través del siguiente correo electrónico:

-   **Email**: [d-malaver@outlook.com](mailto:d-malaver@outlook.com)
